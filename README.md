# life-reset-manager

The **runtime** of the *life-reset* personal manager — a strict, self-improving personal
operating manager (weekly + daily rhythm) that runs from its own durable memory and is
portable across chats and providers.

## What lives here vs. what doesn't

- **Here (the product / runtime):** the manager's `sealed-core` (its non-amendable safety
  layer), the week-files, and the manager's own memory.
- **Not here (governance):** *what* to build — the charter, the outcome tree, the bets, and
  the session history — lives in the **Direction-OS** repo (`my_global_workflow`,
  `live/life-reset/`). That repo decides and tracks; this repo is the thing that runs.

Changes here are made via the Direction-OS's executor / work CALLs; the direction tracks them
by commit evidence. This repo does not need to know the OS internals — it just manages life.

## The one hard rule: stay light

**Markdown-only until a real run earns more.** No heavy runtime infrastructure
(no DATA_MODEL / MEMORY / RETRIEVAL build) before v1 is proven by **one real run**.
Building infrastructure before using it is exactly what derailed this direction once
(2026-06-20). The repo is an address, not a licence to over-engineer — `appetite` + `kill_by`
hold the line, not the location.

## v1 (in progress — bet `g-lr-run`)

Planned files, created by the build sessions (not pre-stubbed):
- `sealed-core.md` — inviolable override path · protected class (genuine recovery / safety /
  floors) · the 4 floor-tripwires (sleep / not-smoking / no-binge / not-vanishing) · manual
  rollback · "rules change only via the gate" · non-punishing-return invariant · the
  **not-a-safety-valve** boundary: the manager is NOT a clinician and does NOT route to a
  specialist or run therapy/practices — the owner self-sources any external human support
  (psychiatrist / friend) outside the system; its response to the checkout-slide is to
  re-ignite the owner's OWN values through an objective external voice — firm, non-punishing,
  never by force, never by referral.
- `operating-template.md` — the week + day skeleton + the rules: week = protected tier-1 →
  routine → wishes-through-filter → explicit cuts; day = gate (R11) → plan → free log → review;
  an accumulator so nothing is lost; week-review → one decision (incl. `{research}` = a separate
  deep-research chat that rewrites the method). The working METHOD (time-blocks, pomodoro, …) is
  a swappable hypothesis, not a law — only the rhythm is fixed. Durable state is optimized for
  the manager (its working memory + cross-provider portability), not for the owner to read — the
  owner interacts by conversation and gets rendered views on demand.

Status: v1 being authored (sealed-core + operating-template done; next is one real run).
Full plan + governance: `my_global_workflow/live/life-reset/NOW.md`.
