# ORA

**_feudalism is so out_**

A single-file, offline focus timer and time-logger for people who'd rather narrate their day than fill in a spreadsheet. Your hours are yours — no lords, no ledgers, no login.

ORA breaks the working day into hour blocks, lets you set an intention for each, run timers against it, and log what actually happened as lightweight "Traces." A tidal **wave** across the top tracks your vitality through the day, and a crystal ball keeps a rabbit on watch.

---

## Quick start

There's nothing to install or build.

```
open index_v2.0.3.html
```

Or just double-click the file. It runs entirely in your browser — no server, no network, no dependencies.

## What's inside

- **Hour blocks** — the day, split into hours. Each block holds an intention, timers, and its logged Traces.
- **Beacons** — your task pool (the left sidebar). Drag a Beacon onto an hour's intention field or a Trace to assign it.
- **Traces** — the time entries you actually log: a time, a client/label, a tag, and notes. Add them inline per hour, or via the **+** on the Traces header.
- **Timers** — each work block has a combined pill you can start/stop; buffer time is tracked alongside the focused work.
- **The wave** — a canvas visualization of your vitality across a rolling window, shaped by your wake periods and the knots you set.
- **Crystal ball & rabbit** — an intro flourish: the ball rolls in below the wave and a rabbit hops up to keep time.
- **Side-Jester** — the occasional sidequest module, for when the day needs a detour.
- **Day summary** — tallies your logged time by tag and by label, with one-click **Copy** or **CSV export**.

## Concepts, briefly

| Term | What it is |
|------|-----------|
| **Beacon** | A task waiting in the pool to be picked up. |
| **Trace** | A logged record of time actually spent. |
| **Intention** | What you mean to do in a given hour block. |
| **Vitality knot** | A point you set on the wave to shape your energy curve. |
| **Tag** | Category for a Trace — work, discussion, testing, or lore. |

## Data & privacy

Everything lives in your browser's `localStorage`. Nothing is sent anywhere. Clearing your browser data (or hitting **Reset**) unwrites the day. Use **Export CSV** if you want a copy that outlives the tab.

## Tech

- One HTML file. Vanilla HTML / CSS / JavaScript.
- Canvas for the wave and rabbit; `requestAnimationFrame` with dirty-flag redraws.
- `localStorage` for persistence. No build step, no framework, no external calls.

## Versioning

The working file is versioned in its name (`index_v2.0.3.html`). Older iterations and notes are kept locally under `99 ARCHIVE/` (git-ignored).
