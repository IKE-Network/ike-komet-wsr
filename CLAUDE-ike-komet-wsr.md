# ike-komet-wsr — Project Notes

<!-- This file is for hand-authored, project-specific information.
     It is created by ws:scaffold-init but never overwritten.
     Commit this file to git. -->

## Public ids: comparison, keys and derivation

A component's `PublicId` is one or more UUIDs, any of which identifies it; a component may
rarely gain UUIDs when two are found equivalent. The full contract is in `PublicId`'s javadoc.

- Two public ids are **equal when they share any UUID**, in any order (`PublicId.equals`). That
  equality is not transitive, and `hashCode` is not consistent with it, by design.
- **Never key a hash collection by a public id**: no `HashMap`/`HashSet`/`ConcurrentHashMap` keys,
  no `Collectors.toSet()` or `distinct()` over public ids, no cache keyed by one.
- A sorted collection (`TreeSet`, `TreeMap`) is fine when "the same UUIDs" is the question: it
  compares the sorted UUIDs whole.
- When "the same component" is the question: **within a store, key by nid**; outside one, match
  single UUIDs or compare with `PublicId.equals`.
- A shared UUID proves identity, the first or any other; a differing first UUID proves nothing,
  so compare the rest (`PublicId.equals`) before concluding two components differ, and never key
  by one UUID (`asUuidArray()[0]`). A UUID derived by hashing a component's (type 5) takes its
  least UUID.
- `PublicIdHashKeyGuardTest` (tinkar-core integration, komet framework) fails the build on a
  hash collection keyed by a public id in main code (exception marked
  `// public-id-hash-key: <reason>`), and on a first UUID taken as an identity:
  `asUuidArray()[0]`, `asUuidList().get(0)`/`getFirst()`, protobuf `getUuids(0)` (exception
  marked `// first-uuid: <reason>`; the record layout's head/rest split in
  `PublicIdentifierRecord.make` is the one). Derive from `publicId.leastUuid()` (signed
  `UUID.compareTo`), compare with `PublicId.equals`, show `idString()`, write record headers with
  `PublicIdentifierRecord.make`, and carry every UUID in protobuf and text formats.
- When content names an existing component under UUIDs the store does not hold, the store adds
  them to the component and raises an advisory (`IdentityAdvisories`); a public id whose UUIDs
  belong to more than one existing component is advised too, and not yet reconciled.

## Architecture

## Key Classes

## Testing Notes
