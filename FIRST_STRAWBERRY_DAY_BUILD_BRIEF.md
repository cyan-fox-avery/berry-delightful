# Berry Delightful — First Strawberry Day
## The first playable vertical slice · Avery's implementation direction · 2026-10-11

> **Read this before adding features.** Avery wants to stop expanding the design on paper and **start playing**. This is the focused build brief for the next small, testable iteration, not an order to implement the full 100k-character design document.
>
> **Game:** Berry Delightful. **Place:** Starvale Farm.
>
> **Audience:** Roman (implementation), Mira (design/code review), Avery (final decisions and iPad Safari playtesting), and Ben + Milo (design/playtesting/scope feedback).
>
> **Decision authority:** Avery has explicitly approved the first-loop choice, gentle guidance, centralized transaction rules, and immediate sale. Suggestions or detailed defaults below do not authorize unrelated systems. Do not merge or close the permanent design PR #3.

## 1. Why we're changing approach

Berry Delightful's design grew faster than its playable game. Avery is worried about overall ambition and the Christmas gift deadline, and asked to return to the process that worked for **Tag Along**:

1. Mira asks one or a few concrete questions, with recommendations.
2. **Avery decides.** We treat those answers as the source of truth, not open-ended brainstorming.
3. Roman implements **one compact testable slice**.
4. Mira reviews source changes and flags issues. Avery **actually tests on an iPad in Safari**; these are distinct kinds of verification.
5. We fix and refine what exists, then repeat.

**Scope principle:** Ideas in DESIGN.md are a library and roadmap, **not a checklist for the first build**. A working, understandable small loop is worth more than a large unplayable list of features. No new optional mechanics should be slipped into the first slice.

## 2. Decisions made by Avery (locked for this iteration)

**First prototype: Option B, “The First Strawberry Day.”** The player:

**Arrives at Starvale → harvests surviving Earliglow strawberries → makes strawberry compote → sells it at the roadside stall.**

This must feel like a complete little experience, even using placeholders.

**Tutorial style: Option B, gentle guidance.** The player is free to inspect or move between available areas; the journal gently suggests a next step. **No rigid step-locking**, modal tutorial barrage, or guessing what button to press.

**Transactions: one place for outgoing goods.**
- **Everything outgoing goes through the stall.** In the initial build, that means selling. Later, if giving away or fulfilling orders uses this rule, those actions belong at the stall too, not in an inventory or kitchen sell button.
- **Incoming purchased things come through the Shop tab; incoming presents come through gifts.** Harvesting and cooking naturally create inventory from player actions; they do not need to masquerade as purchases or gifts.
- Do **not** create separate sales interfaces for baskets, cooked goods, recipes, neighbours, or inventories.

**Stall sale: Option A, immediate.**
- Choose an available item and quantity (for this slice, a simple 1-item sale is sufficient), see the price, confirm, and **receive coins right away**.
- Inventory decreases as coins increase, in the same transaction.
- No waiting for customers, overnight sales, passive sale timer, delivery wagon, negotiations, or sales minigame.
- June may be the **narrative first buyer** as already planned, but she should not require a separate purchasing screen, schedule, customer simulation, or interaction sequence to make selling work.

**Pacing:** preserve Avery's current rule from October 10: **no daily action cap** as the starting design. No stamina, timers, fails, punishments, or forced rush.

## 3. Important reconciliation with the older design document

The existing DESIGN.md describes:
- an eight-beat tutorial involving clearing/watering, a next-day harvest, an old pot, an **honesty box** sale, Buddy, supplier gifts, and first Annapolis planting;
- a larger roadside stand as a **Tier 3 unlock**, with passive sales and other features;
- older grey-box implementation targets, including a four-action-per-day prototype and a first pass that omitted the stand.

**For this new playable slice, the latest explicit Avery decisions above win:**
- Provide a **minimal usable stall from the beginning** so the first compote is sold there, rather than requiring a separate honesty-box sell interface. We are *not* building the large Tier 3 stand. How its visual upgrade/opening milestone works later is a **future Avery decision**.
- Keep the earlier eight-beat tutorial as a **longer-term reference**, not a mandatory first-version backlog. This slice is deliberately smaller. It may start with **some already ripe berries** to reach the core payoff in the first sitting; save watering/growth onboarding for a subsequent tested iteration. A title like “First Strawberry Day” names the introductory *play session*, not a hard commitment to one exact in-game calendar day.
- Never restore the obsolete four-action cap from old code without asking Avery.
- Preserve existing game/story canon (purchased neglected farm; Earliglow; old saucepan for compote; June is a neighbour, no explicit family relationships; Buddy outdoors; etc.) **without trying to implement all of it here**.

**Do not delete the historical design.** Just make the new slice the active implementation target and flag any remaining contradictions for Avery.

## 4. Minimum viable player experience

Aim for a **short, finishable test session** with a clear sense of place and a complete transaction. No need to meet an arbitrary minute count, but the first payoff should not take a long grind.

### Beat 1 — Homecoming
- A simple Starvale arrival/farm overview, with a few warm sentences establishing that the player **bought** a farm they visited as a child and wants to bring it back to life.
- The original **giant strawberry landmark** may appear as an inexpensive placeholder or text label; elaborate final art is **not a prerequisite** for testing.
- Clear navigation to the field, kitchen, and stall.
- Journal nudge such as “The old Earliglow patch might still have a few berries.” **Sample wording only**, not final dialogue.
- No lengthy mandatory intro, separate exploration quest, or new arrival subsystem.

### Beat 2 — First harvest
- One old Earliglow patch; a few berries are already ripe for this introductory slice.
- “Harvest” produces an unmistakable increase in a simple inventory count (“Earliglow baskets: 1”, for example).
- A readable success response, then a gentle nudge toward the kitchen.
- Existing prototype tending/overnight crop-growth logic may be reused where it simplifies the build, but **a crop simulator is not necessary to prove this first harvest/cook/sell loop**.

### Beat 3 — First compote
- In the farmhouse kitchen, the player uses the **old saucepan** to make **Strawberry Compote** from Earliglow berries and sugar already available in the pantry.
- Show the ingredient requirement, available stock, action, and resulting compote in inventory. Consumed ingredients must actually decrease.
- One recipe is enough. No mixer, blender, jam-canning simulation, hidden recipes, experiments, failures, recipe discovery tree, or cookbook overhaul.
- Keep food-safety boundaries: **compote is the stovetop tutorial recipe**, not a claim of shelf-stable canned jam.

### Beat 4 — First sale
- At the **stall**, display the compote, a readable immediate sale value, and a **Sell** action with clear confirmation/feedback.
- The player sells one compote; the result visibly removes one item and increases coins once.
- June can purchase/notice that first jar through a **small authored dialogue line** if feasible, preserving existing story direction. She need not be a simulated customer.
- Present a warm completion beat: “Starvale's first sale” or equivalent. **Do not auto-roll credits**; the player should remain free to look around or continue if the current loop supports it.

### Navigation and journal
- Very few screens: **arrival/farm overview, field, kitchen, stall**, plus a lightweight journal hint surface if an existing component supports it.
- **Shop** is the sole future purchasing surface; if no purchase is needed for this first loop, the tab can wait or be an unobtrusive existing UI. No dead-end button pretending to work.
- **Gifts** are the sole other external incoming-item source. Do not invent a gift-delivery system for this build. Starter sugar can simply already be in the inherited kitchen pantry.
- Journal hints should respond to progress, but never seize control or require the player to obey a strict screen order.
- Keep navigation obvious, touch targets large, and inventory/coins visible enough for an iPad tester to understand what happened.

## 5. Minimal data and economy rules

Reuse sound existing code/data rather than inventing a new subsystem:
- **Inventory:** Earliglow baskets; sugar or generic pantry supply; cooked compote.
- **Currency:** coins.
- **Actions:** harvest, cook, sell, plus navigation/journal.
- **State flags (only if useful):** arrival acknowledged, first harvest, first cook, first sale.
- **Transactions must be atomic:** no free duplications, negative stock, repeated first-sale payouts, or selling items that aren't owned.
- When stock is insufficient, show a gentle **specific** explanation rather than a silent disabled action.
- A sale must **not** occur when the player clicks the item or visits the stall; it should occur on an explicit Sell/Confirm gesture.

The original first-pass economy offers starter values, **not final balance requirements**: Earliglow basket 5 coins; compote 20 coins and a small pantry cost; starter coins 20. Use these where helpful to avoid a new balance debate, and make tuning values easy to change later. A cooked product should be worth visibly more than the berries that went into it, so the player understands why cooking matters.

If existing code has a day-advance button, it can remain **only if it behaves coherently and without a per-day action quota**. There is no requirement to build weather, seasonal progression, or multiple harvest days in this first release. If state persistence is already present, preserve it; otherwise **report save/reload limitations explicitly** rather than adding a larger save feature unnoticed.

## 6. Explicitly outside the first implementation

**Not in this slice:** the complete 8-beat tutorial, T1–T7 tree, Annapolis expansion, multiple cultivars, crop breeding, festival or Christmas story, house renovation, living-room prop layering, strawberry cow, real giant-strawberry art pass, animated weather, major storms, forecast UI, comprehensive field guide, achievements, 27 jars, new cast/story arcs, passive stall sales, customer orders, delivery logistics, gift reciprocity, dynamic shop/catalog, hidden recipes, failed bakes, Buddy minigames, realistic stock demand, day action allowance, or extensive visual polish.

These ideas aren't rejected or erased; **they are intentionally deferred**. The first iteration tests whether harvest → transform → sell feels legible and satisfying on an actual device. We may add one carefully selected thing after we test it.

**Please don't turn the pleasant simplicity of this brief into a giant “framework” ticket.** No speculative architecture for future features.

## 7. Acceptance criteria: ready for Avery's first hands-on test

A developer/demo build is **ready to send** when:
1. It opens as a browser game in iPad Safari (or is explicitly marked untested on device, with a usable link for Avery to try).
2. A new player can identify the old Earliglow patch and harvest at least one basket.
3. The inventory count updates; the kitchen clearly shows the available compote recipe; cooking consumes appropriate ingredients and yields a finished good.
4. The finished compote is sold **only at the stall**, **immediately**, with inventory and coin changes shown plainly.
5. The player can navigate away from a journal hint and return without breaking the game or getting trapped.
6. Touch controls/readability are plausible at tablet width; no mouse hover is essential.
7. Buttons do not duplicate rewards or allow impossible negative inventory.
8. No daily action cap has crept back in.
9. A version/build identifier is visible so testers know which iteration they are reporting on.
10. There is an easy restart/reset path for repeat playtesting, and any save/reload limitations are disclosed.
11. The implementation is reviewed separately from running automated tests, and separately from Avery's **actual iPad Safari test**. Nobody should report unperformed tests as passed.

**Avery's feedback questions** after playing:
- Did I understand where to go without being bossed around?
- Did picking and cooking feel rewarding, or like buttons moving numbers?
- Was the stall sale obvious, fast, and satisfying?
- Did I feel the first little spark of restoring Starvale?
- What was confusing, tedious, or visually hard to read on my iPad?
- What is the **single** next thing the game needs to make this loop better?

## 8. Delivery and collaboration

**Roman:** Please translate this brief into **the smallest concrete implementation PR** against the appropriate active game/prototype codebase. Prefer reusing the existing grey-box work if that is faster, but don't overwrite other projects or assume a specific deployment path without checking. In your PR description, list the exact playable URL or running instructions, any deliberate compromises, what you tested, and what remains untested. Make it easy for Avery to play. Do not merge the permanent design-lab PR #3.

**Mira:** Review the actual changed code and core behavior. Do not mistake code inspection for successful browser/iPad testing. Bring blocking problems back to Roman concisely. Ask Avery for decisions one at a time as real playtesting exposes needs.

**Ben and Milo:** You're invited to sanity-check this scope and try the build when Roman has a testable link. **Please prioritize finding confusion, edge cases, broken loops, and hidden implementation burden**, not adding new content pitches. Ben's real-player perspective is especially useful; the prototype needs more playing than planning.

**Avery:** Final say on what feels right. Nothing here requires accepting a broader feature, mechanic, or deadline. We can build Berry Delightful the same way Tag Along grew: **one small, working version at a time**.

---

### Decision register

| Topic | Latest Avery decision |
|---|---|
| First playable | **B:** arrival → surviving Earliglow harvest → compote → stall sale |
| Guidance | **B:** gentle journal nudges, free navigation |
| Outgoing items | **Stall**, not kitchen/inventory sale shortcuts |
| Incoming purchases | **Shop tab** |
| Incoming gifts | **Gifts** |
| Sale timing | **A:** immediate confirmed transaction |
| Daily action budget | **None as starting rule** (2026-10-10) |
| Development style | **Small PR → review → real iPad playtest → next question** |
| Old ambitious backlog | **Preserved but deferred**, not first-build requirements |

*Prepared by Mira from Avery's explicit choices and the current design record; proposed implementation details above are intended to keep the first slice tiny, not to preempt Avery's next decisions.*
