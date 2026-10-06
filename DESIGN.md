# Strawberry Farm — Design Doc

> Working title (placeholder): **Berry Delightful** — Avery's instinct, not settled.
> Status: design room. No building until one of the current games is finished.
> This doc grows as decisions get made. Last updated: 2026-10-06.

## The game in one breath
A cozy, finite strawberry farming game for Avery's sister Fiona — "a small playable love letter to Fiona: strawberries, sunshine, baking, growing something carefully, making a place beautiful, and eventually sharing what you made with other people."

The player inherits a small neglected patch of land and restores it into a beautiful working strawberry farm. Core loop: plant → tend → harvest → sell or process → improve the farm → unlock new varieties, growing methods, recipes, and possibilities.

## Design pillars
- **Cozy and finite.** A real ending, not endless escalation.
- **The farm is the progress bar.** Every upgrade is visible: fuller greener plants, larger redder berries, neater paths, repaired fences, flowers, bees, then the greenhouse, market setup, decorations, festival bunting. Progress should be obvious just by looking.
- **Real strawberries.** Real varieties with meaningful differences: flavour, colour, harvest season, yield, climate preferences, ideal uses.
- **Baking matters.** Jam, preserves, cakes, tarts, drinks. Gluten-free is a first-class option, never an afterthought. Every food unlocks its real-world recipe after the win.
- **Light learning.** Real cultivation, pollinator, ecology, and food facts — a dusting, never homework.
- **The pig.** Canon pet pig, named by the player, economically useless, delightful. Failed bakes go to the pig, who considers this an excellent outcome.
- **The festival is the win.** The season builds to the town's annual Strawberry Festival: the restored farm opens to visitors and the player presents a signature strawberry creation using everything learned. The farm stays playable afterward.

## Art direction
Warm, dreamy, cheerful, deliberately cute — without becoming childish or saccharine. Pastel pinks, strawberry reds, cream, soft greens. Rounded shapes, gentle shading, cute food art. A slightly nostalgic 2000s/early-2010s browser-game/CD-ROM feel: Cooking Mama energy, old Disney kitchen games, Strawberry Shortcake sweetness.

## Upgrade tree (building — tier by tier, alternating columns)
*Method decided 2026-10-06: build the upgrade foundation first, alternating kitchen/farming per tier so each tier lands as a matched set. Per upgrade we track: tier (= cost), what it unlocks (2+), and its visual change.*

### Farming upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- More strawberry plants (RECURRING — a version of this at every tier; the farm literally grows tier by tier)
- Raised planter boxes (picked over irrigation and greenhouse foundation: pairs with more-plants, biggest immediate visual payoff, feeds the bake loop with volume; irrigation fits tier 2–3, greenhouse foundation later as the aspirational line)

**Tier 2**
- *(open)*

### Kitchen upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- A couple of new recipes — complexity and ingredient count rise each tier as the player gains skill (the recipe complexity curve)
- Appliances: all three — stand mixer, decent blender, big boiling pot (breadth-first foundation; depth comes later)
  - Mixer and blender are multi-tier lines: high-end versions unlock at higher tiers

**Tier 2**
- *(open)*

## The upgrade system (in progress)
*The core of the game — where we started, 2026-10-06.*

Decided (2026-10-06):
- **Checklist-simple.** Upgrades are deliberately simple — a branching checklist, not a strategy layer. The game's complexity lives in the baking/cooking, which is how the player earns money.
- **One currency: coins.** Earned from selling harvests and (mostly) baked/processed goods.
- **Branching tree.** Each upgrade unlocks two or more new ones. Most upgrades are one-and-done (single purchase); a few have subsequent buff tiers after the first purchase.
- Upgrade areas: soil, irrigation, pollination, tools, growing methods — then greenhouse, market setup, decorations, festival bunting.
- Each upgrade changes the farm's artwork, not just its numbers — the tree is the pacing device, the farm's visible transformation is the reward.
- **The tutorial is the trunk.** It refurbishes the farm from neglected to operational while teaching the loop. The player leaves it with: inexpensive kitchen appliances and tools, a modest amount and variety of ingredients (enough for 2–4 recipes to start), and a few scruffy strawberry patches. The first upgrade branches open from there.
- **Two columns.** The upgrade tab has two columns: kitchen upgrades and farming upgrades.
- **Tiers set cost.** Each upgrade has a level/tier which determines its cost — the balancing lever. Most upgrades are single-tier (one-and-done); a few have higher tiers as subsequent buffs.
- **Upgrades feed the baking in every way:** new varieties, new ingredients, better kitchen equipment, new recipes, and better berry quality.

Open questions:
- Which branches open first after the tutorial — the specific first upgrades per column?
- Which upgrades get the multi-tier buff treatment?
- How tightly do upgrades gate each other (greenhouse → new varieties, market → processing)?

## Queued design topics
- Strawberry varieties (roster + characteristics)
- Recipes & processing
- Festival structure & the signature creation
- The pig (name? personality? idle animations?)
- Season structure & pacing
- Educational layer (how the facts surface)

## Title candidates
- Berry Delightful (Avery's instinct — current placeholder)
- Strawberry Season
- The Berry Patch
- Sun-Ripened
- A Strawberry Summer
