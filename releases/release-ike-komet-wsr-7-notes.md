# What changed — mission ike-komet-wsr-7 (2026-08-17)

## tinkar-schema 1.43.4  ·  1.43.3 → 1.43.4

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## komet-bom 3.0.11  ·  3.0.10 → 3.0.11

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## ike-commonmark-attributes 1.0.4  ·  1.0.3 → 1.0.4

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## tinkar-core 1.127.6  ·  1.127.5 → 1.127.6

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **Skip local Lucene indexing when using gRPC mode**
  feature/grpc_search_group
  ## komet-desktop (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## komet-grpc-plugin (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## tinkar-core (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## workspace (2 commits)
  - ws: re-derive depends-on edges
  - workspace: update branches for feature/grpc_search_group

## ike-knowledge-provider 5  ·  4 → 5

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## komet-grpc-plugin 5  ·  4 → 5

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **Skip local Lucene indexing when using gRPC mode**
  feature/grpc_search_group
  ## komet-desktop (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## komet-grpc-plugin (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## tinkar-core (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## workspace (2 commits)
  - ws: re-derive depends-on edges
  - workspace: update branches for feature/grpc_search_group

## tinkar-composer 1.14.4  ·  1.14.3 → 1.14.4

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## rocks-kb 0.1.4  ·  0.1.3 → 0.1.4

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## komet 1.59.4  ·  1.59.3 → 1.59.4

- **Instruction Editor: one editing surface, settled categories, Assistant drawer**
  Focus-or-create replaces the assistant card's escape editor window: a
  MakeCardWindowEvent on the journal topic fronts the open Instruction Editor
  card or creates one; the tabbed Stage and the card-override writers are
  deleted.
  Categories settle to System Prompt | Skill | Tool Contract. General is
  retired (unknown or absent parses to Skill), and versioned seeding gives
  every category a read-only system default, refreshing OUR defaults in place
  on generation bumps.
  Drafting assistance lands as an in-flow Assistant drawer under one
  full-width title bar: per-set conversations (in-memory this increment),
  discussion in text with revisions arriving only through the propose_document
  tool, reviewed as word-level track changes (MarkdownDiff) with Revert and
  Revert draft; manual edits show as track changes too. The editor mirrors the
  portable form's order — name, auto-growing routing description, the
  category / read-only / View|Edit mode strip, body — and the card wears its
  own plum identity.
  Host-card infrastructure: a trailing-toolbar extension point; drawers dock
  in-flow (BorderPane edge regions inside card bounds) wrapping the card
  CONTENT only, so the header spans the widened window with a single close
  control and the window root's resize-handle z-order stays intact (the
  buried south band); opening a drawer grows the window by the panel size,
  closing gives it back.
- **Drill-in content owns the pane's height; Pedro's READ-ONLY pill on system defaults**
  The settings pane's drill gives its section content vertical grow — the
  assistant's prompt preview now fills whatever the pane has instead of
  floating as a small scroll box above empty space. The Instruction Editor
  shows the READ-ONLY pill (mirroring the KLReadOnly control family's
  affordance) beside the category when a system default is open; it swaps
  to the shared control when the family exposes it.
- **A user gesture outranks the standing size cap; unsaved-changes signal; editor settings and rail toggle**
  The third and real growth limit falls: the workspace caps every window
  at MAX_WINDOW_HEIGHT and the resize handlers honored it — now a resize
  gesture past the cap raises it (height and width), while the cap keeps
  governing content-driven auto-growth between gestures. No forbidden
  limit for the human. Both rails' selection fills key on selection AND
  focus — light text only on the focused highlight; the unfocused grey
  selection keeps dark text. Dropped Koncept tokens land where the mouse
  released, never at a stale caret. The editor signals unsaved changes
  (status dot) and enables Save only for a changed, writable set — Save
  as… stays always available, since duplicating an unchanged set is a
  legitimate gesture; a changed read-only default routes to Save as…
  explicitly. The Instruction Editor gains the standardized settings
  sliders (text size, live re-render) and the rail show/hide toggle for
  full-tile content view; the assistant's prompt drill-in gives its whole
  height to the rendered preview and its action reads Open in Instruction
  Editor.
- **Read-only system defaults with Save as…, Koncept drop-in, growth truly unbound, readable selection**
  The seeded examples become read-only system defaults (registration-level
  flag, adoptable onto the knowledge-layout read-only property when it
  lands): Save refuses them — the store guards and the button disables
  with a status note — while Save as… stays live, prompting for a managed
  title (proposed as name-copy, made unique against the tile's
  registrations), so copying is always the explicit gesture. Pre-ruling
  tiles migrate their writable ghosts forward once. The raw editor gains
  Koncept drop-in (KonceptTokenDrop): a concept or pattern dragged from
  anywhere in Komet drops as its id-bearing k: token at the caret, and the
  rendered view shows the live badge — knowledge-referencing instruction
  authoring. Rail selection fills flip with the highlight (the muted
  description was unreadable over it). The window-growth ruling completes:
  constrainToParentBounds no longer pushes a window back inside the
  desktop (origin pins stay), and the east clamp joins the south — the
  workspace extends beneath a growing window in both axes.
- **Card growth has no forbidden limit; the Instruction Editor opens at the assistant's footprint**
  The south-edge resize clamp at the parent desktop's bottom boundary is
  removed: a card may grow past the visible desktop — the workspace
  scrolls and the grid extends beneath it. The north edge's top pin stays,
  since negative desktop coordinates would detach a window from the
  workspace origin. The Instruction Editor card opens at 900x680, the
  assistant card's footprint — sibling cards open at sibling sizes.
- **SettingsPanePopup: the View Options adjacent-pane paradigm for durable preferences**
  The standardized settings pane in knowledge-layout: a PopupControl whose
  root wears the shared filter-options-popup style family (one stylesheet,
  no drift) with the settings-card extension — header grammar, section
  cards (upper-case title, live summary, chevron), drill-in content with a
  back row. Positioning is the extracted ViewOptionsPopupHelper.flankWindow
  (the View Options popup now calls the same math), toggle wiring carries
  the shared filter-showing pseudo-class. The assistant card is the first
  consumer: the sliders affordance opens the pane with Text size (live ±),
  System prompt (the ike-issues#1039 instruction layer in the view/edit
  Markdown pane, tool contract rendered beneath), and API key sections —
  the prompt dialog is deleted, its semantics moved whole. The
  conversations rail wraps titles across lines within the rail and drops
  its scrollbar chrome. komet-desktop's komet-bom import moves to the
  reactor line: a released bom import pins previously-released komet
  sub-modules stale in the jlink boot image (the ike-issues#1019 sub-module
  gap, boot-image edition).
- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **Koncept badge multi-line rendering: semantic cell wrap, expansion and copy surfaces**
  The label-fidelity rule becomes contextual: an assistant table cell is a
  wrapping context, so its chips render multi-line — the name folds at the
  semantic break set (spaces, and after any of / - – — +) via the badge's
  own line breaker, the sigil and identicon seat on the first line, and
  the definition popout flows inline after the last wrapped word. The
  renderer declares the context through InlineDecorator.decorateForCell;
  the assistant's decorator materialises cell chips multi-line. Single-line
  contexts keep the width-driven ellipsis, and an ellipsised badge expands
  to the multi-line rendering on its identity tooltip and on click, in the
  definition popout's PopOver convention. The multi-line alignment rides an
  inline style layer because komet.css pins center-left on .koncept-chip
  and an author stylesheet outranks setAlignment — locked by a test that
  asserts the seating with komet.css applied. Badges also gain copy
  surfaces: a context menu (Copy name, Copy k: token, Select text…) and
  double-click into a pre-selected read-only field for word, character, or
  line copies.

## tinkar-service 1.0.5  ·  1.0.4 → 1.0.5

- **Pin the rocks-kb-engine literal to the version this mission releases**
  An alignment pass re-snapshotted the sub-module literal after the last
  mission's pin — the plan tracks member roots only, so it never
  retargets and the 1022 gate refuses it (the pom comment documents this
  recipe). 0.1.4 is what rocks-kb ships this mission; the sub-module
  settlement (1019) retires this hand-move.
- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## komet-claude-plugin 6  ·  5 → 6

- **Instruction Editor: one editing surface, settled categories, Assistant drawer**
  Focus-or-create replaces the assistant card's escape editor window: a
  MakeCardWindowEvent on the journal topic fronts the open Instruction Editor
  card or creates one; the tabbed Stage and the card-override writers are
  deleted.
  Categories settle to System Prompt | Skill | Tool Contract. General is
  retired (unknown or absent parses to Skill), and versioned seeding gives
  every category a read-only system default, refreshing OUR defaults in place
  on generation bumps.
  Drafting assistance lands as an in-flow Assistant drawer under one
  full-width title bar: per-set conversations (in-memory this increment),
  discussion in text with revisions arriving only through the propose_document
  tool, reviewed as word-level track changes (MarkdownDiff) with Revert and
  Revert draft; manual edits show as track changes too. The editor mirrors the
  portable form's order — name, auto-growing routing description, the
  category / read-only / View|Edit mode strip, body — and the card wears its
  own plum identity.
  Host-card infrastructure: a trailing-toolbar extension point; drawers dock
  in-flow (BorderPane edge regions inside card bounds) wrapping the card
  CONTENT only, so the header spans the widened window with a single close
  control and the window root's resize-handle z-order stays intact (the
  buried south band); opening a drawer grows the window by the panel size,
  closing gives it back.
- **Drill-in content owns the pane's height; Pedro's READ-ONLY pill on system defaults**
  The settings pane's drill gives its section content vertical grow — the
  assistant's prompt preview now fills whatever the pane has instead of
  floating as a small scroll box above empty space. The Instruction Editor
  shows the READ-ONLY pill (mirroring the KLReadOnly control family's
  affordance) beside the category when a system default is open; it swaps
  to the shared control when the family exposes it.
- **A user gesture outranks the standing size cap; unsaved-changes signal; editor settings and rail toggle**
  The third and real growth limit falls: the workspace caps every window
  at MAX_WINDOW_HEIGHT and the resize handlers honored it — now a resize
  gesture past the cap raises it (height and width), while the cap keeps
  governing content-driven auto-growth between gestures. No forbidden
  limit for the human. Both rails' selection fills key on selection AND
  focus — light text only on the focused highlight; the unfocused grey
  selection keeps dark text. Dropped Koncept tokens land where the mouse
  released, never at a stale caret. The editor signals unsaved changes
  (status dot) and enables Save only for a changed, writable set — Save
  as… stays always available, since duplicating an unchanged set is a
  legitimate gesture; a changed read-only default routes to Save as…
  explicitly. The Instruction Editor gains the standardized settings
  sliders (text size, live re-render) and the rail show/hide toggle for
  full-tile content view; the assistant's prompt drill-in gives its whole
  height to the rendered preview and its action reads Open in Instruction
  Editor.
- **Read-only system defaults with Save as…, Koncept drop-in, growth truly unbound, readable selection**
  The seeded examples become read-only system defaults (registration-level
  flag, adoptable onto the knowledge-layout read-only property when it
  lands): Save refuses them — the store guards and the button disables
  with a status note — while Save as… stays live, prompting for a managed
  title (proposed as name-copy, made unique against the tile's
  registrations), so copying is always the explicit gesture. Pre-ruling
  tiles migrate their writable ghosts forward once. The raw editor gains
  Koncept drop-in (KonceptTokenDrop): a concept or pattern dragged from
  anywhere in Komet drops as its id-bearing k: token at the caret, and the
  rendered view shows the live badge — knowledge-referencing instruction
  authoring. Rail selection fills flip with the highlight (the muted
  description was unreadable over it). The window-growth ruling completes:
  constrainToParentBounds no longer pushes a window back inside the
  desktop (origin pins stay), and the east clamp joins the south — the
  workspace extends beneath a growing window in both axes.
- **Card growth has no forbidden limit; the Instruction Editor opens at the assistant's footprint**
  The south-edge resize clamp at the parent desktop's bottom boundary is
  removed: a card may grow past the visible desktop — the workspace
  scrolls and the grid extends beneath it. The north edge's top pin stays,
  since negative desktop coordinates would detach a window from the
  workspace origin. The Instruction Editor card opens at 900x680, the
  assistant card's footprint — sibling cards open at sibling sizes.
- **Instruction categories, ghost examples, and the first-run editor experience**
  Standard categories from a closed enum-backed list (System Prompt,
  Skill, General), carried as a portable category: frontmatter key —
  category CLASSIFIES intent and drives which selectors surface a set
  (the assistant's system-prompt selector skips SKILL-categorized sets);
  attachment at the use site stays the enforcing act, so the editor
  remains roleless. The editor gains the category dropdown, the rail
  shows non-general categories beside descriptions, and the first-run
  experience is fixed: the rail header un-crams (title and actions on
  separate rows — one line ellipsized every label into dot-stubs), and an
  empty tile seeds ghost examples exactly once — the bundled assistant
  instruction layer as a System Prompt example and an authored sample
  Skill — real, overwritable sets, with an explanatory empty state
  behind them.
- **Instruction Editor card and the titled-instruction-set fabric**
  The roleless authoring tile (KEC-ratified shape): the Instruction Editor
  card's rail lists the tile's titled instruction sets with New (seeded on
  the SKILL.md scaffold) and Import…; the editor is name + description —
  the Agent Skills frontmatter surface — over the Markdown body in the
  view/edit pane. It never asks whether a document is a system prompt or a
  skill: that is the attachment role at the use site. Sets are payload
  files in the portable SKILL.md form, registered by preferences index
  entries in the owning tile's node (the entry IS the registration), so
  they ride the preferences git sync; the tile carries the card-type
  marker and kind-plus-sequence names (Instruction Editor N) for
  journal-wide discovery.
  The assistant attaches at the use site: the settings pane's System
  prompt section becomes a selector — the card-local layer or any titled
  set discovered across the journal's editor tiles — with the rendered
  preview tracking the active choice; the escape editor stays for the
  card-local layer, titled sets edit in their own tile. The instruction
  layer resolves selection → card override → bundled default, degrading
  down the chain so a broken selection never silences the assistant.
- **Prompt editor escapes the pane; rail wraps with a hanging indent**
  The settings pane's System prompt drill-in stays at glance depth — a
  rendered preview — and editing escapes to a resizable window at writing
  size via Open editor…: two tabs (Instructions, Tool contract), each
  owning the whole window and growing with it, one window per card. The
  same editor surface the titled-instruction-set direction reuses (system
  prompts and skills unify as titled instruction sets with role-typed
  attachment — recorded on the skills issue). The conversations rail gains
  the numbered-list hanging indent: the ordinal in its own leading column,
  wrapped title lines aligning under the title's first character, the busy
  spinner on the first line.
- **SettingsPanePopup: the View Options adjacent-pane paradigm for durable preferences**
  The standardized settings pane in knowledge-layout: a PopupControl whose
  root wears the shared filter-options-popup style family (one stylesheet,
  no drift) with the settings-card extension — header grammar, section
  cards (upper-case title, live summary, chevron), drill-in content with a
  back row. Positioning is the extracted ViewOptionsPopupHelper.flankWindow
  (the View Options popup now calls the same math), toggle wiring carries
  the shared filter-showing pseudo-class. The assistant card is the first
  consumer: the sliders affordance opens the pane with Text size (live ±),
  System prompt (the ike-issues#1039 instruction layer in the view/edit
  Markdown pane, tool contract rendered beneath), and API key sections —
  the prompt dialog is deleted, its semantics moved whole. The
  conversations rail wraps titles across lines within the rail and drops
  its scrollbar chrome. komet-desktop's komet-bom import moves to the
  reactor line: a released bom import pins previously-released komet
  sub-modules stale in the jlink boot image (the ike-issues#1019 sub-module
  gap, boot-image edition).
- **Assistant settings paradigm, transcript strip, tile-first rail, and the Markdown view/edit pane**
  Completes the editable system prompt and the toolbar restructure. The
  card toolbar reduces to card chrome — coordinate, conversations toggle,
  and the house settings sliders (fa-sliders, white, size-matched via the
  dedicated settings-button geometry class) holding text size, System
  prompt…, and API key…. Conversation-scoped actions (transcript Save,
  expand/collapse all) move into a slim non-scrolling strip at the top of
  the transcript panel. The system-prompt dialog renders both layers
  through the card's Markdown pipeline with a view/edit toggle — the new
  reusable MarkdownEditPane, seed of the snippet-toggle standardization.
  The rail leads with the tile selector (the overarching scope), + New
  disables while browsing a sibling tile, and tile display names follow
  the kind-plus-sequence convention (Assistant Card N, minted once;
  pre-convention timestamp labels migrate forward and the selector
  re-reads after migration).
  The first half of the prompt work (resource split into tool-contract
  core + instruction seed, persistence, the initial dialog) rode the
  parent-172 adoption commit 944ccc9 from the parallel workspace
  operation — an unstaged sweep, noted for the record.
- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **Koncept badge multi-line rendering: semantic cell wrap, expansion and copy surfaces**
  The label-fidelity rule becomes contextual: an assistant table cell is a
  wrapping context, so its chips render multi-line — the name folds at the
  semantic break set (spaces, and after any of / - – — +) via the badge's
  own line breaker, the sigil and identicon seat on the first line, and
  the definition popout flows inline after the last wrapped word. The
  renderer declares the context through InlineDecorator.decorateForCell;
  the assistant's decorator materialises cell chips multi-line. Single-line
  contexts keep the width-driven ellipsis, and an ellipsised badge expands
  to the multi-line rendering on its identity tooltip and on click, in the
  definition popout's PopOver convention. The multi-line alignment rides an
  inline style layer because komet.css pins center-left on .koncept-chip
  and an author stylesheet outranks setAlignment — locked by a test that
  asserts the seating with komet.css applied. Badges also gain copy
  surfaces: a context menu (Copy name, Copy k: token, Select text…) and
  double-click into a pre-selected read-only field for word, character, or
  line copies.

## komet-example-rules-plugin 5  ·  4 → 5

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## complex-clause-plugin 5  ·  4 → 5

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).

## komet-desktop 3.0.5  ·  3.0.4 → 3.0.5

- **Correct the claude-plugin staging pin after the align pass**
  ws:align's bundle-edge derivation re-pointed komet-claude-plugin.version
  one generation stale (6-SNAPSHOT → 5-SNAPSHOT) — the recorded ws:align
  staging-pin defect striking again; pin restored to the member's current
  snapshot with a warning comment at the property.
- **SettingsPanePopup: the View Options adjacent-pane paradigm for durable preferences**
  The standardized settings pane in knowledge-layout: a PopupControl whose
  root wears the shared filter-options-popup style family (one stylesheet,
  no drift) with the settings-card extension — header grammar, section
  cards (upper-case title, live summary, chevron), drill-in content with a
  back row. Positioning is the extracted ViewOptionsPopupHelper.flankWindow
  (the View Options popup now calls the same math), toggle wiring carries
  the shared filter-showing pseudo-class. The assistant card is the first
  consumer: the sliders affordance opens the pane with Text size (live ±),
  System prompt (the ike-issues#1039 instruction layer in the view/edit
  Markdown pane, tool contract rendered beneath), and API key sections —
  the prompt dialog is deleted, its semantics moved whole. The
  conversations rail wraps titles across lines within the rail and drops
  its scrollbar chrome. komet-desktop's komet-bom import moves to the
  reactor line: a released bom import pins previously-released komet
  sub-modules stale in the jlink boot image (the ike-issues#1019 sub-module
  gap, boot-image edition).
- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **Align plugin-layer staging pins to member snapshots**
  komet-claude-plugin was staged at released 5, and komet-markdown-richtext
  at released 1.59.3 through its version-less artifactItem: the renderer is
  a komet sub-module, which neither the workspace extension nor the
  imported released komet-bom retargets, so dev images silently ran
  released plugin-layer bits while the reactor built snapshots. The claude
  pin moves to the member snapshot and the renderer gains an explicit
  staging property, value-aligned for release-plan inference like the other
  staged jars.
- **Skip local Lucene indexing when using gRPC mode**
  feature/grpc_search_group
  ## komet-desktop (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## komet-grpc-plugin (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## tinkar-core (3 commits)
  - update: merge main into feature/grpc_search_group
  - update: merge main into feature/grpc_search_group
  - Skip local Lucene indexing when using gRPC mode
  ## workspace (2 commits)
  - ws: re-derive depends-on edges
  - workspace: update branches for feature/grpc_search_group

## (workspace root) 7  ·  6 → 7

- **Adopt platform 172 across the working set (ike-parent 170 → 172)**
  The activation parent for the mission vocabulary and delivery fixes:
  tooling 249's record model (mission: field, cycle: read forever),
  the mission-labeled release goals with the canonical-label guard
  (1035/1038), and the record-derived what-changed notes (1016). Root
  and all 14 members move together — publish preflight enforces parent
  coherence (324).
- **ws: re-derive depends-on edges**
  - komet-claude-plugin depends-on (+1, -0) added [komet-grpc-plugin]
  Re-derives workspace.yaml depends-on from POM reality after a workspace mutation, so the manifest is never left uncommitted. Build edges are machine-derived; bundle/content/tooling edges are preserved as hand-declared.
