# Estate Progress Tracker

> Visual status for the main Qompass AI projects. Bars move only on gated,
> verified evidence — see [README.md](./README.md) for the rules of this board.

**Data as of:** 2026-10-20 · **Projects:** 10

## Board

| Project | Progress | State | Next step | Updated |
| --- | --- | --- | --- | --- |
| atelier | `██░░░░░░░░░░░░░░░░░░` 10% | Commissioned: study + program + S1 brief complete; seven design questions ruled; GitHub home qompassai/atelier created on ruling; two lane profiles (qompass/ntranch) | S1 build dispatch when the primo Claude focus frees (Ghidra G1 running) | 2026-10-20 |
| Strobe (Track B) | `███████░░░░░░░░░░░░░` 35% | Decisions D1–D6 all ruled; scaffold built; Lovense transport proven; gen test phase 1 gated (23 scenes cataloged, age gate zero exclusions) | Write the Track B brief (Stage A evidence gated); gen test phase 2 through atelier S1 | 2026-10-20 |
| lumen | `███████████░░░░░░░░░` 55% | Stages 1–3 built; Stage 4 built and in remediation | Close the Stage 4 findings: render SSIM adversarial case, base L/R naming check, morph-target census | 2026-10-20 |
| tackle | `██░░░░░░░░░░░░░░░░░░` 10% | Commissioned; program and U0 brief written | U0 spike dispatch, 2026-10-21 | 2026-10-20 |
| fathom | `███████████░░░░░░░░░` 55% | Core server live (25 tools) + il2cpp module; Stage A GATED: la$$Load lift fully recovered, no wall; Ghidra G1 building | Gate G1; the Track B brief's evidence gap is closed | 2026-10-20 |
| twilight | `███░░░░░░░░░░░░░░░░░` 15% | Slice A1 gated (core server + engine detection) | A2 prep: verify the remaining engine signatures, write the A2 brief | 2026-10-20 |
| broadside | `██░░░░░░░░░░░░░░░░░░` 10% | Commissioned; study, program, and honeypot design complete; build not started | P0 census and pin-down when the build order is given | 2026-10-20 |
| phlow scheduler | `███████░░░░░░░░░░░░░` 35% | S1 delivered and in Pax gate | Gate S1; then S2 (clock + dispatcher) and S3 (MCP surface) | 2026-10-20 |
| Odyssey (manuscripts) | `████████░░░░░░░░░░░░` 40% | Slate active; tracker live; TKO draft v1.1 delivered; peer reviews current | TKO preflight (word counts, reference verification, protocol figure) | 2026-10-20 |
| diver maps migration | `███░░░░░░░░░░░░░░░░░` 15% | S0 complete: goldens pinned for formatters, linters, LSP | S1: smallest with-local-fn samples; golden-diff must be empty | 2026-10-20 |

## Project logs

Newest first within each project. One line per gated movement: the date, what
closed, the gate evidence, and the resulting percentage.

### atelier

- 2026-10-20 — Fleet name scrub in flight under the Owner-role
  convention: the owner's personal name is replaced by the role
  noun Owner in design records estate-wide, atelier first (its
  seed documents carried 24 role references). The exception is
  the main README where the name is resume material. This board
  was already zero-hit.

- 2026-10-20 — Board added at 10%. Commissioned as the estate's media
  MCP: one Rust server driving image, video, and music generation
  behind a ComfyUI backend, with two config-selected lane profiles —
  qompass (SFW, fleet-facing) and ntranch (adult, Strobe) — whose
  roots, logs, and outputs never mix. Study, program, and the S1
  brief are complete; all seven design questions were ruled the same
  day, including the license rule: alert, not deny — a model without
  a license record is admitted with the alert stamped on results and
  provenance manifests, and its outputs are not cleared for
  production. The GitHub home qompassai/atelier was created on that
  ruling. S1 is four tools and Iris only; its acceptance is the
  Strobe gen test — the three cataloged scenes regenerated through
  atelier's own img2img under the ntranch profile. A trigger-gated
  convergence into lumen is planned for later; the servers stay
  separate, with a single handoff, until the triggers are met.

### Strobe (Track B)

- 2026-10-20 — A detailed tracker now lives in NTRanch/Strobe
  (TRACKER.md, commit 90f18d3): workstream bars for design, cast
  book, scaffold, Lovense integration, the art pipeline, and
  publication. This board keeps the summary row.

- 2026-10-20 — Gen test phase 1.5 complete: flattened 1280x720
  composite references for the three test scenes (full layer
  accounting, deviations documented in COMPOSITES.md) and
  Danbooru tag-form prompts added to the regen briefs, md5-
  identical on primo and in the sandbox. Phase 2 regenerates
  the set through atelier S1.

- 2026-10-20 — Decisions D1–D6 all ruled and the gen test phase 1
  gated: 35%. D6, ruled 2026-10-20, is the two-layer sync model —
  music-layer output follows the chart's beat pulses, and the
  judgement layer scales output as a continuous falling function of
  timing offset, with a low thud on a miss. Gen test phase 1
  cataloged 23 adult scenes; the age gate closed with zero exclusions
  on the game's own 18+ boot-screen statement plus a full dialogue
  corpus sweep. A three-scene test set is briefed, and phase 1.5
  (flattened composite references and tag-form prompts) followed.
  Phase 2 regenerates the set through atelier S1.

- 2026-10-20 — Board seeded at 30%. Decisions D1–D6 ruled (D6, the W4 sync
  model, ruled 2026-10-20); Unity scaffold committed; the Lovense bridge
  transport passed its full test suite (82/82) against a fake Remote endpoint.
  The Track B brief waits on the fathom Stage A acceptance evidence.

### lumen

- 2026-10-20 — Registry publication: `ai.qompass/lumen` v0.1.1 is
  live on the official MCP Registry (status active, marked latest;
  MCPB bundle on the v0.1.1 GitHub release, SHA-256 c207e299…;
  verified through the registry API). The bar does not move:
  publication is not a build-stage gate.

- 2026-10-20 — Stage 4 remediation briefed to Azoth: add the 30°
  arm-error adversarial to the render SSIM gate and prove the gate
  catches it, settle the base L/R naming against anatomy, and
  characterize the unequal morph-target counts without silently
  normalizing them. The brief waits on a doorbell tap. Also recorded
  from lumen's side: the atelier boundary — atelier generates flat
  media, lumen transforms sprites to 3D, and lumen may ingest
  atelier-generated sprites as sources; the planned convergence of
  atelier into lumen is trigger-gated, not current.

- 2026-10-20 — Board seeded at 55%. Stages 1–3 built and gated; Stage 4
  (sprite-to-3D factory) built and in remediation on three gated findings:
  the render SSIM gate misses the mandated 30° arm-error adversarial, base
  L/R naming may be mirrored against anatomy, and morph-target counts differ
  across models.

### models

- 2026-10-20 — Letter-keyed model roster applied and verified live
  in rose: Clara (code), Freya (fast), Mira (multimodal — carries
  vision), Opal (operator), Sylvia (structured), and Tessa (tools)
  answer under their own names; Aria (audio) and Vera (video) are
  registry-only rows for now. Iris is Illustrious XL v1.1, SHA-256
  verified byte-identical against the official release on primo.
  MODELS.md in this repo is the roster record.

### MCP Registry

- 2026-10-20 — Registry publication: `ai.qompass/lupin` v0.1.0 is
  live on the official MCP Registry (status active, marked latest;
  MCPB bundle on the v0.1.0 GitHub release, SHA-256 1399234b…;
  verified through the registry API). With phaedrus and periscope
  published in the same batch, the registry now carries seven
  ai.qompass servers: eigenstyle, fathom, phlow, lumen, periscope,
  phaedrus, lupin. qompass.ai was updated the same day (commit
  8292580): the three roster rows read Published with registry
  links, and the site's published-server test pins moved from four
  to seven (70 tests green). No bar moves: publication is not a
  build-stage gate.

- 2026-10-20 — Registry publication: `ai.qompass/phaedrus` v0.1.0
  is live on the official MCP Registry (status active, marked
  latest; MCPB bundle on the v0.1.0 GitHub release, SHA-256
  4c8abf6c…; verified through the registry API).

- 2026-10-20 — Registry publication: `ai.qompass/periscope` v0.1.0
  is live on the official MCP Registry (status active, marked
  latest; MCPB bundle on the v0.1.0 GitHub release, SHA-256
  e89eaaed…; verified through the registry API).

### tackle

- 2026-10-20 — Board seeded at 10%. Commissioned as the estate's editor
  broker MCP (Unity first, separate from lumen). Study, program, and the U0
  spike brief are written; the U0 dispatch is scheduled for 2026-10-21.

### fathom

- 2026-10-20 — Board seeded at 45%. Core MCP server live with 25 tools and a
  published registry record. The IL2CPP Stage A worker died on 2026-10-19;
  the takeover is running under Pax. The Ghidra parity matrix passed its
  gate, unblocking the G1 read core (78 tools).
- 2026-10-20 — Stage A gated by Pax at 55%: the takeover recovered the
  full chart transform and key schedule statically (AES-128-CBC, string
  vault fully reversed; Pax independently re-decoded the vault slices).
  il2cpp tools committed locally (12eefa6), tests 156/0, apply idempotent.
  Load test stays unnecessary. Ghidra G1 is building under Astra.

### twilight

- 2026-10-20 — Program amended: the Slice B Create lanes are atelier
  client tools. Twilight consumes both atelier profiles (qompass and
  ntranch) and keeps its gallery surface; generation itself is
  atelier's. A2 prep — verifying the remaining engine signatures,
  then writing the A2 brief — is Pax's next step.

- 2026-10-20 — Board seeded at 15%. Slice A1 gated by Pax: core server plus
  engine detection (3 read tools), commit `9ed46e3`, clean tree. A2 (catalog
  + hardware fit + model management) is next; its prep starts with verifying
  the 12 engine signatures A1 left marked unverified.

### broadside

- 2026-10-20 — Renamed press → broadside on the Owner's ruling: the
  honeypot commission outgrew the old name. The design package moved
  to ~/workspace/broadside-20261020/; the crate will ship as
  broadside-mcp (the bare crates.io name is a 2023 crate). The same
  ruling assigns broadside the JWKS duty: broadside, not Volta,
  publishes the estate Agent Card JWKS at /.well-known/jwks.json as
  a signed-manifest artifact, with verify failing the build on key
  mismatch. Site roster and subpage renamed the same day (site
  commit 96794c9; /solutions/mcp/press is gone), and the census
  entry renamed with it. Bar unchanged at 10% — a rename is not
  progress.

- 2026-10-20 — Commissioning package complete, including the
  honeypot design: canary endpoints and canary credentials,
  injection quarantine in the fetch pipeline, a fail2ban blocklist
  with decay on the hosting side, and hash-chained evidence packets
  — with no hack-back, on attribution and CFAA grounds. The build
  order is the owner's call, after tackle.

- 2026-10-20 — Board seeded at 10%. Commissioned 2026-10-20: a small Rust
  MCP that builds, verifies, and deploys qompass.ai, with the honeypot layer
  designed the same day. Study, program, and stage map (P0–P4) are complete;
  no build stage has started.

### phlow scheduler

- 2026-10-20 — S1 stands delivered as an uncommitted tree; the Pax
  gate (report read, tree verification, and the test, format, and
  lint runs) is pending. The bar does not move until that gate
  passes.

- 2026-10-20 — Board seeded at 35%. S1 delivered by the build worker as an
  uncommitted tree (fail-closed parser, validated Job model, next-fire
  calculator, append-only store, STOP kill switch) and is in Pax's gate:
  report read, tree verification, and the test/format/lint run come before
  any commit. S2 and S3 follow the gate.

### Odyssey (manuscripts)

- 2026-10-20 — JGME peer reviews D-26-01056 and D-26-00815 are
  complete; the portal submission clicks are the owner's. TKO draft
  v1.1 stands delivered with the PQC and FDA/CISA device-precedent
  threads carried in.

- 2026-10-20 — Board seeded at 40%. The manuscript slate is active with its
  own tracker in the Odyssey repo. TKO draft v1.1 delivered 2026-10-20 (the
  PQC and FDA/CISA threads carried in); two JGME peer reviews are complete,
  with submission clicks outstanding.

### diver maps migration

- 2026-10-20 — Board seeded at 15%. S0 complete: the live config backed up
  and goldens pinned (formatter, linter, and LSP inventories hashed). S1
  converts the smallest samples first and requires an empty golden-diff
  before anything installs live.

## Updating this tracker

1. Gate the work. Evidence first, board second.
2. Move the row's bar and percentage per the stage arithmetic in
   [README.md](./README.md), and refresh its state, next step, and date.
3. Append the dated log line to the project's section above.
4. Commit one project per commit with a conventional message.
