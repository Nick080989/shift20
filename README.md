# SHIFT/20

**One key. Two worlds. Twenty seconds.** A one-button arcade game made for **GitHub Game Off 2026** (theme: *SHIFT*) and the **20 Second Game Jam 2026**.

▶ Play in your browser: https://nick080989.itch.io/shift20

## How to play
You exist in two overlapping worlds. Walls in your current world are solid; walls in the other world are just outlines you pass through. Press **Shift** (or Space, or tap) to swap worlds. Coins only count in their own world, so chain them for combo multipliers up to x8. The run lasts exactly 20 seconds and obstacles arrive on the beat of the music.

## Theme interpretation
"Shift" three ways: the **Shift key** is the only control, you **shift between two worlds**, and the colour palette **shifts** (light/dark inversion) every time you do.

## Tech
- A single `index.html`: plain JavaScript + Canvas 2D, no engine and no build step.
- Web Audio for sound effects and a looping music track.
- Obstacles are spawned on beats (156 BPM) so the game plays like a one-button rhythm game.

## Credits
- Sound effects: [Pocket Arcade SFX](https://nick080989.itch.io/pocket-arcade-sfx). Music: "Night Chase" from [Pocket Arcade Music](https://nick080989.itch.io/pocket-arcade-music). Both were synthesized procedurally in code by the author.
- AI disclosure: the game was designed and programmed with Claude, an AI coding assistant. Graphics are drawn by code at runtime. No image or audio generation models were used.

## License
Code: MIT. The audio files in `audio/` are included so the game runs, and are licensed for use in this game only (they are part of the commercial packs linked above).
