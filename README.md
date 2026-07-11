# Mystery of Ancient Darkness - Open Prologue Demo

**A dependency-free cinematic prologue player for a narrative-first occult adventure.**

[Run the live demo](https://elyssov.github.io/MOAD-Demo/)

This repository is the public, open-source presentation layer for **Mystery of
Ancient Darkness (MOAD)**, a game in active development by Misfits Software.
It packages illustrated frames, dual-character voiceover, ambient sound, and
typewriter-style captions into a single browser experience with no build step
and no external runtime.

The main game is a 1930s occult adventure about Lord Eugene and Lady Alice
Compton, two parents who enter an ancient Egyptian horror to recover their
nine-year-old son. Its design principle is simple: mechanics should carry the
story. Magic changes Alice visibly; violence can destroy information as well as
enemies; wounds, fear, and preparation shape the expedition rather than merely
decorating a health bar.

## What is open here

- A self-contained HTML/CSS/JavaScript prologue player
- Keyboard-driven slide sequencing and typewriter captions
- Per-scene voiceover and layered ambient sound playback
- A local-first asset layout that works without a backend
- A compact testbed for narrative timing, accessibility, and localization

The current public build contains:

- 13 illustrated narrative frames
- 24 voice tracks
- 25 ambient and sound-effect tracks
- Two locally bundled display fonts

The unreleased Godot production repository remains private while commercial
assets and game systems are still changing. This repository is the public
open-source surface: a working demo, a reproducible narrative player, and the
place where reusable presentation tooling will be extracted and documented.

## Run locally

No package manager or build process is required.

1. Clone or download this repository.
2. Serve the directory with any static HTTP server.
3. Open `index.html` through that server.
4. Select **Start prologue**.

Controls:

- `Space` or `Enter`: advance
- `Esc`: end or close when the browser permits it

Audio starts only after user interaction, as required by modern browsers.

## Open-source roadmap

- Separate the presentation runtime from MOAD-specific scene data
- Publish a documented JSON scene format
- Add captions, reduced-motion support, and screen-reader landmarks
- Add English/Russian localization switching
- Improve mobile and touch controls
- Add automated checks for missing media and broken scene references
- Package the player as a reusable template for narrative prototypes
- Publish a playable vertical slice from the game when production permits

## Misfits Software

Misfits Software is a small, unfunded, distributed garage collective built
around an unusual production model: strong human authorship and direction,
specialized AI collaborators, and open tooling wherever it can be separated
from unreleased commercial assets.

Eugene Lyssovsky is the project's creator, narrative designer, systems
designer, and creative director. The wider project combines more than 25 years
of tabletop game-mastering experience with AI-assisted research, writing,
prototyping, visual development, and code review.

Project overview: [lyssovsky.com/moad.html](https://lyssovsky.com/moad.html)

## Contributing

Issues and pull requests are welcome, especially around accessibility,
localization, browser compatibility, audio behavior, performance, and turning
the player into a reusable open-source narrative tool.

Please keep changes focused on the public player and its documentation. Do not
add third-party media unless its license and attribution are clear.

## License

The source code and documentation are released under the [MIT License](LICENSE).

Story text, characters, original artwork, voice tracks, and sound assets are
not included in the MIT grant; see [ASSET_LICENSE.md](ASSET_LICENSE.md).
Bundled third-party fonts remain under their original licenses.
