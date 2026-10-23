# EdRoid

Play PC games on your Android phone. Copy a game folder to the phone, add it in EdRoid, tap **Launch**.

<!-- download -->
### [⬇ Download EdRoid 0.7.2 (167 MB)](https://github.com/Ender909v1/EdRoid-releases/releases/download/v0.7.2/EdRoid-0.7.2.apk)
<!-- /download -->

Older versions and what changed: [all releases](https://github.com/Ender909v1/EdRoid-releases/releases)

## What it plays

| Game | How EdRoid runs it |
|---|---|
| RPG Maker MV / MZ, TyranoBuilder, HTML5 games | Built-in game player, full screen |
| Windows games (`.exe`): Unity, Unreal, GameMaker, Godot, Wolf RPG, visual novels… | Built-in Windows engine (based on Winlator) |
| Ren'Py, RPG Maker XP / VX / VX Ace | Opens the JoiPlay app (install it separately) |

Japanese, Chinese and Korean games work too: EdRoid sets the language and font by itself.

## What you need

- Android 8 or newer, on a 64-bit phone.
- For Windows games: about 2 GB free space. Phones with Snapdragon (Adreno graphics) run them best; others work, slower.

## Install

1. On your phone, tap the download link above.
2. Open the downloaded `EdRoid-….apk`.
3. If Android says it can't install apps from this source, tap **Settings**, allow it, then go back.
4. Tap **Install**.

**Updates:** when a new version is out, EdRoid asks **Update EdRoid?** as it opens. Tap **Update**: it downloads the new version and opens the installer. Your games, saves and settings stay.

## Add a game

1. Copy the whole game folder to your phone. The **Download** folder is best.
2. In EdRoid, open the menu (top right) › **Export game** › **Choose game folder**, and pick that folder. Allow access to files if asked.
3. Check the report, then tap **Export to Android**.
4. The game is now in **Library**. Tap **Launch**.

The first Windows game sets up the Windows engine. That takes 1–3 minutes and happens once.
If the game folder has several `.exe` files, EdRoid asks which one starts the game.

## Playing

**Touch, in Windows games**
- Tap: click there
- Drag: hold the click and move
- Hold: right click
- Two fingers: right click and scroll
- Back button: the game menu (keyboard, stretch window, touch mode, on-screen buttons, exit)

**On-screen buttons**
- Menu › **Controls**. Default is built in. Tap **+ New layout** to make your own (it starts like Default), then **Edit** it: drag buttons to move them, add buttons, change their key, shape or size. Tap **Equip** on the layout you want.
- Different buttons for one game: Library › **⋮** › **Controls**.
- The **⚙ gear** over a game: tap it to show or hide the buttons, drag it anywhere, long-press it for the game menu (Windows games) or to exit (web games).

**Library ⋮ menu**
- **Start file**: which `.exe` starts the game
- **Speed**: from Safe to Fastest, if a game crashes or runs slowly
- **Open saves folder** / **Open game folder**: look at, back up or replace saves
- **Add to home screen**: launch the game straight from your home screen

## Tips

- **The game closes when you switch apps:** in Android Settings › Apps › EdRoid › Battery, allow background activity. On OPPO / realme / OnePlus (ColorOS) it's called *Allow background activity*.
- **The game window is small or cut off:** choose 1280×720 in the game's own settings, or use the back-button menu › *Stretch game window*.
- **It's laggy:** close other apps, or try Library ⋮ › Speed.
- **The game closed by itself:** when you go back to EdRoid it shows what happened, with a **Copy** button. Paste that text when you ask for help in [Issues](https://github.com/Ender909v1/EdRoid-releases/issues).

## Third-party software

The Windows engine is based on [Winlator](https://github.com/brunodev85/winlator-app) (LGPL-2.1) and includes Wine (LGPL-2.1), Box64 (MIT), DXVK (zlib), VKD3D-Proton (LGPL-2.1) and Mesa Turnip (MIT). The source of EdRoid's modified engine is available on request in [Issues](https://github.com/Ender909v1/EdRoid-releases/issues).
