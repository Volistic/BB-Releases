# Badge & Build — downloads

Badge & Build is a 2D block sandbox (dig, build, explore, fight bosses) that started on a
conference badge and now runs on PC, with online multiplayer.

**➡ [Download the launcher from the latest release](../../releases)**

> Everything here is a **beta** for now. Expect bugs and changes.

## Playing

1. From the newest [release](../../releases), download **`BadgeBuild-windows.zip`**. That's
   the launcher, about 10 MB.
2. Unzip it anywhere and run `BadgeBuild.exe`. No install, no Python.
3. If Windows says "Windows protected your PC" (the program isn't signed), click
   **More info → Run anyway**.

You only download the launcher once:

- **Every version:** on the start screen, **Version** lists all the releases here. Pick one and
  the launcher downloads it (it's tiny) and plays it.
- **Updates:** when a newer launcher is out, the start screen says so. Press **U**, or pick
  "Update the launcher" on the Version page. It downloads, restarts, and keeps everything.
- **Joining friends:** if a friend's game is on another version, your game switches to it for
  that game, downloading it from here if needed.

Your worlds, name and settings are kept in `%APPDATA%\BadgeBuild`, never in the launcher's
folder, so updates and other versions never lose them. Older versions play on a copy of your
worlds.

## What's in each release

| File | For |
|---|---|
| `BadgeBuild-windows.zip` | The launcher. Players download this. |
| `game-<version>-<code>.zip` | That version's game code. The launcher downloads it for you. |
| `BadgeBuildServer-windows.zip` | A server: online play with no port forwarding, a dedicated world, plugins. Read `README.md` inside. |

## Problems

[Open an issue](../../issues). Note which version you're on and what happened. For
multiplayer issues, include `game.log` from `%APPDATA%\BadgeBuild`.
