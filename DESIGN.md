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
- **The Festival Committee's Readiness List** (DECIDED 2026-10-06; shown in-game from Act II): 1) Starvale fully restored (complete the T7 tree); 2) roadside stand open and serving; 3) a signature festival creation baked (T7 showcase recipe — Pineberry + Gariguette come to the festival; the "Berry Famous" moment). All three met → formal invitation → **14-day countdown** → festival day as a short playable vignette (walk the fair, present the creation, spot the cameos) → free play continues after. Structural milestones only, nothing grindy. (Option A DECIDED 2026-10-06: T7 completes Act II — the festival waits for the full tree rather than triggering at T6.)
- **Nudge** (DECIDED 2026-10-06): if ~day 50 arrives with the list incomplete, the committee's letter arrives warmly noting what's missing — diegetic, no fail state.
- Day loop (proposed): one free action phase per day (tend, harvest, bake, sell, buy upgrades), closed by End day; plants grow overnight. New plantings take ~3–4 days to first fruit; June-bearers produce heavily in ~8-day windows; everbearers trickle all season; greenhouse enables out-of-season growing. One simple weather forecast per day (sun/rain/heat) — cultivar personalities live here. Rain auto-waters all beds (DECIDED 2026-10-06 — the forecast is worth reading). Watering is one tap per bed; irrigation (T3) auto-waters.

## Day loop & tutorial (DECIDED 2026-10-06)
- Each day = one free action phase: water beds (one tap per bed), plant, harvest, bake, sell, shop upgrades — then End day. Overnight, plants grow and tomorrow's weather rolls in.
- Buying "more plants" plants them directly — no seed inventory to manage.
- Neglect slows growth/yield, never kills. No fail states in the tending.
- Tutorial beats: 1) inherit Starvale, name the pig; 2) clear and tidy the old Earliglow patch (tap-to-tend); 3) water it; 4) harvest the first berries — small, past-prime Earliglows, quietly showing why new varieties matter; 5) sell → first coins; 6) bake the first recipe; 7) buy more plants (Annapolis) → the farm visibly grows; 8) done — farm operational, loop learned, tier 1 open.

## Design pillars
- **Cozy and finite.** A real ending, not endless escalation.
- **The farm is the progress bar.** Every upgrade is visible: fuller greener plants, larger redder berries, neater paths, repaired fences, flowers, bees, then the greenhouse, market setup, decorations, festival bunting. Progress should be obvious just by looking.
- **Real strawberries.** Real varieties with meaningful differences: flavour, colour, harvest season, yield, climate preferences, ideal uses.
- **Baking matters.** Jam, preserves, cakes, tarts, drinks. Recipes default to gluten-free wherever possible — not a separate version, just how they're written. Every food unlocks its real-world recipe after the win.
- **Light learning.** Real cultivation, pollinator, ecology, and food facts — a dusting, never homework.
- **The pig.** A big, well-socialized barnyard pig — not a little potbelly, a proper big ol' pig who just happens to be extremely friendly — named by the player, economically useless, delightful. Wanders the farm, sleeps in straw, investigates baskets, gets muddy, appears in inconvenient places, provides personality. Failed bakes go to the pig, who considers this an excellent outcome — and by design, nothing the kitchen can produce would ever disagree with him. (Wording kept in game abstraction per ChatGPT's review 2026-10-06.)
- **The festival is the win.** The season builds to the town's annual Strawberry Festival: the restored farm opens to visitors and the player presents a signature strawberry creation using everything learned. The farm stays playable afterward.
- **A gift, not a job.** Passive systems should feel like the farm giving you something, never like another obligation — "a jar that fills every few days is a gift; a jar you must tend is a job." (From Milo via ChatGPT, adopted 2026-10-06 — use as a design test for every ambient system.)

## Setting
**Starvale Farm** — a fictionalized echo of Stardale Farm, the real strawberry farm near Avery and Fiona's childhood home where they used to pick strawberries together.

## Art direction
Warm, dreamy, cheerful, deliberately cute — without becoming childish or saccharine. The goal: a game Fiona could have loved opening in 2008–2012, still attractive and coherent now. Touchstones: early-2000s/early-2010s browser games, Cooking Mama, old Disney kitchen CD-ROM games, Strawberry Shortcake-type sweetness.

The world is rooted in an **early-2000s Eastern Ontario / Ottawa Valley farm community** — not generic cottagecore or anonymous farm-sim countryside. Landscape language: red or weathered barns, silos, Holstein cows in nearby fields, round hay bales, tree lines and open farmland, gravel drives, roadside produce-stand energy, handmade/painted farm signs, practical sheds, strawberry rows with straw mulch, wildflowers, clover, bees and pollinator gardens, big soft white summer clouds, warm July sunlight, local-community feeling over polished agritourism. All stylized through a soft childhood-memory lens — rounded charming cows, oversized pillowy clouds, storybook barns, warm golden hay-bale shapes. Slightly idealized, the way remembered summer places are.

**Colour language:** strawberry pink, berry red, cream, soft leaf greens, sky blue, warm wood, small touches of butter yellow. Pink prominent without making every object pink; surrounding greens keep the sweetness grounded.

**UI and objects:** soft, friendly, handmade, slightly nostalgic — rounded panels and buttons, scalloped or softly decorative labels, selective gingham, strawberry blossom and seed motifs, hand-painted sign energy, jam-jar labels, baskets, recipe cards, wooden counters, genuinely delicious-looking food, light sparkle/glow for ripe fruit, discoveries, upgrades. Avoid: ultra-clean modern minimalist UI, industrial farming imagery, exaggerated cottagecore fantasy, sterile mobile-game polish, anything globally generic.

**Visual progression (the farm is the progress bar):** early Starvale has duller/patchier plants, smaller paler fruit, uneven beds, tired fencing, sparse flowers, worn signs. As the player improves soil, water, cultivation, pollination, equipment: leaves fuller and greener, berries larger/deeper red/more abundant, more flowers and pollinators, neater paths, repaired fences and buildings, flower borders, accumulating baskets/signs/rain barrels/tools/market elements, eventually a greenhouse, late-game festival bunting. Early vs. late screenshots should read instantly as transformation through care.

**Cultivar unlock art (noted 2026-10-06, for art time):** when a new cultivar unlocks, show dedicated art depicting its berries' true colours — white Pineberry, pink Rosé, the deep reds — so each new colour lands as a reward. The colour reveal is part of the unlock.

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
- Roadside stand (NEW unlock at tier 3: the farm's first direct-sales structure — produce-stand energy straight from the visual identity; hand-painted sign, crates of berries. Does all three: better prices than default selling, passive sales ticking over while you bake, and the start of the festival pipeline. Opens Act II.)

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
- T2 recipes (DECIDED 2026-10-06): 1) **Jam Thumbprints** (mixer — cookie dough + T1 strawberry jam; recipes that eat other recipes, a production chain; simplest); 2) **Honey Strawberry Cake** (mixer — hive honey + Cavendish; the cross-column showcase; creaming method); 3) **Strawberry Custard Tart** (mixer — tart shell + vanilla custard + glazed Annapolis; the pretty one, most complex; foreshadows the festival signature creation). Relative value ~55/65/80 — each tier's simplest beats the last tier's best. Kent sits out fresh; its destiny is T3's frozen smoothies.

**Tier 3** — DECIDED 2026-10-06
- High-end blender (staggered from tier 2)
- New drinks recipes (require the high-end blender — hard requirement carries forward) + expanded preserves line (varietal jams — Jewel jam, Bounty jam as the benchmark — using the tier-1 big boiling pot; gated by tier/skill). Basic jam unlocked back at T1; T3 is where preserves get serious.
- The pot's own high-end moment deferred — let tiers breathe, don't overfill
- T3 recipes (DECIDED 2026-10-06): drinks — 1) **Sparkling Strawberry Lemonade** (Jewel + lemon; the flavour favourite's drink); 2) **Frozen Kent Smoothie** (frozen Kent + yogurt + hive honey; the three-tier chain paying off; "Brain Freeze" lives here); varietal jams — 3) **Jewel Jam**; 4) **Bounty Jam** (the benchmark; "Bounty Hunter" lives here). Relative value ~90/100/110/120. Whole tier naturally GF. Jewel is T3's flavour star across both lines, pairing with the new roadside stand.

**Tier 4** — DECIDED 2026-10-06
- Copper preserving pan (the pot's high-end moment; completes the equipment trilogy: mixer → blender → pan)
- Advanced preserves recipes (require the copper pan — hard requirement carries forward)

**Tier 5** — DECIDED 2026-10-06
- Bigger farmhouse oven — *bigger, not industrial* (industrial clashes with the game's anti-industrial visual identity)
- Advanced baking recipes, requiring the bigger oven (hard requirement carries forward; the next step up the baking line)

**Tier 6** — DECIDED 2026-10-06
- New greenhouse varieties (the greenhouse begins feeding the kitchen)
- New recipes using the new varieties (complexity curve continues)

**Tier 7** — DECIDED 2026-10-06
- Rare / out-of-season greenhouse varieties
- Showcase recipes built around them (complexity curve continues)

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

## Experimenting, failed bakes & sharing (DECIDED 2026-10-06)
- **Experimenting** (kitchen action, unlocks at T2): pick 2–3 things from your pantry — berry baskets, made goods (jam, compote), honey — and combine. Match a hidden recipe's inspiration combo → discover it free ("Happy Accident"); anything else → failed bake → pig. Ingredients are spent either way — that is the economy. No coin cost, no other limiter. (Full rules DECIDED 2026-10-06; answers ChatGPT's economy/boundary notes.)
- **Hidden recipes**: one per tier from T2 on; same-tier discovery only, using only what you own. Anything undiscovered auto-unlocks with the next tier's kitchen upgrade — no FOMO. Each shows a vague hint line on the experiment screen (Empire cookies' hint in Mom's voice). Known roster: Empire cookies (T2, via jam experimenting); the rest designed alongside their tiers.
- **"Your version" signature** (Ben's catch, adopted 2026-10-06): a recipe you discover keeps a permanent mark — the card records that it was found, not given, plus a small permanent quality/price edge. The auto-unlock backstop still hands out every recipe (no FOMO), but a found recipe is yours in a way a granted one isn't. Keepsake bonus, not a balance lever — it doesn't fight the pricing philosophy. Empire cookies are the first test case.
- **Failed bakes** come from two triggers: experimenting (the risk of the unknown) and baking with neglected berries. The pig is the gentle landing for both.
- **Empire cookies** (memorial recipe): Avery's mom made them for holidays — jam-filled sandwich cookies; discoverable via jam experimenting. Solarium memory recorded: in winter she'd keep them in the solarium instead of the freezer, when it was cold enough.
- **Sharing/gifting**: the player can give baked goods to named townsfolk — a small verb for the game's emotional core ("a love letter about sharing"). Mechanical weight TBD; light by design.
- **Freezer**: boring T1 unlock — the fridge's freezer compartment; a dedicated chest freezer comes as a later upgrade. No capacity minigames — functional, not fussy. (Kent's freezing needed a home; this is it.)

## The Freakberry & the Barbara Special (DECIDED 2026-10-06 — Avery's idea)
- **The freakberry**: each harvest day, a small chance any bed produces a mutant berry — huge, cockscomb-shaped (real phenomenon: fasciation, fused blossoms), flagged as special. Cabot beds slightly likelier, since king berries are already its thing. Sell it for a premium — or gift it.
- **Matthew, Dave & Mark**: a trio of brothers hanging around the farm/stand — Barbara's grandsons, Avery's real cousins (Barbara is Avery and Fiona's real grandma). They think giant strawberries are the coolest thing and would love to try one — the diegetic nudge, no UI hint needed.
- **The trade**: gift a freakberry to the brothers → they share their grandma's family recipe: **the Barbara Special** — an absolutely gorgeous latticework strawberry pie with egg-wash on top. A secret recipe outside the experimenting track; a deluxe upgrade of the standard pie.
- **Design requirement**: a basic Strawberry Pie recipe must exist no later than T2 (oven era) so the Special reads as an upgrade — not yet placed (T2 currently has 3 recipes; placement TBD).
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
- Rosé — pink-fruited (cf. Driscoll's Rosé); light pink berries, peachy/floral flavour, creamy texture. The delight pick — grown because it's pink. (Added 2026-10-06 for Fiona.)
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
- T7: Pineberry + Rosé + Gariguette — the jewel box: white wonder, pink delight, French diva; festival material

## Achievements (brainstorm — 2026-10-06, nothing decided)
Principle (carried from the shark game): no grind counters — celebrate moments, discovery, craft, the pig. Fiona shares Avery's sense of humour, so funny ones are explicitly wanted.
- Firsts: "The Old Patch" (first harvest, from the Earliglow tutorial patch), first bake, first stand sale
- Cultivar stories: grow all 15; "The Breeder" (Mara → Charlotte); "White Wonder" (first white Pineberry); "Pretty in Pink" (first pink Rosé harvest); "Matchmaker" (Yamaska pollinated); "The Hollow King" (hollow Cabot king berry); "NePo Baby" (first Charlotte)
- Craft: "Brain Freeze" (first smoothie from frozen Kents); first gluten-free bake; complete a recipe family; "Bounty Hunter" (jam from Bounty berries); "Honey Money" (sell first honey jar)
- Pig: name the pig; "Quality Control" (pig eats a failed bake); "Basket Case" (pig asleep in a basket); "That'll Do, Pig" (Avery's — the pig tastes a number of *different* failed recipes; the pig as critic — variety, not grind); "Pig Out" (three different failed bakes in a single day)
- Festival: "Berry Famous" (present the signature creation)
- Weather & mishap: "Hot Mess" (harvest Honeoye in a heatwave); "Fun Size" (the tutorial's shriveled Earliglows)
- Sharing: "Good Neighbour" (Avery's — give food away; the sharing verb's moment)
- Roman's pitches (2026-10-06 — kept per Avery): "Happy Accident" (first recipe discovered by experimenting); "Like Mom Made" (discover Empire cookies); "Underfoot" (the pig gets underfoot in the kitchen); "Chill Out" (freeze your first berries); "Under Glass" (first greenhouse harvest); "You're Invited" (the festival countdown triggers); "Crown Jewel" (Jewel jam + Jewel lemonade); "Preservation Society" (all three jams canned); "Comeback Kid" (a neglected bed bounces all the way back — HIDDEN per ChatGPT's review 2026-10-06; achievements shape behaviour, and neglect must never feel like an optimal checklist action in a game about care); "Storm Baker" (bake in a thunderstorm); "Blue Ribbon" (BANKED for the festival pass per ChatGPT's review 2026-10-06 — "win a festival category" would smuggle in an undesigned judging system; revisit when the festival itself is designed)

## Easter eggs (2026-10-06 — inclusions decided, forms in discussion)
Rule (from the shark game): value NOT tied to progression; funny/silly/educational/cute/sweet; must not break the game's reality.
- Decided inclusions (Avery, at Ben's suggestion — real memories): **Thumper**, the tan-and-white rabbit with upright ears — visits the field edge now and then, thumps once, hops off; **Pookie**, the hamster — not live (would break reality), but a tiny framed drawing on the farmhouse windowsill, a memorial object; **Baby**, the dog — occasional farm visitor (sun-naps included); Avery can provide a photo for sprite creation when art time comes; **the cardinal** (dad) — perches on the fence post on quiet mornings, never explained.
- Riff pile (Avery wants these too): heart berry — pressing would squash it (it's not a flower), and a fresh one would rot, so this one's for eating: sweetest berry of the summer, a tiny private moment, then gone; Strawberry Moon flavor text in June; cloud shapes (strawberry, pig); festival crowd cameos — Tammy and Michael (married couple), June, Barbara (Avery and Fiona's real grandma — "classic grandma"), Ben (love interest, implied only — kept 2026-10-06; the crowd gossip does the work), Avery (lol); plus Sarah and Harley; childhood object buried in the old Earliglow patch (was: a marble — cut, they never played with marbles; awaiting what's true to them); tap-the-pig trick (ten taps → dramatic flop); four-leaf clover in the keepsake box. The keepsake box (farmhouse shelf) is the quiet little museum holding the durable treasures — no reward attached.

## Prototype scope — v0.1 (DECIDED 2026-10-06)
- **In:** full tutorial (8 beats) → T1 open; T1 complete (Annapolis + Honeoye planting, raised planter boxes, all 4 starter recipes, all 3 appliances); day loop with overnight growth + one weather forecast/day; first-pass economy; nameable pig that eats failed bakes.
- **Endpoint:** completing T1 → "to be continued" beat that teases the bees (a bee drifts past, the beekeeper waves from the road) — v0.2's trailer.
- **Out:** T2+, festival/countdown, achievements, easter eggs, greenhouse, roadside stand; session-based for now (save/load deferred — flagged as an open question).
- **Launch-readiness:** tutorial completable end-to-end; all 4 recipes bakeable and sellable; numbers in; version number displayed (standing rule); placeholder art is fine (canon for now).

## Queued design topics
- Strawberry varieties: tier placement DECIDED 2026-10-06 (15 keeps across T1–T7). Maybes decided 2026-10-06 (Earliglow kept for tutorial; other six cut). Also decides whether soil/mulch/compost is a real mechanic or cut (no filler).
- Recipes & processing
- Act III festival-prep phase & the signature creation (finite checklist design)
- The pig (name? personality? idle animations?)
- Season structure & pacing: season/time/day-loop/tutorial decided 2026-10-06; first-pass numbers (costs, yields, prices, growth times) pending
- Educational layer (how the facts surface)

## Title candidates
- Berry Delightful (Avery's instinct — current placeholder)
- Strawberry Season
- The Berry Patch
- Sun-Ripened
- A Strawberry Summer
