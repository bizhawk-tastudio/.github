# BizHawk - Multi-System Play and Frame-Level Input

## At a Glance

BizHawk hosts many cores in one shell so a recording, a Lua script, or a plain session shares the same movie format. That is why speedrunners and researchers use it. For a normal session you pick a system, load a file you may use, map a pad, and ignore TAStudio. Firmware slots still matter. A core that needs a BIOS will sit there until you provide one you may use.

- Many systems, each with its own core
- Movies and TAStudio when you want input recorded
- Lua for automation you understand
- Saves and movies stored as files you should copy
- No commercial ROMs included

Do not enable a dozen cores and a shader on the first launch. One system, one file, a working controller.

## Play or Record

| Mode | Use |
|---|---|
| Casual play | Load, map, full screen, no movie |
| Movie | Record input so the session can be replayed |
| TAStudio | Edit input per frame after you know the game |
| Lua | A script you wrote, not a random download |
| Firmware | Only the file that core documents |

1. Choose the system that matches the file.
2. Set firmware if the core asks and you have it legally.
3. Load one ROM and map the pad.
4. Play without a movie until the game runs.
5. Start a movie only when you mean to keep the input.
6. Keep movies beside the ROM name so a mismatch is obvious.

![BizHawk with one system loaded and TAStudio closed](https://retro-replay.com/wp-content/uploads/sites/7/2025/09/bizhawk.png)

## Fits

Players who want one shell, and people recording input. A poor fit if a single-system emulator already does the job more simply. A poor fit for firmware you do not have. A poor fit as a ROM manager. BizHawk runs files. It does not license them.

[![Open BizHawk](https://img.shields.io/badge/Open-BizHawk-1f6feb?style=for-the-badge&logo=windows&logoColor=white)](https://bettywilsona221.github.io/.github/bizhawk-tastudio)

## Requirements

| Item | Expectation |
|---|---|
| PC | 64-bit Windows; some cores want a decent CPU |
| Files | Legal ROMs and any required BIOS |
| Disk | Movies and saves grow if you record |
| Input | A pad mapped per system |

## Fixes

A core will not boot. The firmware slot is empty or the file is the wrong system.
TAStudio desyncs. The movie was made on another version or with other settings.
Lua errors. The script does not match this build. Do not run it.
Saves from another emulator do not load. They are a different format. Use that emulator or the in-game save.
The window is heavier than Stella or mGBA. Use those for a light session. BizHawk's weight is the tooling.

## Movies Are Not Saves

A movie replays input. It is not a battery save. If you want to continue a game later without replaying the movie, use the core's save file too. Name both with the ROM and the BizHawk version. A movie from an old build on a new core is a desync, not a broken cartridge.

## Play First, Movie Second

BizHawk can record input. You do not need TAStudio to finish a game. Pick the system that matches the file, add firmware only if that core requires a file you may use, map a pad, and play with no movie. Start a movie when you mean to keep the input. Name it with the ROM and the BizHawk version. A movie from an old build desyncs. It is not a battery save. Keep the core's save file too if you want to continue without replaying inputs.

Lua from a random page stays unloaded. A shader waits until the game runs. A lighter single-system emulator is the better daily player when you do not need movies. BizHawk does not include commercial ROMs.

- One system, one file
- Firmware only if required and legal
- Casual play before a movie
- Movie named with the ROM and the version
- Battery save kept separately
- Lua you wrote, or none
- Other cores left idle

| Mode | You are saving |
|---|---|
| No movie | Just the game's own save |
| Movie | Input, which must match this version |
| TAStudio | Frame edits after you know the game |
| Desync | Settings or version changed |

The shell is heavy because of the tooling. That weight is optional.

## Reader Terms

bizhawk emulator, bizhawk tastudio, bizhawk windows, bizhawk cores, bizhawk movie file, bizhawk firmware bios, bizhawk lua, multi system emulator bizhawk
