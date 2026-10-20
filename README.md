# Level Devil

A pixel-art trap platformer in a single HTML file. Ten levels, each with its own traps, enemies and mood, ending in a boss fight. Nothing here is fair, and that's the point.

## Play

Open `level-devil.html` in any modern browser. There's no install, no server and no extra files. All the music and sound effects are generated live in the browser.

## Controls

| Key | Action |
|---|---|
| Arrow keys / WASD | Move |
| Space | Jump |
| K | Throw katana |
| R | Restart level |
| M | Mute / unmute |

Touch controls are also supported.

## The 10 Levels

1. Spikes
2. Roof-fall barriers
3. Saws
4. Portals with a huge gap
5. Thrown katanas
6. Rolling boulder
7. Spiked ceiling, falling rocks and saws
8. Three chasing enemies. Kill each with 5 katanas thrown in the direction you're facing.
9. The hardest level
10. Boss fight across 4 platform layers

## Features

- Every level has its own traps, enemies and look
- Procedural soundtrack, one seamless 16-bar loop per level. The music adds layers as you get further, and speeds up during boulder chases and boss rage
- Sound effects for every action, including blood and slash sounds on death
- Death effect: flash, shockwave rings, two crossing katana slashes, then an iris-wipe respawn
- Blood stains stay on the floor within a level

## Tech

- HTML5 canvas, 320x180 logical resolution, pixel-perfect scaling
- Vanilla JavaScript with zero dependencies
- Web Audio API: music is pre-rendered with `OfflineAudioContext` into layered stems, and a live sequencer plays until each loop is ready

## Tips

- Die early and die often. Every trap teaches you something.
- Listen to the music. When the layers build up, you're doing well.

> "Fall seven times, stand up eight." (Japanese proverb)
