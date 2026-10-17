# NBA Street Homecourt for PS5

**NBA Street Homecourt (Xbox 360) running natively on a jailbroken PS5**, at 1440p and a locked 60 fps.

The game is statically recompiled, not emulated: its Xbox 360 code is turned into a native PS5 program, with a hub made for the DualSense.

## What's in it
- 1440p at a locked 60 fps, with FXAA
- Two controller schemes: **Modern** (the default) plays like NBA 2K, with Square to shoot; **Classic** is the game's own layout
- PlayStation button prompts throughout the game, and a DualSense on the controls screens
- The game's achievements as trophies: a popup when you earn one, and your progress on the hub's Trophies page
- A hub to start the game, change settings, back up your saves and play your own menu music

## What you need
- A jailbroken PS5 that runs homebrew apps from `/data/homebrew/`
- Your **own** copy of NBA Street Homecourt for Xbox 360. No game files are included.

## Install
1. Download `PPSA93007.zip` from [Releases](https://github.com/elripalda/nbastreet-ps5/releases) and copy the `PPSA93007` folder to `/data/homebrew/` on your PS5.
2. Copy everything from your extracted disc into its `GameData` folder (you can leave out `$SystemUpdate`):

```
/data/homebrew/PPSA93007/GameData/default.xex
/data/homebrew/PPSA93007/GameData/SPLASH_16_9_en
/data/homebrew/PPSA93007/GameData/SPLASH_4_3_en
/data/homebrew/PPSA93007/GameData/TITLEIMAGE.PNG
/data/homebrew/PPSA93007/GameData/data/...
```

Launch it from your homebrew launcher. The hub opens first: press START GAME.

**Updating:** copy the new `PPSA93007` folder over the old one. Your `GameData` and `UserData` (saves, trophies) stay as they are.

## The hub
L1 / R1 change pages, the D-pad picks and changes settings, Circle goes back, OPTIONS starts the game. Settings save as you change them.

For menu music, put your own songs (.mp3, .ogg, .flac, .wav) in `/data/homebrew/PPSA93007/hub/music/`. R3 skips to the next one.

## Problems?
Open an issue with the newest file from `/data/homebrew/PPSA93007/logs/`. For a more detailed log, add the line `diagnostics = 1` to `ps5_settings.ini` in the app folder.

## Credits
Made by **[elripalda](https://github.com/elripalda)**: the recompilation, the PS5 port, the hub, the PlayStation buttons, the controller schemes and the trophies.

Built with the [ReXGlue](https://github.com/rexglue/rexglue-sdk) recompiler.

*An unofficial fan project, not affiliated with or endorsed by EA, the NBA, Microsoft or Sony. No game files are included.*
