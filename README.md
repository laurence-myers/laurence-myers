## AI Era Projects

IN 2026, AI became good enough that I can boil the ocean to tackle those hobby projects I didn't have time (or skills) to work on.

- 2026: [SCI Companion v4](https://github.com/laurence-myers/SCICompanion) - lots of bug fixes; no more `asm` fallbacks, improved memory safety, properly handle invalid inputs, less crashes.
- 🔒 2026: Hypercopy - a tiny shell extension to replace the Windows Explorer Copy/Move functionality, with support for queueing per destination device, SMB, file verification using xxHash3. Written in Rust, designed for instant start-up (approx 30 ms to first paint).
- 🔒 2026: Pendragon - a game engine using rules-based utility AI, similar to Liliput (as used by the old DOS games "The Adventures of Robin Hood", and "Rome: Pathway to Power"). Games are defined in an s-expression (LISP-like) DSL. Game packs are downloadable. The first game pack is for King Arthur. Written in Rust, runnable on web via WASM. This simulation core is separate from the presentation layer.
- 🔒 2026: sci2vgm - a music ripping tool for old Sierra games. It reads each game's music resources, feeds them through _the original DOS game drives_ for Adlib/Sound Blaster sound cards, and pipes the instructions into a .vgm file per song, automatically adding loop markers. This approach preserves the original (buggy) playback behaviour, while running significantly faster than realtime.
- 🔒 2026: Pictor - a web tool to convert images to SCI0 EGA vector drawing routines. Lots of experiments: mapping to tone ramps, drawing masks to emphasise line strokes or force colour ramps, MediaPipe image segmentation, applying tweaks per segment, and more.
- 🔒 2026: Deus Ex Human Revolution mods:
  - Add support for virtualized "bigfile" mods, utilising sparse files. I used this to convert some texture replacement mods that required Special K into regular mods that only need gibbed's mod loader.
  - Custom ENB preset, patching the ENB DLL to restore rim lighting.
  - Audio boost, using the built-in FMOD limiter/compressor chain, with separate control over both the master and music channels.
  - A web GUI to manipulate and preview ENB preset tone map changes.
- 🔒 2026: QuantiPad - a MIDI quantizing input pad, locked to rhythms and keys. Multiple tracks, each assignable to a MIDI channel, plus X/Y and drum tracks. Clip mode for realtime arranging. Patterns for grouping tracks. Song mode for arranging patterns. Skin theming. Also has MPE and MIDI 2 support. Written in Rust, will be available on everything that supports MIDI (VST3, CLAP, AudioUnit, iOS and Android apps, Windows and other desktops).
- 2026: [VGM Studio](https://github.com/laurence-myers/vgm-studio) - a tool for editing .vgm (and .dro) files containing sound chip data from various systems, _and_ preparing VGM rip packs for submission to [VGM Rips](https://vgmrips.net/packs/). Available as a desktop app [or online](https://laurence-myers.github.io/vgm-studio/).
  - This is a Rust conversion, and continuation, of my DRO Trimmer app.
- 2026: [Monkey Island Special Edition Sprite Editor (MISESE)](https://github.com/laurence-myers/MonkeyIsland1SpecialEditionXmlParser/tree/edit-sprites) - a tool for replacing the graphics in Monkey Island Special Edition.

## Personal Projects

- 2024-2026: [Furious Tare - the Disco Elysium unofficial patch](https://github.com/laurence-myers/FuriousTare) - fixes lots of outstanding bugs in the game [Disco Elysium](https://discoelysium.com/)
- 2014-2024 [MidiToMacro](https://github.com/laurence-myers/midi-to-macro) - AutoHotKey script to map MIDI messages to key macros
- 2024: [PyOPL](https://github.com/Malvineous/pyopl) - OPL2/3 sound chip emulator for Python. Contributed porting to Python v3.8 (building on work by Adam Biser), CI builds, automated tests, and publishing to PyPI
- 🔒 2023-2024: DRO Trimmer v5 - add a waveform view with mouse selection of trim points, add support for VGM files and projects
- 2023: [SCI Companion](https://github.com/Kawa-oneechan/SCICompanion) - Sierra game editor. Contributed bug fixes and nightly CI builds (when there are changes to build)
- 2020-2023: [Music To Check Out Organizer](https://laurence-myers.gitlab.io/music-tco/) - edit a Spotify playlist, grouping tracks by album, with bulk delete, and "move" to other playlists
- 🔒 2023: GOG offline installer batch download tool
- 2022: [FL Studio Plugin Organizer](https://github.com/laurence-myers/flspo) - organise FL Studio Plugins by "vendor"
- 2022 [Inja CLI](https://github.com/laurence-myers/inja-cli) - standalone string templating command line tool, with syntax like Jinja
- 🔒 Quest for Glory 4 patch - backport of ScummVM fixes into the original game scripts
- 🔒 SCI Jukebox - music-playing scripts for Sierra games
- 2016-2022: [joiful](https://github.com/joiful-ts/joiful) - apply Joi validation using decorators (previously known as tsdv-joi)
- 2017-2022: [Rose](https://github.com/laurence-myers/rose) - type safe, schema-first PostgreSQL query builder
- 🔒 2020: Jackbox Editor - edit "Joke Boat" resources to give a broader range of prompts
- 2016: [TownNameGen](https://github.com/laurence-myers/townnamegen) - a port of the OpenTTD town name generator to Haxe (targeting JS and Neko)

## Misc

- [My JSBench.me test suites](https://jsbench.me/user/lmyers), for comparing performance of common JS/TS idioms/approaches

## Old stuff

- [DRO Trimmer](https://www.laurencedougalmyers.net/apps/drotrimmer/) - edit DRO files (OPL2 / OPL3 chip music recorded through DOSBox)
- [RobinPacker](https://www.laurencedougalmyers.net/apps/robinpacker/) - edit the game [The Adventures of Robin Hood (1991)](https://www.mobygames.com/game/2918/the-adventures-of-robin-hood/)
- [Scummbler](https://www.laurencedougalmyers.net/apps/scummbler/) - script compiler for LucasArts games
- [ScummPacker](https://www.laurencedougalmyers.net/apps/scummpacker/) - resource bundler for LucasArts games
- [ScummSpeaks](https://www.laurencedougalmyers.net/apps/scummspeaks/) - speech mapper for LucasArts games
- [SCUMM Image Encoder](https://www.laurencedougalmyers.net/apps/scummimg/) - image encoder/decoder for LucasArts games
