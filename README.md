# Progress

The Qompass AI estate progress board. One page — [TRACKER.md](./TRACKER.md) —
shows where each main project actually stands: a progress bar, a state, the
next step, and a dated log per project.

This board exists so progress is a matter of record, not of impression. The
workers building these projects (Pax, Azoth, Astra, and dispatched build
workers) mark their own progress here as part of finishing a stage.

## The standing rule

**A bar never moves on a claim. A bar moves only on a gate.**

A gate is verified evidence: a test run with exact counts, a build that
passes its checks, a review of the artifact against its brief, a live
read-back of a deployed change. If the evidence has not been checked by the
gatekeeper, the bar does not move — no matter how finished the work feels.
Estimates, intentions, and "almost done" are not progress and are never
recorded as any.

## How a worker marks progress

1. **Finish and gate the work first.** The gate evidence exists before the
   board changes, never after.
2. **Edit your project's row in TRACKER.md.** Set the bar and the percentage
   from the stage arithmetic in the project file below — completed gated
   stages over total planned stages — not from a feeling about the work.
3. **Update the state and next step** so the row reads true for someone who
   has never seen the project.
4. **Append a dated line to your project's log section** in TRACKER.md:
   what stage closed, what the gate evidence was, and the new percentage.
   Newest entries at the top of the section.
5. **Commit with a conventional message**, e.g.
   `progress(strobe): Stage A evidence gated — 30% → 40%`.
   One project per commit.

## Stage arithmetic

Each project's percentage is `gated stages ÷ planned stages`, weighted where
a stage was split into lettered substages of known size. The seed percentages
(2026-10-20) were set by Pax from the gated state of each program on that
date, and each project's log records the basis. When a program's stage map
changes, the log entry that moves the bar notes the new denominator.

## What lives here

- `TRACKER.md` — the board: one row per project plus a dated log per project.
- `README.md` — this file: the rules of the board.
- `LICENSE` — Apache License 2.0.

Project code, designs, and evidence live in each project's own repository.
This repo holds the summary of record only.
