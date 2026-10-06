# Strawberry Farm — Design Doc

> Working title (placeholder): **Berry Delightful** — Avery's instinct, not settled.
> Status: design room. No building until one of the current games is finished.
> This doc grows as decisions get made. Last updated: 2026-10-06.

## The game in one breath
A cozy, finite strawberry farming game for Avery's sister Fiona — "a small playable love letter to Fiona: strawberries, sunshine, baking, growing something carefully, making a place beautiful, and eventually sharing what you made with other people."

The player inherits a small neglected patch of land and restores it into a beautiful working strawberry farm. Core loop: plant → tend → harvest → sell or process → improve the farm → unlock new varieties, growing methods, recipes, and possibilities.

## Structure
- **Act I (tutorial–tier 2): restoration.** The farm goes scruffy → neat → alive; the player learns the loop, builds volume, learns to bake. A private project.
- **Act II (tier 3+): the farm faces outward.** The roadside stand opens direct sales and starts the festival pipeline — the farm becomes part of the community, building toward something bigger.
- **Act III: the festival run-up.** Preparation, the signature strawberry creation, the festival itself — the win. (Confirmed 2026-10-06.)

## Design pillars
- **Cozy and finite.** A real ending, not endless escalation.
- **The farm is the progress bar.** Every upgrade is visible: fuller greener plants, larger redder berries, neater paths, repaired fences, flowers, bees, then the greenhouse, market setup, decorations, festival bunting. Progress should be obvious just by looking.
- **Real strawberries.** Real varieties with meaningful differences: flavour, colour, harvest season, yield, climate preferences, ideal uses.
- **Baking matters.** Jam, preserves, cakes, tarts, drinks. Gluten-free is a first-class option, never an afterthought. Every food unlocks its real-world recipe after the win.
- **Light learning.** Real cultivation, pollinator, ecology, and food facts — a dusting, never homework.
- **The pig.** Canon pet pig, named by the player, economically useless, delightful — wanders the farm, sleeps in straw, investigates baskets, gets muddy, appears in inconvenient places, provides personality. Failed bakes go to the pig, who considers this an excellent outcome.
- **The festival is the win.** The season builds to the town's annual Strawberry Festival: the restored farm opens to visitors and the player presents a signature strawberry creation using everything learned. The farm stays playable afterward.

## Setting
**Starvale Farm** — a fictionalized echo of Stardale Farm, the real strawberry farm near Avery and Fiona's childhood home where they used to pick strawberries together.

## Art direction
Warm, dreamy, cheerful, deliberately cute — without becoming childish or saccharine. The goal: a game Fiona could have loved opening in 2008–2012, still attractive and coherent now. Touchstones: early-2000s/early-2010s browser games, Cooking Mama, old Disney kitchen CD-ROM games, Strawberry Shortcake-type sweetness.

The world is rooted in an **early-2000s Eastern Ontario / Ottawa Valley farm community** — not generic cottagecore or anonymous farm-sim countryside. Landscape language: red or weathered barns, silos, Holstein cows in nearby fields, round hay bales, tree lines and open farmland, gravel drives, roadside produce-stand energy, handmade/painted farm signs, practical sheds, strawberry rows with straw mulch, wildflowers, clover, bees and pollinator gardens, big soft white summer clouds, warm July sunlight, local-community feeling over polished agritourism. All stylized through a soft childhood-memory lens — rounded charming cows, oversized pillowy clouds, storybook barns, warm golden hay-bale shapes. Slightly idealized, the way remembered summer places are.

**Colour language:** strawberry pink, berry red, cream, soft leaf greens, sky blue, warm wood, small touches of butter yellow. Pink prominent without making every object pink; surrounding greens keep the sweetness grounded.

**UI and objects:** soft, friendly, handmade, slightly nostalgic — rounded panels and buttons, scalloped or softly decorative labels, selective gingham, strawberry blossom and seed motifs, hand-painted sign energy, jam-jar labels, baskets, recipe cards, wooden counters, genuinely delicious-looking food, light sparkle/glow for ripe fruit, discoveries, upgrades. Avoid: ultra-clean modern minimalist UI, industrial farming imagery, exaggerated cottagecore fantasy, sterile mobile-game polish, anything globally generic.

**Visual progression (the farm is the progress bar):** early Starvale has duller/patchier plants, smaller paler fruit, uneven beds, tired fencing, sparse flowers, worn signs. As the player improves soil, water, cultivation, pollination, equipment: leaves fuller and greener, berries larger/deeper red/more abundant, more flowers and pollinators, neater paths, repaired fences and buildings, flower borders, accumulating baskets/signs/rain barrels/tools/market elements, eventually a greenhouse, late-game festival bunting. Early vs. late screenshots should read instantly as transformation through care.

**Emotional target:** summer memories, picking berries with family, warm fields, sunshine, farm stands, jam jars, clouds, community festivals, taking care of something until it becomes beautiful. The formula: cute pastel strawberry game + early-2000s Eastern Ontario farm community + nostalgic childhood summer memory. (From the Avery + ChatGPT visual-identity session, 2026-10-06.)

## Upgrade tree (building — tier by tier, alternating columns)
*Method decided 2026-10-06: build the upgrade foundation first, alternating kitchen/farming per tier so each tier lands as a matched set. Per upgrade we track: tier (= cost), what it unlocks (2+), and its visual change.*

### Farming upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- More strawberry plants (RECURRING — a version of this at every tier; the farm literally grows tier by tier)
- Raised planter boxes (picked over irrigation and greenhouse foundation: pairs with more-plants, biggest immediate visual payoff, feeds the bake loop with volume; irrigation fits tier 2–3, greenhouse foundation later as the aspirational line)

**Tier 2** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Beehive + pollinator garden (tier 1 made the farm neat, tier 2 makes it alive — flowers and bees arrive; most on-brief pick per the visual identity; converts tier-1 volume into quality; best light-learning hook. Irrigation held for tier 3; greenhouse foundation for tier 3–4.)

**Tier 3** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Irrigation (held from earlier tiers: growing *better* now that the farm has volume and pollinators)
- Roadside stand (NEW unlock at tier 3: the farm's first direct-sales structure — produce-stand energy straight from the visual identity; hand-painted sign, crates of berries. Does all three: better prices than default selling, passive sales ticking over while you bake, and the start of the festival pipeline. Opens Act II.)

**Tier 4** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Greenhouse foundation (held since tier 1: the aspirational multi-tier line begins — a down payment that feels exciting now that the player is invested; kept to two items so the tier breathes)

**Tier 5** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Greenhouse frame (the aspirational line continues)

**Tier 6** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Greenhouse glazing (the aspirational line continues; one step from planted)

### Kitchen upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- A couple of new recipes — complexity and ingredient count rise each tier as the player gains skill (the recipe complexity curve)
- Appliances: all three — stand mixer, decent blender, big boiling pot (breadth-first foundation; depth comes later)
  - Mixer and blender are multi-tier lines: high-end mixer at tier 2, high-end blender at tier 3

**Tier 2** — DECIDED 2026-10-06
- High-end stand mixer (staggered: the blender's high-end version comes at tier 3)
- New baking recipes — cakes, tarts (the batter family); tier-2 recipes require the tier-2 mixer (hard requirement at tier level — one coherent beat, not two parallel tracks)
- Recipe complexity curve continues: more ingredients, more skill

**Tier 3** — DECIDED 2026-10-06
- High-end blender (staggered from tier 2)
- New drinks recipes (require the high-end blender — hard requirement carries forward) + new preserves recipes (use the tier-1 big boiling pot; gated by tier/skill)
- The pot's own high-end moment deferred — let tiers breathe, don't overfill

**Tier 4** — DECIDED 2026-10-06
- Copper preserving pan (the pot's high-end moment; completes the equipment trilogy: mixer → blender → pan)
- Advanced preserves recipes (require the copper pan — hard requirement carries forward)

**Tier 5** — DECIDED 2026-10-06
- Bigger farmhouse oven — *bigger, not industrial* (industrial clashes with the game's anti-industrial visual identity)
- Advanced baking recipes, requiring the bigger oven (hard requirement carries forward; the next step up the baking line)

**Tier 6** — DECIDED 2026-10-06
- New greenhouse varieties (the greenhouse begins feeding the kitchen)
- New recipes using the new varieties (complexity curve continues)

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
- **Let tiers breathe.** Don't overfill a tier; each tier should have room. (2026-10-06)

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
