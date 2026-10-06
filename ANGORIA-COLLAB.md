# Helping with Angoria — a guide for Avery (and your Muse)

Hey! Ben asked me (Milo, his Muse) to write up how you two can plug into Angoria. This is meant to be readable by humans and AI assistants alike, so it's structured accordingly.

---

## What Angoria is

A 2D isometric browser MMORPG, Dofus Touch-inspired in structure but 100% original IP. Turn-based tactical combat (6 AP / 3 MP, elemental spells, line of sight, push/pull), 10 original classes, 8 regions, dungeons with multi-phase bosses, questlines, professions, and a full in-browser map creation tool.

- **Repo:** `BenSlak/Angoria` (private — you're a collaborator now)
- **Stack:** Node.js + WebSockets server, vanilla JS + Canvas 2D client
- **Live (currently down):** https://angoria-lfnu.onrender.com/ — we're migrating off Render to a VPS

---

## Getting oriented

Start here, in this order:

1. **`README.md`** (repo root) — game description, mechanics, tech, asset breakdown, dev log
2. **`docs/design.md`** — full game design doc (classes, spells, systems)
3. **`docs/STYLE-BIBLE.md`** — art direction ("Painterly Tactical" v1.0)
4. **`docs/MAPTOOL.md`** — map tool spec
5. **`docs/PAINTED-MAP-FORMAT.md`** — map JSON format

Run it locally:
```bash
cd server && npm install
ALLOW_TEST_RESET=1 node server.js
# → http://localhost:8081
```

---

## Current state (2026-10-06)

**Done:**
- Game server: combat engine, 10 classes, monsters + AI, dungeons, quests, world graph, ~13,800 lines
- Client: isometric renderer, combat UI, character creation, paper-doll equipment system, ~9,700 lines
- Map tool: rebuilt Oct 3 (new UI, 10-layer system, categorized asset browser)
- **85,000+ assets** across 40 cultural styles (being pushed to GitHub in batches right now)

**In progress / stuck:**
- **Map editor viewport bug** — the 26×18 isometric grid should fill the editor viewport edge-to-edge (COVER, not contain). The bounds math is fixed and deployed, but the visual still shows black bands. Debug logging is in place. This is the top open bug.
- **Hosting migration** — Render is unreliable (slow deploys, ephemeral disk, currently offline). Plan is Oracle Cloud free tier VPS (2 OCPUs, 12 GB RAM, 200 GB). Setup guide not yet written.
- **40-style push** — 37 commits of new assets pushing to GitHub in batches; may need monitoring.

**Open backlog:**
- 6 monster animation sets need final death/run sheets
- World map (M key) has a WebSocket bug — server sends maps, client doesn't store them
- Durable map persistence (currently ephemeral on Render)
- `DELETE /api/world/cell` route needs replacing with non-destructive archive

---

## How you can help

**For Avery (human):**
- **Playtest** the game and map tool once the VPS is up — fresh eyes on UX and bugs
- **Asset QC** — spot-check the 40 new style packs for visual defects (white backgrounds, broken transparency)
- **Design input** — the map editor UX, in particular, could use a designer's eye

**For Avery's Muse (AI):**
- **Map editor viewport bug** (`client/maptool/editor.html`, `fitMap()` + `mapBounds()`) — the debug logging I added prints `canvas=WxH, map=WxH, zw=, zh=` to the console on Fit. The math says COVER should work; the visual disagrees. Picking up this investigation would help a lot.
- **Code review** on the new map tool UI (`fcc6511`) — it's a large single-file app; fresh review welcome
- **Docs** — anything you find confusing in `docs/`, flag it or fix it

**Ground rules:**
- Ben's standing rule: **never delete anything** — add, don't erase. If something needs removal, ask first.
- The repo is private; don't share code or assets outside the collaborator circle
- Angoria is original IP — Dofus Touch is a structural reference only, never copy it

---

## Talking to each other

Ben's Muse (me) and Avery's Muse can coordinate through GitHub — PR comments, issues, or threads like this one. If you're picking up the viewport bug, drop a comment on this PR so we don't double up.

— Milo 🐺
