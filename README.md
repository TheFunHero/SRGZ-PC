# Sonic Riders: Zero Gravity – PC Port

A native Windows port of **Sonic Riders: Zero Gravity** (Wii), made by static recompilation. The game's own code was translated to run directly on PC, so it isn't an emulator.

<!-- Trailer: replace the link below with your YouTube video -->
**▶ [Watch the trailer](https://www.youtube.com/)**  ·  **⬇ [Download the latest release](https://github.com/TheFunHero/SRGZ-PC/releases/latest)**

> [!IMPORTANT]
> **This port does not include the game.** There are no graphics, music, sound or text from Sonic Riders: Zero Gravity in the download.
> You need your own copy of the Wii version, and the port reads everything from it.

---

## Features

- **Sharper picture:** internal resolution from 1x to 6x (up to 3840×2880), 16:9 widescreen, fullscreen or a borderless window, VSync and an FPS counter
- **Online races for 2 to 4 players** with room codes. The launcher sets up your router through UPnP when it can, and players on your home network show up by themselves.
- **Controllers just work:** Xbox, PlayStation, Switch Pro and most others, with button prompts in the GameCube, PlayStation or Xbox style
- **Bring your progress with you:** import saves from Dolphin, a `0_Games.sav` file or a real Wii (through Dolphin), and copy your progress back to Dolphin whenever you like
- **Riders Classic Style:** a built-in gameplay mod (see below)
- **Sonic Riders: Regravitified:** play the ROM hack, set up from your own patched disc
- **File mods:** each mod goes in its own folder, and you set the load order in the launcher
- **Hide the race HUD** (F4) for clean footage, in races and in replays
- **Check for updates:** the launcher tells you when a new version is out
- Takes the game's own icon from your copy of the game

## What you need

| | |
|---|---|
| **PC** | 64-bit Windows and a graphics card with OpenGL 3.3 |
| **Game** | Your own **North American** Wii disc of Sonic Riders: Zero Gravity (game ID **RS9E8P**), dumped to a disc image: `.iso`, `.rvz`, `.wbfs`, `.wia`, `.ciso` or `.gcz` |
| **Dolphin** | A recent version of [Dolphin](https://dolphin-emu.org/) that comes with `DolphinTool.exe`. The port uses it to unpack your disc and your Wii saves. |
| **Space** | About 4 GB, plus about 8.5 GB more if you add Regravitified |

> Other regions and the PlayStation 2 version **won't work**. The launcher checks your disc and tells you if it's the wrong one.

## How to install

1. Download **`SRZG-PC.zip`** from the [latest release](https://github.com/TheFunHero/SRGZ-PC/releases/latest) and unzip it anywhere, for example `C:\Games\SRZG`.
2. Start **`port\bin\srgz.exe`**.
3. Select **SET UP** and pick your disc image. If the launcher asks, show it where `Dolphin.exe` is.
4. Wait a few minutes while your disc is unpacked. When it says **All set!**, press **PLAY**.

The full guide, covering controls, online play, saves and mods, is in `port\README - How to play.txt`. You can also open it from the launcher.

**Updating:** unzip the new version over the old one. Your game files, saves and settings aren't in the download, so they stay.

## Gameplay mods

**Riders Classic Style**
Restores the racers' natural type abilities, so you can use any gear you want and your rider keeps their type (Speed grinds, Fly takes air rings, Power breaks obstacles). Boost with LB/LT to attack rivals, use shortcuts or just speed things up. Also adds charge jumps. It works with just your game, and the music, menus and opponents stay vanilla.

**Sonic Riders: Regravitified**
Plays the Regravitified ROM hack with its changes and new music. It runs Regravitified's own code from your patched copy of the hack, so none of it is built into the port. Set it up from your patched disc image on the Gameplay Mods page.

With both mods off, you get the game exactly as it plays on the Wii.

## Online play

One player hosts from the **Online** page and sends the room code to the others, who join with it. Everyone needs:
- the same version of the port
- the same game files
- the same mods

If the lobby says your router couldn't be set up automatically, see the "ONLINE PLAY" part of the guide.

## Known issues

- Windows SmartScreen or your antivirus may warn about `srgz.exe` because the file isn't signed. Choose **More info → Run anyway**.
- Windows Firewall may ask about `srgz.exe` the first time you play online. Choose **Allow**.

## Reporting a problem

Please [open an issue](https://github.com/TheFunHero/SRGZ-PC/issues) and include:
- what you were doing when it happened
- your `port\log.txt`. It's overwritten every time you start the game, so copy it first.
- for online problems: the `log.txt` of **every** player
- your PC's processor and graphics card

## Credits

- The Xbox button icons are by [VictorPines](https://commons.wikimedia.org/wiki/User:VictorPines), from Wikimedia Commons, under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). See `port\CREDITS.txt`.
- Sonic Riders: Regravitified belongs to its own creators. The port only runs it from your own patched copy.

## Legal

Sonic Riders: Zero Gravity is © SEGA. This is an unofficial fan project, and it isn't affiliated with or endorsed by SEGA, Nintendo, Sony or Microsoft. No game files are included. Please only use a copy of the game you own.
