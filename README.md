# FakeGames

Console menu for Windows that makes Discord show a chosen game as running,
without installing it. It uses Discord's own game detection: a small window is
started under the game's exe name, so Discord sees a running process.

## Features
- 10 games out of the box + add any supported game by name
- Toggle games on/off manually, stop all, cleanup on exit
- No game files, no installs, no Python required

## How to use
1. Download FakeGames.exe from Releases.
2. Run it, pick a game by number; the same number turns it off.
3. Keep the console open while the window is running.

## Notes
- Windows 10/11 only. SmartScreen/AV may warn (unsigned PyInstaller build).
- Unofficial tool, gray area of Discord rules. Use at your own risk.
- Don't run a fake game while the real one is open: stopping works by exe name.
- Only network request: the public Discord game list.

## Important Warnings

* **Quest Danger:** Spoofing Discord Quests can get you banned or lose rewards. Check the Quests tab and don't fake active games. Use at your own risk!
* **100% Privacy:** No logins, tokens, registry tweaks, or data tracking. 
* **Source Code:** Closed for now. It's an unsigned .exe from a random dude — if you don't trust it, don't run it.
