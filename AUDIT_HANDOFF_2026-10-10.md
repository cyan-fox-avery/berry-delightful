# Berry Delightful: canon-consistency audit handoff
**2026-10-10 · For Roman and Milo · Prepared by Mira 🩵🍓**

**Scope of this pass:** Editorial corrections to `DESIGN.md` on the permanent design-room branch. **No new gameplay features approved, no production code changed, no PR merge.** The aim is to prevent earlier proposals from masquerading as current decisions, while preserving the dated design history.

**Naming convention:** **Berry Delightful is the game. Starvale Farm is the fictional farm.** Stardale Farm is the real-world inspiration. Use these names consistently in issues, UI, text and artwork.

## Changes applied, and why

| Area | What I changed | Why |
| --- | --- | --- |
| Canon hierarchy | Added a current-canon summary and explicit precedence rule near the top. | Older dated brainstorming must not overrule Avery's more recent decisions. |
| Status / team pacing | Replaced the stale 'no building' banner with authorized grey-box testing; recorded Avery's requested breather from new pitches. | The prototype exists, but full production and extra pitches are not automatically approved. |
| Story premise | Replaced 'inherited farm' in the opener: the player **bought** the neglected farm they visited as a child. | Avery answered this directly; the purchased-farm premise makes the restoration an act of choice. |
| Daily actions | Reframed **four actions/day as historical prototype behavior**; **no cap is the current starting hypothesis**. Festival visits are not action-metered either. | Avery explicitly chose to test cozy, unconstrained play and restore a limit only if days become repetitive checklists. |
| Storms | Preserved the early scripted storm, safe crops, closed outdoor actions, kitchen focus, pig tell and neighbour's blessing; removed assumed replacement quota of four kitchen actions. | The storm rules had retained the rejected budget. Unique later storm vignettes are still undecided. |
| Narrative timeline | Clarified festival = farming/gameplay payoff; autumn = giving/free play; Christmas = personal finale/letter and fictional `'Fiona'` cultivar; Year Two only if the player opts in afterward. | The journal-shelving pitch must not move the Christmas ending behind a replay/reset interaction. |
| Journal / saving | Kept the first journal open through Christmas, with optional post-Christmas shelving; marked rewind-to-old-page loading as **undecided** and emphasized save safety. | Page-turning as presentation must not silently promise a working multi-save rewind system or destructive reset. |
| 27 jars | Removed readable notes and 'four hands' references from canon. Jars are now **visual-only** and not interactable. | Avery declined the notes feature; the jars belong to the private emotional reference to *27 Things About Fiona*. |
| Writing style and learning | Removed jar-note writing from Barbara's voice description; marked the field guide **adopted**, with entries appearing on first harvest. | Brings headings and voice rules into line with the PR decisions. |
| Keepsakes | Replaced the misleading 'nothing decided' heading and clarified that lists in the design document do not create a player-facing achievements checklist. | Achievements are physical keepsakes, with marginalia, not another UI system. |
| Prototype | Replaced the obsolete T1-only/no-save v0.1 launch plan with the authorized tutorial→T2 grey box and five-part graduation gate; kept the original proposal explicitly as history. | The prototype scope has changed; sign-off criteria must describe the actual intended experiment. |
| Remaining tasks and names | Refreshed the open-issues list, recorded the farmhouse-window idea as **open**, archived title alternatives and updated the stand-order exception to anonymous handwriting-based notes. | Stops stale queue items and the original named-regulars pitch from being treated as fresh requirements. |

## Current decision boundaries (please protect these)

- **No action limit is the default for the next comparative playtest**, not a permanent prohibition on a future budget. Decide from observed play, not intuition alone.
- The **festival's exact beat map is parked**, although its relaxed walk, family serving and one pig incident are already canon.
- **Barbara's original strawberry patch is not at Starvale.** After the Barbara Special, a gifted runner can be planted at Starvale. Do not transplant the real memory to the wrong property.
- The **27 jars remain an easter egg**, not a data/content project.
- The **Christmas letter must not depend on opting into Year Two** or manually shelving the journal. The actual method for advancing from autumn free play to Christmas remains to be specified.
- `Fragaria × ananassa 'Fiona'` is **fictional in-game canon**, not a verified claim that the cultivar name is available in real-world registration systems.
- **Avery asked for a breather.** This document is not a new brainstorm; any further concept should wait.

## Open decisions (deliberately NOT resolved by this audit)

1. **Grey Box 2:** Roman mentions a no-cap variant. Please link its exact commit, branch or deployment. The `lab/main` code available during this audit still represented the earlier action-limited build. Do not use the old build as evidence that the new pacing has passed.
2. **Day-loop validation:** Do no-cap days create satisfying choices or repetitive water-all/harvest-all checklists? Ben and Mira are the named gatekeepers; the first priority is a human playthrough and a reliable technical check.
3. **Storm test coverage:** The graduation gate asks players to notice the pig's pre-storm tell and enjoy a storm day. If these aren't in the tested prototype, explicitly mark those gate items *not yet tested*. Do not invent successful results.
4. **Year Two and saving:** How is the voluntary new-season reset presented and confirmed, how are existing journals protected, what carries over, and is reading an earlier journal page distinct from rewinding the save? Avoid accidental data loss.
5. **Winter arrival:** How the autumn free-play season transitions to Christmas without creating compulsory gift-board chores is not yet specified.
6. **Window:** Avery's 6–12 dawn-to-stars stages should remain visual and non-pressuring. When/why the lighting updates is still open.
7. **Other parked pitches:** exact festival beat sequence, optional storm vignettes, soil/compost mechanics, and final sound-file licensing. Keep their current statuses.

## Prototype code review carried forward (not fixed by this editorial pass)

Checked in `cyan-fox-avery/lab` on the connected `main` branch before this audit. These need re-verification in the *actual* variant under playtest:

- **Duplicate ingredients:** `js/ui.js` experiment selector toggles a selected ingredient off on a second click; combinations requiring two of the same berry cannot be selected.
- **Double-spend:** `js/engine.js` experimentation spends an action before its already-known-recipe path calls `bake()`, which spends another.
- **Jam inventory:** `bake("jam")` increments both baked goods and standalone jam, and the sell overlay lists both; this can double-count sellable product.
- **Tutorial hooks:** `js/ui.js` can call tutorial progression hooks even if the related engine operation fails, e.g. selling and some pig interactions.

The historical main-branch code also still had the old action system; **don't fix its counters blindly if Grey Box 2 uses a different architecture.** Check the current test ref first. No JS files were changed in this audit.

## Handoff request

**Roman:** Please sanity-check the edited `DESIGN.md` against the most recent explicit Avery decisions, and share the exact Grey Box 2 test ref when ready. **Milo:** Please review the canon distinctions and remaining-open classifications, rather than resubmitting the parked pitches as new proposals. If I mistook any unresolved question for a decided rule, flag it for Avery instead of silently adopting a new answer.

The aim is one shared, dependable design reference: **a tiny illustrated browser game with an enormous amount of heart, not an enormous production.**

— Mira 🩵🍓
