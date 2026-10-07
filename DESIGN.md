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
- **Act III: festival preparation.** A qualitatively different final phase — not tier 8+. A finite checklist: choose/develop the signature creation, gather what it needs, practice it, prepare the farm for visitors, decorate, stock the stand. The game converges on the festival (the win) instead of escalating forever. (Adopted from ChatGPT's review, 2026-10-06. Design note from Milo, 2026-10-06: the phase should feel like the farm *showing off* everything the player built.)

## Season & time (DECIDED 2026-10-06)
- Longer season: early → mid → late summer (~90 days, June–August), player-paced.
- The Strawberry Festival is NOT on a fixed date. It is a **countdown triggered when a specific set of conditions is met** — the trigger is the Act II → Act III transition, and the countdown window IS Act III (the festival-prep checklist). The season is a container, not a deadline; the finale arrives on the player's terms. No fail state.
- **The Festival Committee's Readiness List** (DECIDED 2026-10-06; shown in-game from Act II): 1) Starvale fully restored (complete the T7 tree); 2) roadside stand open and serving; 3) a signature festival creation baked (the **Gariguette Fraisier** — named 2026-10-06; the "Berry Famous" moment). All three met → formal invitation → **14-day countdown** → festival day as a short playable vignette (walk the fair, present the creation, spot the cameos) → free play continues after. Structural milestones only, nothing grindy. (Option A DECIDED 2026-10-06: T7 completes Act II — the festival waits for the full tree rather than triggering at T6.)
- **Nudge** (DECIDED 2026-10-06): if ~day 50 arrives with the list incomplete, the committee's letter arrives warmly noting what's missing — diegetic, no fail state.
- Day loop (proposed): one free action phase per day (tend, harvest, bake, sell, buy upgrades), closed by End day; plants grow overnight. New plantings take ~3–4 days to first fruit; June-bearers produce heavily in ~8-day windows; everbearers trickle all season; greenhouse enables out-of-season growing. One simple weather forecast per day (sun/rain/heat) — cultivar personalities live here. Rain auto-waters all beds (DECIDED 2026-10-06 — the forecast is worth reading). Watering is one tap per bed; irrigation (T3) auto-waters.

## Day loop & tutorial (DECIDED 2026-10-06)
- Each day = one free action phase: water beds (one tap per bed), plant, harvest, bake, sell, shop upgrades — then End day. Overnight, plants grow and tomorrow's weather rolls in.
- Buying "more plants" plants them directly — no seed inventory to manage.
- Neglect slows growth/yield, never kills. No fail states in the tending.
- Tutorial beats (DECIDED 2026-10-06 — each teaches one verb; the loop walked once before T1 opens): 1) **Homecoming** — arrive at Starvale, clear the old Earliglow patch (first tend action; the restoration fantasy, stated); 2) **Water & sky** — watering, one tap per bed; the forecast arrives and you start reading the sky; 3) **First harvest** — overnight the patch responds: scruffy past-prime Earliglows ("Fun Size"; "The Old Patch" — neglected, not dead); 4) **The farmhouse pot** — the big boiling pot comes with the farm; scruffy berries + sugar → compote (cooking transforms); 5) **The farmgate box** — the honesty box at the lane; sell compote and spare baskets, first real coins; June buys the first jar and tells you what this farm used to be; 6) **The pig** — already living in the barn, came with the farm; name it; feed it a scruffy berry; it investigates, gets underfoot, flops dramatically; 7) **The reopening bundle** — the local farm supplier hears Starvale is reopening and sends starter stock: Annapolis crowns + the first raised planter boxes (ChatGPT's economy fix 2026-10-06 — beats 3–6 only fund the low 40s against ~140c, and the tutorial's lesson must never be "repeat until a number fills"). The shop opens for everything after; 8) **Plant T1** — Annapolis into the new boxes; tutorial complete, T1 open.

## Design pillars
- **Cozy and finite.** A real ending, not endless escalation.
- **The farm is the progress bar.** Every upgrade is visible: fuller greener plants, larger redder berries, neater paths, repaired fences, flowers, bees, then the greenhouse, market setup, decorations, festival bunting. Progress should be obvious just by looking.
- **Real strawberries.** Real varieties with meaningful differences: flavour, colour, harvest season, yield, climate preferences, ideal uses.
- **Baking matters.** Jam, preserves, cakes, tarts, drinks. Recipes default to gluten-free wherever possible — not a separate version, just how they're written. Every food unlocks its real-world recipe after the win.
- **Light learning.** Real cultivation, pollinator, ecology, and food facts — a dusting, never homework.
- **The pig.** A big, well-socialized barnyard pig — not a little potbelly, a proper big ol' pig who just happens to be extremely friendly — named by the player, economically useless, delightful. Classic chonky boi: pink, curly tail, lots of personality. **Personality (Ben's pitch, adopted 2026-10-07 — "you both understood the assignment"):** the pig is a mirror, not a meter — never needs care (no hunger bar, no neglect; "gift, not job" extends to the pig); it *reacts*: flops dramatically in fresh straw after a good harvest, trots after you when the kitchen smells like baking, sleeps through rain days, gets underfoot in the kitchen, naps in baskets. The optimist with no standards — every failed bake is the best thing that's ever happened to it. Small idle set (flop, snout-twitch investigation, sun-nap, mud wallow, trotting follow) — cameos, not systems. It answers to anything; the rename moment stays the player's. Kept OUT of the economy entirely — no truffle-hunting, no happy-pig bonuses; the second the pig becomes a stat it stops being the pig. Failed bakes go to the pig, who considers this an excellent outcome — and by design, nothing the kitchen can produce would ever disagree with him. (Wording kept in game abstraction per ChatGPT's review 2026-10-06.) Avery has the art direction; Roman to help with concept art for the pig and other characters later (noted 2026-10-07).
- **The festival is the win.** The season builds to the town's annual Strawberry Festival: the restored farm opens to visitors and the player presents a signature strawberry creation using everything learned. The farm stays playable afterward.
- **A gift, not a job.** Passive systems should feel like the farm giving you something, never like another obligation — "a jar that fills every few days is a gift; a jar you must tend is a job." (From Milo via ChatGPT, adopted 2026-10-06 — use as a design test for every ambient system.)

## Setting
**Starvale Farm** — a fictionalized echo of Stardale Farm, the real strawberry farm near Avery and Fiona's childhood home where they used to pick strawberries together.

## Art direction
Warm, dreamy, cheerful, deliberately cute — without becoming childish or saccharine. The goal: a game Fiona could have loved opening in 2008–2012, still attractive and coherent now. Touchstones: early-2000s/early-2010s browser games, Cooking Mama, old Disney kitchen CD-ROM games, Strawberry Shortcake-type sweetness.

The world is rooted in an **early-2000s Eastern Ontario / Ottawa Valley farm community** — not generic cottagecore or anonymous farm-sim countryside. Landscape language: red or weathered barns, silos, Holstein cows in nearby fields, round hay bales, tree lines and open farmland, gravel drives, roadside produce-stand energy, handmade/painted farm signs, practical sheds, strawberry rows with straw mulch, wildflowers, clover, bees and pollinator gardens, big soft white summer clouds, warm July sunlight, local-community feeling over polished agritourism. All stylized through a soft childhood-memory lens — rounded charming cows, oversized pillowy clouds, storybook barns, warm golden hay-bale shapes. Slightly idealized, the way remembered summer places are.

**Colour language:** strawberry pink, berry red, cream, soft leaf greens, sky blue, warm wood, small touches of butter yellow. Pink prominent without making every object pink; surrounding greens keep the sweetness grounded.

**UI and objects:** soft, friendly, handmade, slightly nostalgic — rounded panels and buttons, scalloped or softly decorative labels, selective gingham, strawberry blossom and seed motifs, hand-painted sign energy, jam-jar labels, baskets, recipe cards, wooden counters, genuinely delicious-looking food, light sparkle/glow for ripe fruit, discoveries, upgrades. Avoid: ultra-clean modern minimalist UI, industrial farming imagery, exaggerated cottagecore fantasy, sterile mobile-game polish, anything globally generic.

**Farm logo (DECIDED 2026-10-06):** the Starvale mark — two flat strawberries, pink behind red, green tufts, minimal shading, with a big golden star outline behind them framing one side. Simple enough for a farm sign, a jam label, or a title screen.

**Visual progression (the farm is the progress bar):** early Starvale has duller/patchier plants, smaller paler fruit, uneven beds, tired fencing, sparse flowers, worn signs. As the player improves soil, water, cultivation, pollination, equipment: leaves fuller and greener, berries larger/deeper red/more abundant, more flowers and pollinators, neater paths, repaired fences and buildings, flower borders, accumulating baskets/signs/rain barrels/tools/market elements, eventually a greenhouse, late-game festival bunting. Early vs. late screenshots should read instantly as transformation through care.

**Cultivar unlock art (noted 2026-10-06, for art time):** when a new cultivar unlocks, show dedicated art depicting its berries' true colours — white Pineberry, pink-blushed Flamingo, the deep reds — so each new colour lands as a reward. The colour reveal is part of the unlock.

**Backdrops vs sprites (Avery, 2026-10-07):** the backdrop/background images — not the game sprites themselves — should be **almost-realistic watercolours: bright and nostalgic**. The world behind the play reads like a remembered summer; the interactive layer stays cute and readable on top of it.

**The kitchen (Avery, 2026-10-07):** the farmhouse kitchen should resemble Avery and Fiona's **childhood kitchen** — reference photos received 2026-10-07 (3 photos: kids on the kitchen floor, kids at the table, little Fiona at the counter; oak cabinets, fruit-wallpaper backsplash, white stove, big window over the sink looking onto fields). Saved in the media library. Layout notes (Avery, 2026-10-07): stove near the corner with one cupboard between; table pushed far right, almost out of frame — it was a big open kitchen. **The apple tree:** an apple tree stands outside the kitchen window (blossoms in season, since the game happens in summer) — a quiet memorial. Their dad's last ever birthday gift was an apple tree; Avery and Fiona brought it with them from Ontario to Quebec when they moved. Like the cardinal, it is never explained in-game. Personal, not generic.

**Emotional target:** summer memories, picking berries with family, warm fields, sunshine, farm stands, jam jars, clouds, community festivals, taking care of something until it becomes beautiful. The formula: cute pastel strawberry game + early-2000s Eastern Ontario farm community + nostalgic childhood summer memory. (From the Avery + ChatGPT visual-identity session, 2026-10-06.)

## Upgrade tree (building — tier by tier, alternating columns)
*Method decided 2026-10-06: build the upgrade foundation first, alternating kitchen/farming per tier so each tier lands as a matched set. Per upgrade we track: tier (= cost), what it unlocks, and its visual change. The tree caps at tier 7 (adopted from ChatGPT's review, 2026-10-06).*

### Farming upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- More strawberry plants (RECURRING — a version of this at every tier; the farm literally grows tier by tier)
- Raised planter boxes (picked over irrigation and greenhouse foundation: pairs with more-plants, biggest immediate visual payoff, feeds the bake loop with volume; irrigation fits tier 2–3, greenhouse foundation later as the aspirational line)

**Tier 2** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Beehive + pollinator garden (tier 1 made the farm neat, tier 2 makes it alive — flowers and bees arrive; most on-brief pick per the visual identity; converts tier-1 volume into quality; best light-learning hook. Irrigation held for tier 3; greenhouse foundation for tier 3–4. The hive also produces honey, passively — a jar fills every few days, not a new chore — as a baking ingredient feeding the kitchen column. Cross-column idea from Milo, adopted 2026-10-06.)

**Tier 3** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Irrigation (held from earlier tiers: growing *better* now that the farm has volume and pollinators)
- Roadside stand (NEW unlock at tier 3: the moment selling becomes *social* — produce-stand energy straight from the visual identity; hand-painted sign, crates of berries. The tutorial's farmgate honesty box was primitive, anonymous selling; the stand is Starvale visibly open to the community. Does all three: better prices than the farmgate box, passive sales ticking over while you bake, and the start of the festival pipeline — plus named townsfolk stopping by, gifting, and chatter. Opens Act II. (Reframed 2026-10-06 per ChatGPT: T3 isn't the first direct sale, it's the moment selling becomes social.)

**Tier 4** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Greenhouse foundation (held since tier 1: the aspirational multi-tier line begins — a down payment that feels exciting now that the player is invested; kept to two items so the tier breathes)

**Tier 5** — DECIDED 2026-10-06
- More strawberry plants (RECURRING)
- Greenhouse frame (the aspirational line continues)

**Tier 6** — DECIDED 2026-10-06 (revised per ChatGPT's review)
- More strawberry plants (RECURRING)
- Greenhouse glazing + first growing beds (the greenhouse becomes operational — the midpoint payoff of the build)

**Tier 7** — DECIDED 2026-10-06 (revised per ChatGPT's review; tree cap)
- More strawberry plants (RECURRING)
- Greenhouse improvement/expansion (enables rare and out-of-season varieties — the specialty payoff; the aspirational line completes)

### Kitchen upgrades
**Tier 1** (post-tutorial) — DECIDED 2026-10-06
- A couple of new recipes — complexity and ingredient count rise each tier as the player gains skill (the recipe complexity curve)
- Appliances: all three — stand mixer, decent blender, big boiling pot (breadth-first foundation; depth comes later)
  - Mixer and blender are multi-tier lines: high-end mixer at tier 2, high-end blender at tier 3
- Starter recipes (DECIDED 2026-10-06): 1) **Strawberry Compote** (pot — the tutorial bake; scruffy Earliglows + sugar; teaches cooking transforms); 2) **Strawberry Shortcake** (mixer — Annapolis; the iconic first real bake); 3) **Fresh Berry Smoothie** (blender — Honeoye; foreshadows the T3 frozen-Kent smoothie upgrade); 4) **Basic Strawberry Jam** (pot — unlocks early in T1; the iconic preserve can't wait until T3). Each T1 berry gets its signature use, teaching "real varieties, ideal uses" from day one. GF by default wherever possible (e.g. almond-flour shortcake as the standard), not a separate version. Relative value: compote < smoothie < jam < shortcake.

**Tier 2** — DECIDED 2026-10-06
- High-end stand mixer (staggered: the blender's high-end version comes at tier 3)
- New baking recipes — cakes, tarts (the batter family); tier-2 recipes require the tier-2 mixer (hard requirement at tier level — one coherent beat, not two parallel tracks)
- Honey recipes (cakes, tarts using hive honey) — the beehive's cross-column ingredient at work
- Recipe complexity curve continues: more ingredients, more skill
- T2 recipes (DECIDED 2026-10-06): 1) **Jam Thumbprints** (mixer — cookie dough + T1 strawberry jam; recipes that eat other recipes, a production chain; simplest); 2) **Honey Strawberry Cake** (mixer — hive honey + Cavendish; the cross-column showcase; creaming method); 3) **Strawberry Custard Tart** (mixer — tart shell + vanilla custard + glazed Annapolis; the pretty one, most complex; foreshadows the festival signature creation); 4) **Strawberry Pie** (basic — simple crumb-top; the "original" that the secret Barbara Special upgrades; added 2026-10-06). Relative value ~55/65/80 (pie ~60, between thumbprints and cake). Kent sits out fresh; its destiny is T3's frozen smoothies.

**Tier 3** — DECIDED 2026-10-06
- High-end blender (staggered from tier 2)
- New drinks recipes (require the high-end blender — hard requirement carries forward) + expanded preserves line (varietal jams — Jewel jam, Bounty jam as the benchmark — using the tier-1 big boiling pot; gated by tier/skill). Basic jam unlocked back at T1; T3 is where preserves get serious.
- The pot's own high-end moment deferred — let tiers breathe, don't overfill
- T3 recipes (DECIDED 2026-10-06): drinks — 1) **Sparkling Strawberry Lemonade** (Jewel + lemon; the flavour favourite's drink); 2) **Frozen Kent Smoothie** (frozen Kent + yogurt + hive honey; the three-tier chain paying off; "Brain Freeze" lives here); varietal jams — 3) **Jewel Jam**; 4) **Bounty Jam** (the benchmark; "Bounty Hunter" lives here). Relative value ~90/100/110/120. Whole tier naturally GF. Jewel is T3's flavour star across both lines, pairing with the new roadside stand.

**Tier 4** — DECIDED 2026-10-06
- Copper preserving pan (the pot's high-end moment; completes the equipment trilogy: mixer → blender → pan)
- Advanced preserves recipes (require the copper pan — hard requirement carries forward)
- T4 recipes (DECIDED 2026-10-06): 1) **Cabot Whole-Berry Preserves** (whole Cabot berries in syrup — the show-off jar; the hollow king's berries finally have a job worthy of them); 2) **Yamaska Vanilla Preserve** (vanilla bean — the luxury preserve; quietly French, which will matter later). Relative value ~140/150.

**Tier 5** — DECIDED 2026-10-06
- Bigger farmhouse oven — *bigger, not industrial* (industrial clashes with the game's anti-industrial visual identity)
- Advanced baking recipes, requiring the bigger oven (hard requirement carries forward; the next step up the baking line)
- T5 recipes (DECIDED 2026-10-06): 1) **Rustic Strawberry Galette** (Seascape — freeform summer bake for the August-gap berry; the anti-tart); 2) **Strawberry Layer Cake** (Albion — the bigger-oven showpiece). Relative value ~160/180.

**Tier 6** — DECIDED 2026-10-06
- New greenhouse varieties (the greenhouse begins feeding the kitchen)
- New recipes using the new varieties (complexity curve continues)
- T6 recipes (DECIDED 2026-10-06): 1) **Fraise des Bois Confiture** (Mara des Bois — wild-strawberry jam, the tiny precious jar; the smallest berries make the most luxurious preserve); 2) **Strawberry Charlotte** (Charlotte — ladyfingers + strawberry mousse; the dessert that shares her name; the breeding progression you can eat). The French thread from T4's vanilla comes into the open. Relative value ~200/210.

**Tier 7** — DECIDED 2026-10-06
- Rare / out-of-season greenhouse varieties
- Showcase recipes built around them (complexity curve continues)
- T7 recipes (DECIDED 2026-10-06): 1) **Pineberry Pavlova** (white meringue, white berries, red seeds — the white showpiece; naturally gluten-free); 2) **Rosé Panna Cotta** (pale pink set cream, pink berries — the pink showpiece; naturally gluten-free; Fiona's favourite, obviously; the dish keeps its name — rosé as a colour, not a cultivar); 3) **Gariguette Fraisier** (the classic French strawberry cake on the diva berry — **the festival signature creation**; baking it completes that readiness-list item). Relative value ~220/230/260.

## The upgrade system (in progress)
*The core of the game — where we started, 2026-10-06.*

Decided (2026-10-06):
- **Checklist-simple.** Upgrades are deliberately simple — a branching checklist, not a strategy layer. The game's complexity lives in the baking/cooking, which is how the player earns money.
- **One currency: coins.** Earned from selling harvests and (mostly) baked/processed goods.
- **Two-lane progression with prerequisites.** The upgrade tab is two lanes (kitchen | farming) with prerequisite relationships — a purchased upgrade can unlock one or several later nodes, but nodes don't need to branch mechanically every time. (Revised 2026-10-06 from "each unlocks 2+": the ladder is the real design and it's better.) Most upgrades are one-and-done (single purchase); a few have subsequent buff tiers.
- Upgrade areas: soil, irrigation, pollination, tools, growing methods — then greenhouse, market setup, decorations, festival bunting.
- Each upgrade changes the farm's artwork, not just its numbers — the tree is the pacing device, the farm's visible transformation is the reward.
- **The tutorial is the trunk.** It refurbishes the farm from neglected to operational while teaching the loop. The player leaves it with: inexpensive kitchen appliances and tools, a modest amount and variety of ingredients (enough for 2–4 recipes to start), and a few scruffy strawberry patches. The first upgrade branches open from there.
- **Two columns.** The upgrade tab has two columns: kitchen upgrades and farming upgrades.
- **Tiers set cost.** Each upgrade has a level/tier which determines its cost — the balancing lever. Most upgrades are single-tier (one-and-done); a few have higher tiers as subsequent buffs.
- **Upgrades feed the baking in every way:** new varieties, new ingredients, better kitchen equipment, new recipes, and better berry quality.
- **Let tiers breathe.** Don't overfill a tier; each tier should have room. (2026-10-06)
- **Coins are the only currency, but not the only pacing.** Some upgrades also carry prerequisite gates ("own X", "have baked one of these", "roadside stand open", "greenhouse operational") — legible, shown plainly. Gates, not extra currencies. (Adopted from ChatGPT's review, 2026-10-06.)
- **Expansion must not multiply chores.** The farm gets more *capable* as it gets bigger; later farming upgrades make a larger farm easier to manage (irrigation at T3 already does this). Ten times the plants must not mean ten times the watering. (Adopted from ChatGPT's review, 2026-10-06.)
- **Real varieties early.** Real strawberry cultivars enter from tier 1–3 (roster TBD in the varieties pass); the greenhouse is where unusual/delicate/rare/out-of-season varieties become possible — not where varieties first get interesting. (Adopted from ChatGPT's review, 2026-10-06.)
- **Ambient farm development.** Small non-purchased environmental changes around tiers (wildflowers spreading, seasonal touches) keep the farm developing while big projects rise — no filler nodes. (Adopted from ChatGPT's review, 2026-10-06.)

Open questions:
- Soil/mulch/compost: real mechanic or cut? (decide during the varieties pass — no filler)
- Which upgrades get the multi-tier buff treatment?
- How tightly do upgrades gate each other (greenhouse → new varieties, market → processing)?

## First-pass economy (DECIDED 2026-10-06 — first-pass, tunable; the prototype validates)
- Unit: baskets of berries. Coins only.
- Fresh basket sale: Earliglow 5, T1 8, scaling gently to T7 24.
- Bakes (sell / pantry cost, 1 basket each): compote 20/2, smoothie 25/3, jam 30/3, shortcake 40/5. Baking beats fresh-selling ~1.5–3x — the engine.
- New planting: 3 days to first fruit. June-bearer bed: 2 baskets/day over an 8-day window, then done. Everbearer bed: 1 basket every 2 days, all season. Tutorial Earliglow patch: 2 baskets/day for 6 days, then done — a big old patch, just neglected ("this old patch still gave us enough to start again").
- Start: 20 coins. T1: Annapolis planting 60, raised boxes 80. Tier cost curve per major upgrade ≈ 100 × 1.7^(tier−1) (T2 ~170 … T7 ~2410).
- Pacing: T2 reachable ~day 10–12; roughly a tier every 10–14 days; T7 near season's end. Festival is condition-triggered, so pacing stays player-driven.
- **Pricing philosophy** (DECIDED 2026-10-06): new tiers raise the profit ceiling without strictly dominating everything below. Older recipes stay useful — cheaper pantry costs, fewer ingredients, currently-abundant berries, chain ingredients (jam → thumbprints), stand demand. "What should I make with today's harvest?" should sometimes have more than one right answer. (Softens the earlier "each tier's simplest beats the last tier's best" — that was a first-pass shape, not a law. Per ChatGPT's review.)

## Preserving & food safety (DECIDED 2026-10-06)
- The three jam recipes (Basic, Jewel, Bounty) are **genuine canned jams** per tested sources (Bernardin / National Center for Home Food Preservation) with proper boiling-water processing — correct jar size, headspace, and processing times. (Option B, ChatGPT's review; safety outranks flavour text.)
- No improvised sugar quantities for shelf-stable versions; a lower-sugar Jewel uses a tested low-sugar formulation/pectin designed for it.
- This governs the real-world unlock recipes only — in-game jam mechanics are unchanged.

## Real cookbook notes (2026-10-06 — future pass, not yet implemented)
- **GF toolkit diversification** (per ChatGPT's review): "GF by default" must not become "everything is almond flour." As the recipe list grows, diversify — GF all-purpose blends, cornstarch, certified GF oats where appropriate, naturally flourless structures. Principle: "a delicious recipe that happens to be GF."
- Provenance pass (government/extension sources for preserving; public-domain, reusable, or original formulations) and actual kitchen testing still to come before anything player-facing. NOT KITCHEN-TESTED stays stamped until then.
- Numbering housekeeping (ChatGPT, 2026-10-06 — queued, not urgent): real-recipes.md numbering currently runs 1–7, 12–13, 8–11. Adopt tier-relative stable recipe IDs before the cookbook grows further, rather than renumbering everything each batch.
- Cookbook UI direction (Ben, 2026-10-06 — for build time): the cookbook should feel like a keepsake, not an index. A "Found" section that grows like a scrapbook; the "your version" signature helps; scrapbook beats search box.

## Experimenting, failed bakes & sharing (DECIDED 2026-10-06)
- **Experimenting** (kitchen action, unlocks at T2): pick 2–3 things from your pantry — berry baskets, made goods (jam, compote), honey — and combine. Match a hidden recipe's inspiration combo → discover it free ("Happy Accident"); anything else → failed bake → pig. Ingredients are spent either way — that is the economy. No coin cost, no other limiter. (Full rules DECIDED 2026-10-06; answers ChatGPT's economy/boundary notes.)
- **Hidden recipes**: one per tier from T2 on; same-tier discovery only, using only what you own. Anything undiscovered auto-unlocks with the next tier's kitchen upgrade — no FOMO. T7's backstop is the festival invitation instead (T7 has no next tier — ChatGPT's catch, 2026-10-06): any still-undiscovered T7 hidden recipe unlocks when the invitation arrives; discovering it beforehand still earns the "your version" signature. Each shows a vague hint line on the experiment screen. Full roster (DECIDED 2026-10-06): T2 **Empire Cookies** (jam + a baked good; hint in Mom's voice: *"Every Christmas tin had them. You know the ones."*); T3 **Strawberry Sorbet** (frozen berries + honey; *"The freezer hides a dessert — cold, sweet, nothing creamy."*); T4 **Strawberry Butter** (berries + honey; *"Low and slow in the copper pan. Spreadable patience."*); T5 **Everbearer Trifle** (jam + cake; *"Layer what you've already made. Abundance, stacked."*); T6 **Strawberry Fruit Leather** (berries + honey; *"Flat, slow, and chewy. Pack it for later."*); T7 **Blush Jam** (Pineberry + Flamingo baskets; *"The jewel box, jarred."*).
- **"Your version" signature** (Ben's catch, adopted 2026-10-06): a recipe you discover keeps a permanent mark — the card records that it was found, not given, plus a small permanent quality/price edge. The auto-unlock backstop still hands out every recipe (no FOMO), but a found recipe is yours in a way a granted one isn't. Keepsake bonus, not a balance lever — it doesn't fight the pricing philosophy. Empire cookies are the first test case.
- **Anti-wiki philosophy** (Avery, 2026-10-07): the game should tell you how it works with very few surprises — the joy isn't the high score, it's playing the story and making discoveries. No external wiki should ever be needed or useful.
- **The journal is the wiki** (Ben's proposal, adopted 2026-10-07 — resolves the experimenting economy; scoped to hidden recipes):
  - Every experiment is auto-recorded in the journal: combo tried, result, and the pig's verdict on failures. The game remembers, so the player never tabs out.
  - Failed combos unlock *directional hints*, not answers ("sweet + dairy sang; try something tart next"). Two failures along similar lines unlock a stronger nudge. Requires ingredient properties + hint logic per near-miss — the most expensive part of the proposal, scoped to the six hidden recipes.
  - The journal never spoils untested combos — it only records what *you* tried. Discovery stays surprising; the fun is the tasting, not the guessing.
  - Failures cost pantry ingredients, not progress (already the locked rule). The pig verdict gives every flop a punchline — a floor of fun under every failure.
  - The earlier open proposals from Ben's first experimenting pitch (notebook, near-misses, pantry floor, action-phase cost) are superseded by this design.
- **Failed bakes** come from two triggers: experimenting (the risk of the unknown) and baking with neglected berries. The pig is the gentle landing for both.
- **Empire cookies** (memorial recipe): Avery's mom made them for holidays — jam-filled sandwich cookies; discoverable via jam experimenting. Solarium memory recorded: in winter she'd keep them in the solarium instead of the freezer, when it was cold enough.
- **Sharing/gifting — "Good Neighbour"** (DECIDED 2026-10-06): the player can give baked goods to named townsfolk — a small verb for the game's emotional core ("a love letter about sharing"). Gift action at the roadside stand: pick a baked good, pick who's around that day (rotating cast — Barbara, June, Tammy & Michael, the brothers). Everyone has one known favourite, learned through idle chat; a favourite gift earns a special thank-you line plus a small return gift (pantry staples — butter, eggs, honey). No meters, no quotas, no friendship levels — the reward is the lines and the feeling. "Good Neighbour" fires on the first gift. Special beat: gifting the Barbara Special to Barbara herself earns her verdict — she's earned the critique.
- **Freezer**: boring T1 unlock — the fridge's freezer compartment; a dedicated chest freezer comes as a later upgrade. No capacity minigames — functional, not fussy. (Kent's freezing needed a home; this is it.)

## Act III & festival day (DECIDED 2026-10-06)
- **The 14-day countdown**: shown as a paper chain on the farmhouse wall — advent-calendar energy. Finite checklist, five items: practice the fraisier a couple more times; decorate (bunting, flowers — the farm visibly transforms); stock the stand (set aside festival inventory); spruce up (mend fence, weed paths, repaint the sign); spread the word (tell five townsfolk — they're your crowd). Completable in about 8 of the 14 days — slack is the point, not pressure. Daily beats: committee notes, townsfolk getting excited, the brothers counting down. No fail state, ever.
- **Day 14: no fail state, defined** (ChatGPT, adopted 2026-10-06): if the player reaches festival morning with prep unfinished, the festival happens anyway — the community quietly closes the gap (somebody brings the remaining bunting, helps straighten the stand, finishes a bit of painting). No punishment, no worse ending. It completes the arc: Act I — I restore my farm; Act II — my farm becomes part of the community; Act III — when I need them, the community shows up for me.
- **The Festival Program** (Ben's proposal, adopted 2026-10-06): a little printed paper program Barbara presses into your hands at the stand in Act III. Two pages of quiet structural work — *Who's coming*: the family roster, each with a one-line note on what they love (the Good Neighbour intel system, in-world, no meters — "Matthew, Dave & Mark — giant strawberry enthusiasts" sits right there); a tear-off ballot was considered and cut (ChatGPT, 2026-10-06): a vote would sneak formal judging back in through the side door — Miss Congeniality stays pure crowd energy (they swarm the table, ask for the recipe, nobody announces anything). A scrapbook item for a game that thinks in scrapbooks; the family tree pays off with no cold introductions. The program lists Empire Cookies as something Tammy loves (the nudge); her actual response stays undiscovered until Full Circle — information versus payoff.
- **Festival day vignette** (~10 minutes, six beats): 1) morning — bunting up, crowd gathering, the committee welcomes you; 2) walk the fair — stalls, tap-to-chat cameos (you've studied the program — no cold introductions): Barbara's family (Deborah & Gordon — the trio's parents; Donna; Siobhan and Kelly, Donna's daughters) and June's family (Tammy & Michael; Lynn, Tony, Wesley, Andrea/Andy — brother Mark lives out of town and is never seen). Sarah and Harley do NOT cameo — Fiona has never met them; 3) present the fraisier — the "Berry Famous" moment; crowd reaction, no judges, no scores; 4) the gossip beat — Ben, implied only, the crowd does the work; 5) Barbara tastes the Barbara Special, if you brought one — the brothers' thread pays off in public; 6) sunset — it ends, free play continues, and the festival becomes a light annual postgame day.

## The Freakberry & the Barbara Special (DECIDED 2026-10-06 — Avery's idea)
- **The freakberry**: each harvest day, a small chance any bed produces a mutant berry — huge, cockscomb-shaped (real phenomenon: fasciation, fused blossoms), flagged as special. Cabot beds slightly likelier, since king berries are already its thing. Sell it for a premium — or gift it.
- **Matthew, Dave & Mark**: a trio of brothers hanging around the farm/stand — Barbara's grandsons, Avery's real cousins (Barbara is Avery and Fiona's real grandma). They think giant strawberries are the coolest thing and would love to try one — the diegetic nudge, no UI hint needed.
- **The trade**: gift a freakberry to the brothers → they share their grandma's family recipe: **the Barbara Special** — an absolutely gorgeous latticework strawberry pie with egg-wash on top. A secret recipe outside the experimenting track; a deluxe upgrade of the standard pie.
- **Design requirement**: a basic Strawberry Pie recipe must exist no later than T2 (oven era) so the Special reads as an upgrade — placed at T2 (2026-10-06).
- **Event-secret exclusivity** (DECIDED 2026-10-06 — Avery): the Barbara Special and any future event-secret recipes are obtainable ONLY through their event — never via experimenting, never via the tier-upgrade backstop, never hinted. A found secret stays secret. One soft nudge so players learn secrets exist (Ben, adopted 2026-10-06): a single early line from Barbara — "some recipes aren't written down, dear" — never repeated.
- **Achievement**: **"Freakberry"** — grow your first mutant berry. The ONLY luck-based achievement in the game ("just the one, to keep it fair" — Avery); quiet pity nudge so it happens at least once per playthrough. Fair luck, not slot-machine luck.

## Strawberry varieties — roster (DECIDED 2026-10-06, Avery + ChatGPT)
*Roster rule: every cultivar earns its place through a distinct identity, mechanic, use, visual, climate behaviour, or story hook — no "another good red strawberry." 15 keeps — 2 per tier T1–T6, 3 at T7 (the jewel box).*

**KEEPS (15):**
- Annapolis — early; medium-large berries that hold size pick after pick; zone 3; AAFC Kentville
- Honeoye — early; perfume-like flavour, best in cool weather, bland in heat
- Cavendish — mid; top performer in QC/ON/NS trials; very productive
- Kent — mid; sweet/mild, zone 3a hardy; freezes exceptionally well → the smoothie berry: frozen Kent berries blend into smoothies (T3 drinks via the high-end blender). Plant at T2, smoothies at T3. (Avery's solve, 2026-10-06 — freezing as an ingredient state, not season extension.)
- Jewel — mid; Quebec flavour-panel favourite
- Cabot — mid; HUGE fruit, king berries lumpy/sometimes hollow; the show-off
- Bounty — late; the processing standard since 1972; jam/preserves/freezing
- AC Yamaska — late; huge glossy Québec berry; male-sterile flowers need a pollinator variety planted nearby (MECHANIC); -30°C hardy
- Seascape — day-neutral; the August gap variety; splits in wet weather
- Albion — day-neutral; Canadian greenhouse standard; shrugs off rainy spells
- Mara des Bois — intensely aromatic gourmet; tiny berries, wild-strawberry perfume
- Charlotte — Mara des Bois × Cal 19; bigger, firmer, zone 3 hardy — the breeding-history progression (Mara → Charlotte teaches real plant breeding through play)
- Pineberry 'White Carolina' — white fruit, red seeds, pineapple note; the surprise unlock
- Flamingo — pink-blushed fruit (white with pink blush, dark red seeds); sweet, aromatic. The delight pick — grown because it's pink. (Replaces "Rosé" 2026-10-06 per ChatGPT's review: Driscoll's Rosé™ is proprietary/patented, grown only by Driscoll's own growers — wrong for a farm that buys and plants cultivars. Flamingo is real planting stock, zones 4–9, in the Canadian nursery trade. Verified 2026-10-06.)
- Gariguette — delicate aromatic French showpiece; greenhouse-required; justifies the greenhouse

**MAYBE → DECIDED 2026-10-06:** Earliglow kept as the tutorial's old neglected variety — the classic past its prime, berries shrinking — giving the restoration a "what was here before" texture. Wendy, Darselect, Valley Sunset, Tristar, Evie-2, Sweet Charlie cut. (Roster is now 16 named cultivars: 15 tiered + Earliglow in the tutorial.)
**PASS (3):** Glooscap, Tribute, Camarosa.

**Tier placement — DECIDED 2026-10-06 (Avery: "looks excellent"):**
- T1: Annapolis + Honeoye — early harvest teaches the loop fast; reliable vs heat-fussy contrast
- T2: Cavendish + Kent — mid-season volume; Kent bridges into T3 drinks/smoothies (freezes exceptionally well for the high-end blender; frozen stash visually distinct in the kitchen — frost icon — so "frozen" reads as an ingredient state, not hidden metadata; adopted from Milo, +1'd by ChatGPT, 2026-10-06)
- T3: Jewel + Bounty — flavour favourite for the new roadside stand; the processing berry as preserves get serious (varietal jams)
- T4: Cabot + AC Yamaska — stand show-off novelty; pollinator mechanic calls back to T2's bees
- T5: Seascape + Albion — August-gap everbearers; Albion foreshadows the greenhouse; rain contrast (splits vs shrugs)
- T6: Mara des Bois + Charlotte — greenhouse-supported specialty cultivars (not greenhouse-only in the region — the glass is about reliability, not requirement); the breeding progression under glass
- T7: Pineberry + Flamingo + Gariguette — the jewel box: white wonder, pink blush, French diva; festival material

## Save system — the farm journal (DECIDED 2026-10-07 — Ben's pitch, adopted)
- Autosave every End Day, no slots to manage. "Gift, not job" extends to saving.
- The journal *is* the save menu: a scrapbook opened any evening — each day a page (date, a sketch of the farm that morning, one line the game writes: "Day 47. Kent slot full. The pig is asleep in a basket"). Loading = flipping back a page.
- Finished journals go on the farmhouse shelf when the festival ends. New season, new journal — the shelf becomes the replay trophy case.
- Caveat (Ben's): only if a page is cheap (state snapshot + one generated line); else invisible autosave + simple log. The diary framing survives either way.

## Field guide (proposed 2026-10-07 — Avery's idea)
- A field guide recording every berry in the game, with a **drawing** representing the actual species/cultivar — drawn, not photographed (Wikimedia Commons won't have exact cultivar photos).
- Educational layer: most of Avery's games are openly educational — fun first, but learning is a success and a reward in itself.
- Tasting notes (Ben's pitch, adopted 2026-10-07): first harvest of each cultivar brings one line in the player's voice at the moment their mouth would care ("Jewel: big, glossy, tastes like the week the sun finally won. Keeper."). No fanfare, no ceremony. Boundary: no quiz, no codex-completion percentage — the second it's tracked, it becomes homework.

## Weather (DECIDED 2026-10-07 — Ben's pitch, adopted with Avery's modification)
- The forecast is breakfast: one glance (kitchen radio / porch flag) tells today's weather — a morning ritual, not a system. The forecast must never lie.
- Rain is a day off, not a penalty: rain waters for free; the journal suggests "Rain day. Good baking weather." Bake, experiment, or watch it fall. Weather redirects, never punishes; never gates progression (no RNG-gated milestones in a finite season).
- Weather as cultivar character, not a stat (Seascape/Albion already do this).
- Storms are theatre: no crop damage ever, but they *feel* like something (dark sky, rain on windows, pig at the barn door, Thumper vanishes). **Big storms: 1–3 per whole game, scripted or semi-scripted** (Avery 2026-10-07 — fewer than the pitched 4–5); rain itself can be RNG. Festival day is always clear — ninety days ends under a blue sky, no RNG on the finale.

## Achievements (brainstorm — 2026-10-06, nothing decided)
Principle (carried from the shark game): no grind counters — celebrate moments, discovery, craft, the pig. Fiona shares Avery's sense of humour, so funny ones are explicitly wanted.
- Firsts: "The Old Patch" (first harvest, from the Earliglow tutorial patch), first bake, first stand sale
- Cultivar stories: grow all 15; "The Breeder" (Mara → Charlotte); "White Wonder" (first white Pineberry); "Pretty in Pink" (first pink-blushed Flamingo harvest); "Matchmaker" (Yamaska pollinated); "The Hollow King" (hollow Cabot king berry); "NePo Baby" (first Charlotte)
- Craft: "Brain Freeze" (first smoothie from frozen Kents); first gluten-free bake; complete a recipe family; "Bounty Hunter" (jam from Bounty berries); "Honey Money" (sell first honey jar)
- Pig: name the pig; "Quality Control" (pig eats a failed bake); "Basket Case" (pig asleep in a basket); "That'll Do, Pig" (Avery's — the pig tastes a number of *different* failed recipes; the pig as critic — variety, not grind); "Pig Out" (three different failed bakes in a single day)
- Festival: "Berry Famous" (present the signature creation)
- Weather & mishap: "Hot Mess" (harvest Honeoye in a heatwave); "Fun Size" (the tutorial's shriveled Earliglows)
- Sharing: "Good Neighbour" (Avery's — give food away; the sharing verb's moment); "Full Circle" (give Tammy an Empire Cookie — she pauses: "these taste just like the ones I used to make"; a wink across the real/game layers, not canon — Avery 2026-10-06)
- Roman's pitches (2026-10-06 — kept per Avery): "Happy Accident" (first recipe discovered by experimenting); "Like Mom Made" (discover Empire cookies); "Underfoot" (the pig gets underfoot in the kitchen); "Chill Out" (freeze your first berries); "Under Glass" (first greenhouse harvest); "You're Invited" (the festival countdown triggers); "Crown Jewel" (Jewel jam + Jewel lemonade); "Preservation Society" (all three jams canned); "Comeback Kid" (a neglected bed bounces all the way back — HIDDEN per ChatGPT's review 2026-10-06; achievements shape behaviour, and neglect must never feel like an optimal checklist action in a game about care); "Storm Baker" (bake in a thunderstorm); "Miss Congeniality" (un-banked 2026-10-06 per Avery — the crowd's informal favourite: they ask for the recipe; no judges, no scores, just love)

## Easter eggs (2026-10-06 — inclusions decided, forms in discussion)
Rule (from the shark game): value NOT tied to progression; funny/silly/educational/cute/sweet; must not break the game's reality.
- Decided inclusions (Avery, at Ben's suggestion — real memories): **Thumper**, the tan-and-white rabbit with upright ears — visits the field edge now and then, thumps once, hops off; **Pookie**, the hamster — not live (would break reality), but a tiny framed drawing on the farmhouse windowsill, a memorial object; **Baby**, the dog — occasional farm visitor (sun-naps included); Avery can provide a photo for sprite creation when art time comes; **the cardinal** (Robert — Avery and Fiona's dad, Barbara's late son, well-loved around town) — perches on the fence post on quiet mornings, never explained; a family member may have a quiet line about him when it appears (mild — Avery, 2026-10-06).
- Riff pile (Avery wants these too): heart berry — pressing would squash it (it's not a flower), and a fresh one would rot, so this one's for eating: sweetest berry of the summer, a tiny private moment, then gone; Strawberry Moon flavor text in June; cloud shapes (strawberry, pig); festival crowd cameos — Barbara's family: Deborah & Gordon (the trio's parents), Donna, Siobhan, Kelly (Donna's daughters); June's family: Tammy & Michael (married; Tammy is June's youngest), Lynn, Tony, Wesley, Andrea (Andy) — brother Mark lives out of town, never seen; plus Ben (love interest, implied only — the crowd gossip does the work), Avery (lol). Sarah and Harley do NOT cameo — Fiona has never met them. (Two Marks — don't confuse them: the trio's Mark is Deborah's son; Tammy's brother Mark is the unseen one.) Buried childhood object: CUT 2026-10-06 (marble cut earlier — they never played with marbles; the whole idea cut — Avery couldn't find anything important/memorable enough); tap-the-pig trick (ten taps → dramatic flop); four-leaf clover in the keepsake box. The keepsake box (farmhouse shelf) is the quiet little museum holding the durable treasures — no reward attached.

## Prototype scope — v0.1 (DECIDED 2026-10-06)
- **In:** full tutorial (8 beats) → T1 open; T1 complete (Annapolis + Honeoye planting, raised planter boxes, all 4 starter recipes, all 3 appliances); day loop with overnight growth + one weather forecast/day; first-pass economy; nameable pig that eats failed bakes.
- **Endpoint:** completing T1 → "to be continued" beat that teases the bees (a bee drifts past, the beekeeper waves from the road) — v0.2's trailer.
- **Out:** T2+, festival/countdown, achievements, easter eggs, greenhouse, roadside stand; session-based for now (save/load deferred — flagged as an open question).
- **Launch-readiness:** tutorial completable end-to-end; all 4 recipes bakeable and sellable; numbers in; version number displayed (standing rule); placeholder art is fine (canon for now).

## Queued design topics
- Strawberry varieties: tier placement DECIDED 2026-10-06 (15 keeps across T1–T7). Maybes decided 2026-10-06 (Earliglow kept for tutorial; other six cut). Also decides whether soil/mulch/compost is a real mechanic or cut (no filler).
- Recipes & processing
- Act III festival-prep phase & the signature creation — DESIGNED 2026-10-06 (paper-chain countdown, 5-item checklist, 6-beat festival vignette; fraisier named as signature). Family cameo tree recorded 2026-10-06 (Barbara's + June's families).
- The pig (name? personality? idle animations?)
- Season structure & pacing: season/time/day-loop/tutorial decided 2026-10-06; first-pass numbers (costs, yields, prices, growth times) pending
- Educational layer (how the facts surface)

## Title candidates
- Berry Delightful (Avery's instinct — current placeholder)
- Strawberry Season
- The Berry Patch
- Sun-Ripened
- A Strawberry Summer
