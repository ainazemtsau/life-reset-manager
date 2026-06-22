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

## v1 — the files

A small, complete set of structured markdown. The AI (ChatGPT / Claude / Claude Code / Codex)
is the interpreter; there is no code. The owner runs v1 himself and returns with problems.

- `manager.md` — the operating instructions: who the manager is · how you interact (log freely;
  state stored for the manager; rendered to you on demand; portable across chats/providers) ·
  the recipe model (day & week are composed from `recipe.md`; components are clean seams that
  can later be backed by a skill/tool/script) · the procedures (a deep-research that PICKS the
  starting method — not a default · week planning · day planning + R11 gate · day log/support
  with slip→rebalance · day & week review → one decision + a deep-research that REWRITES the
  recipe) · the accumulator ("nothing is lost") · honesty/BITE · what is inviolable.
- `recipe.md` — the current, editable configuration of HOW we work: the method (set by the
  first-run deep-research, not defaulted) · the day components · the week sections · active
  techniques. The manager rewrites this (with the owner's "ok") via review/deep-research.
- `state.md` — the manager's durable working memory: running-state · the accumulator
  (problems / misses / ideas) · week & day records. For the manager; rendered to the owner.
- `sealed-core.md` — the non-amendable safety floor: inviolable override (incl. R11 refusal) ·
  protected class (genuine recovery / safety / floors / routine rest) · the 4 floor-tripwires ·
  recovery-vs-slide · the objective voice (anchored to the owner's own plan; never
  scare/cheer/force/refer) · non-punishing return · the **not-a-safety-valve** boundary (no
  clinical routing) · manual rollback · "rules change only via the gate" · a 2-assertion smoke check.

Light governance notes: `my_global_workflow/live/life-reset/NOW.md`.
