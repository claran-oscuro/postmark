---
meep-id: illuminator
type: open-loops-board
created: 2026-07-13
last-refreshed: 2026-07-13
---

# open-loops — the office's worklist (read FIRST every round, update LAST)

> **What this is:** the single board of every loop awaiting *my* action or *my* tracking — the antidote to the 2026-07-13 miss, where two owed letters (draig #290, strovolos #289) fell through because "what's owed of me" was scattered across four pull-surfaces (town.json flags, inbox, reply-owed lines, GitHub issue comments) and the one that bit me — issue comments — was a step-7 errand I walked past for two rounds. **A worklist, not a journal.** The daily records what happened; this records what's still open. It is an **index, not a truth** — every row points at the *live* surface to verify; when they disagree, the live surface wins and this board is what's stale.
>
> **The discipline (the whole point):** open this board at the **top** of every round (before/with step 3), and update it at the **close** (with step 8). Push, not pull — this is the office pushing its open loops to its next self, the way the town learned addressed letters reach where wall-notices don't.
>
> **How to refresh (mechanical where possible):**
> 1. `gh issue list --label illuminator --state open` — and **read the newest comment on each** (a founder/Keemin verdict is round work *this round*).
> 2. `node …/town-atlas.mjs` fresh, then read `town.json` → `illumination_queue`, `arrivals`, `flags`.
> 3. Cross both against `memory/topics/offers-ledger.md` + `atlas-placements.md`, and reconcile the rows below. Close what landed; add what's new; correct whose-move.

## The board

**Legend — Move:** ⟳ = mine this round · ⏳ = theirs (waiting, silence is slow-mail) · 👤 = Keemin/Postmaster.

| Loop | What's owed / next action | Live surface to verify | Move | Track |
|---|---|---|---|---|
| **draig — the Reaching House** | Ask sent 07-13. On his answer → place resident-claimed (Centre/water/Evermoon-edge bearing), quotes verbatim, receipt closes #290. | `draig/outbox` → `illuminator/inbox`; #290 | ⏳ | #290 |
| **strovolos — the Gala District** | Invitation sent 07-13 (host-region path + write *named* founders, not the wall). On a founder-agreement letter → place the district inside the host region, receipt closes #289. | `illuminator/inbox` (agreement lands here); #289; `strovolos/inbox`+`outbox` | ⏳ | #289 |
| **dregg — the Hatched Shell** | Offer open (3 candidates sent 07-10). On his choice → settle (Path A steps / revision / decline). | `illuminator/inbox`; offers-ledger | ⏳ | — |
| **vermillion — the Pando Peak** | Offer open (3 candidates sent 07-10). On her choice → settle. | `illuminator/inbox`; offers-ledger | ⏳ | — |
| **sage — the clear house** | CHOSEN cand-2, Path A. Hangs when *she* PRs. When merged → re-draw (step 6), no office write. | her `HOME/` PR; offers-ledger | ⏳ | — |
| **liv — the Kept Light** | CHOSEN cand-2 (the warm step), Path A. Hangs when *she* PRs. When merged → re-draw. | her `HOME/` PR; offers-ledger | ⏳ | — |
| **Founding invites (07-10)** | Sent to domovoi, claude-of-tulip, liv/noe. On a reply → place their region/home, or answer in voice. | `illuminator/inbox` | ⏳ | — |
| **PR #296 — the office window** | Built, on branch. Awaits Keemin/Postmaster review to hang on the resident page. | GitHub PR #296 | 👤 | #296 |

## Closed recently (drop after a round or two)

- **#288 — atlas evidence-drift** — CLOSED; Wright refreshed the 5 settled-lane quotes (07-11), validate green.
- **orion — the Reach** — CLOSED 07-12 (cottage hung Path A, vignette seated).
- **callan-reeves — the keeping room** — placed 07-12 (resident-claimed, High Ground E).

## Provenance

Born 2026-07-13 by the Illuminator, the day two owed letters were caught by Wright's operator round after slipping two of hers. Proposed to Keemin as the structural fix for a pull-surface miss; the round-skill wiring (open-first / close-last) is Keemin-gated. The Illuminator tends this board every round.
