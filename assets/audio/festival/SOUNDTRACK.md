# Starvale Strawberry Festival — approved soundtrack 🎻🍓

**Status:** Avery approved Mix 6 and the seamless repeat transition on October 17, 2026. **Do not remix or replace** without asking Avery.

**Asset:** `starvale-festival-loop.m4a` (AAC, stereo, exactly 360 seconds, 8,709,815 bytes).

- SHA-256: `bea29458a6ee8cea70ce6f5c37572f414f3a6ab9e2bfb63910a7352ccb6022f8`
- Git blob SHA: `9051b013a4e623b2788aa53c304759eec909300f`
- This is the **approved** six-minute loop-ready M4A, not a newly encoded substitute. Match the SHA-256 before using.
- Source audio was mixed with distant Galway traditional music, soft crowd conversations (no added footsteps), and naturally distant applause.
- Applause tapers off into ~6 seconds of crowd ambience, then the music comes back on the next loop. The current seamless-boundary audition is approved; test repeat playback on iPad Safari.
- Begin playback on a user gesture and expose music/audio controls. Prefer Web Audio `AudioBufferSourceNode.loop` if native AAC element looping introduces a small gap. Don't autoplay unexpectedly.
- This audio is for **the Strawberry Festival**, not the regular farm scenes.

## Source recordings and credit

1. **Galway Session**, recorded by **Gaillimhcommon** (August 31, 2009), Wikimedia Commons: https://commons.wikimedia.org/wiki/File:GalwaySession1.ogg — identified on Commons as **CC BY-SA 3.0**. License: https://creativecommons.org/licenses/by-sa/3.0/
2. **Outdoor Garden Party**, **Bansemer**, Freesound: https://freesound.org/people/Bansemer/sounds/686975/ — marked **CC0** at source.
3. **Applause i**, **Thore**, Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Applause_i.ogg — marked **public domain** at source.

**Changes to source recordings:** Adjusted music tonal balance/level to suggest musicians at a distance, layered an outdoor social crowd at a lower level, augmented the applause and gently filtered/mixed it to match distance, created a 360-second repeating ambient music bed. An adaptation of Galway's CC BY-SA material must carry appropriate credits, a description of modifications, and a compatible ShareAlike license for the adapted audio.

**Rights warning:** The Galway Commons upload identifies the recorder but not the performers. Their rights/permission have *not* been independently established. **Do not treat this soundtrack as cleared for public-game distribution until that question has been resolved.** The repository is public, so the branch/PR itself is also publicly visible.

## Asset staging

The GitHub upload path for large binary files required temporary `assets/audio/festival/.parts/part-000` through `part-011` binary pieces. A one-time GitHub Actions job concatenates them in filename order, validates SHA-256, removes the temporary pieces, and commits the exact resulting M4A. Never ship the separate part files.

**This PR is asset preservation only.** No gameplay code, no festival trigger, and no merge/closure of the permanent design-room PRs.
