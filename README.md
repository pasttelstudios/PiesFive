<div align="center">

# PiesFive

**A console-style game launcher for PC, inspired by the PlayStation 5 interface.**
Organize your own game library and play it through the KytyPS5 and shadPS4 emulators, with an original interface built from scratch to make emulation feel like a console.

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![License](https://img.shields.io/badge/license-freeware-blue)
![Languages](https://img.shields.io/badge/languages-9-blue)
![Status](https://img.shields.io/badge/status-Active%20Development-brightgreen)

</div>

---

> [!IMPORTANT]
> PiesFive is not affiliated with Sony Interactive Entertainment or PlayStation. The project does
> not distribute games, emulator binaries or copyrighted system software; all game artwork shown
> in the app is read locally from your own files. Use only game files that you have obtained
> legally.

## What is PiesFive?

PiesFive is a free game launcher for Windows. It gives your PC a clean, controller-first interface in the style of a modern game console: a home screen with your games, user profiles, trophies, settings and a game library, all navigable with a gamepad or keyboard.

Under the hood, PiesFive does not emulate anything itself. It launches your games through **[KytyPS5](https://github.com/KytyPS5/KytyPS5)**, the open source PlayStation 5 emulator, and **[shadPS4](https://github.com/shadps4-emu/shadPS4)**, the open source PlayStation 4 emulator, and handles the tedious parts for you: installing and updating the emulators, picking the right one for each game, passing the right settings to it, and keeping every profile's saves and trophies organized.

## Features

- **Console-like home screen** — your games front and center, with recently played titles first.
- **PS5 and PS4 games in one library** — each game carries its platform badge, and PiesFive picks the right emulator for it automatically.
- **shadPS4 on demand** — the PS4 emulator is never downloaded on its own. It installs when you open your first PS4 game, or anytime from Settings, while your PS5 games keep using KytyPS5.
- **Multiple user profiles** — each profile has its own name, avatar, saves and trophies.
- **Safe profiles** — saves and trophies are tied to a numeric user ID, so renaming a profile never moves or deletes your progress.
- **Full emulator control from the UI** — resolution, fullscreen, V-Sync, HDR, upscaling, microphone selection, trophy notifications and more, for both emulators, without touching config files.
- **Automatic emulator updates** — PiesFive fetches KytyPS5 and shadPS4 from their official releases and keeps them up to date.
- **Emulator version manager** — stable, test and up to 30 custom builds per emulator, with one-click rollback, and recommended builds for each game.
- **Trophy viewer** — browse the trophies you have unlocked in each game, on PS5 and PS4.
- **Game library** — covers and artwork are read from your own game files, right on your PC.
- **Steam library** — your Steam games sit alongside your emulated library.
- **Storage** — see how much space each game takes, disk by disk.
- **Controller-first navigation** — designed to be used from the couch, gamepad in hand, with DualSense battery in the Control Center and a built-in controller tester for buttons, triggers and sticks.
- **Nine languages** — English, Spanish, Brazilian Portuguese, German, French, Polish, Simplified Chinese, Japanese and Russian, switchable instantly.
- **Developer options** — emulator console, Vulkan and shader validation and more, for testing and debugging the emulators.

## How it works

1. You add games you have dumped from **your own console and your own discs/downloads**.
2. PiesFive reads each game's own metadata and artwork from the game files themselves, and detects whether it is a PS4 or a PS5 game.
3. When you press Play, PiesFive starts the right emulator with your profile and settings applied. If it is your first PS4 game, shadPS4 installs itself first and the game opens as soon as it finishes.
4. The emulators store saves and trophies per user ID, and PiesFive shows them back to you in the interface.

## Screenshots

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/whos-playing.png" width="420" alt="Choose Who's Playing"/><br/>
      <strong>Choose Who's Playing</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/game-library.jpg" width="420" alt="Your Game Library"/><br/>
      <strong>Your Game Library</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/game-library-ps4.jpg" width="420" alt="PS4 Games in Your Library"/><br/>
      <strong>PS4 Games in Your Library</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/shadps4-install.jpg" width="420" alt="Getting ShadPS4 Ready"/><br/>
      <strong>Getting ShadPS4 Ready</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/quick-power-menu.jpg" width="420" alt="Quick Power Menu"/><br/>
      <strong>Quick Power Menu</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/trophy-collection.png" width="420" alt="Trophy Collection"/><br/>
      <strong>Trophy Collection</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/emulator-settings.png" width="420" alt="KytyPS5 Settings"/><br/>
      <strong>KytyPS5 Settings</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/shadps4-settings.png" width="420" alt="ShadPS4 Settings"/><br/>
      <strong>ShadPS4 Settings</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/emulator-version-manager.png" width="420" alt="Emulator Version Manager"/><br/>
      <strong>Emulator Version Manager</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/choose-language.png" width="420" alt="Choose Your Language"/><br/>
      <strong>Choose Your Language</strong>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <img src="docs/screenshots/about-piesfive.png" width="420" alt="About PiesFive"/><br/>
      <strong>About PiesFive</strong>
    </td>
  </tr>
</table>

<details>
<summary><strong>View more screenshots</strong></summary>
<br/>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/game-library-horizon.jpg" width="420" alt="Library: Horizon Forbidden West"/><br/>
      <strong>Library: Horizon Forbidden West</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/game-hub.jpg" width="420" alt="Game Hub"/><br/>
      <strong>Game Hub</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/control-center.jpg" width="420" alt="Control Center"/><br/>
      <strong>Control Center</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/controller-battery.jpg" width="420" alt="Accessories and Controller Battery"/><br/>
      <strong>Accessories and Controller Battery</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/add-game-ps4.png" width="420" alt="Add a PS4 Game"/><br/>
      <strong>Add a PS4 Game</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/shadps4-install-prompt.jpg" width="420" alt="This Is a PS4 Game"/><br/>
      <strong>This Is a PS4 Game</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/trophy-collection-ps4.png" width="420" alt="PS4 Trophy Collection"/><br/>
      <strong>PS4 Trophy Collection</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/shadps4-version-manager.png" width="420" alt="ShadPS4 Version Manager"/><br/>
      <strong>ShadPS4 Version Manager</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/patch-notes.png" width="420" alt="Patch Notes"/><br/>
      <strong>Patch Notes</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/store-coming-soon.png" width="420" alt="PiesFive Store (Coming Soon)"/><br/>
      <strong>PiesFive Store (Coming Soon)</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/settings-general.png" width="420" alt="General Settings"/><br/>
      <strong>General Settings</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/settings-controllers.png" width="420" alt="Controller Settings"/><br/>
      <strong>Controller Settings</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/controller-tester.png" width="420" alt="Controller Tester"/><br/>
      <strong>Controller Tester</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/storage.png" width="420" alt="Storage"/><br/>
      <strong>Storage</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/developer-options.png" width="420" alt="Developer Options (KytyPS5)"/><br/>
      <strong>Developer Options (KytyPS5)</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/developer-options-shadps4.png" width="420" alt="Developer Options (ShadPS4)"/><br/>
      <strong>Developer Options (ShadPS4)</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/checking-updates.png" width="420" alt="Checking for Updates"/><br/>
      <strong>Checking for Updates</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/update-available.png" width="420" alt="Emulator Update Available"/><br/>
      <strong>Emulator Update Available</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/profile-menu.png" width="420" alt="Profile Menu"/><br/>
      <strong>Profile Menu</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/edit-profile.png" width="420" alt="Edit Profile and Avatars"/><br/>
      <strong>Edit Profile and Avatars</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/updating-piesfive.png" width="420" alt="Updating PiesFive"/><br/>
      <strong>Updating PiesFive</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/choose-avatar.png" width="420" alt="Choose Your Avatar"/><br/>
      <strong>Choose Your Avatar</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/boot-screen.png" width="420" alt="Boot Screen"/><br/>
      <strong>Boot Screen</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/about-emulators.png" width="420" alt="About the Emulators"/><br/>
      <strong>About the Emulators</strong>
    </td>
  </tr>
</table>

</details>

## Requirements

- Windows 10 or 11 (64-bit)
- A PC capable of running KytyPS5 and/or shadPS4 (see each emulator's own requirements)
- Your own legally dumped games — **PiesFive includes no games and no emulator binaries**
- PS4 trophies need a trophy key, which is not included with shadPS4 or PiesFive. Without it, PS4 games run normally but do not earn trophies.

## Roadmap

- Cloud saves (optional, using your own cloud account)
- Per-game emulator settings
- DLC / add-on support
- PiesFive Store (verified games and homebrew catalog)
- Compatibility badges from the official emulator compatibility lists

## Credits

- **[KytyPS5](https://github.com/KytyPS5/KytyPS5)** — the emulator that does the real work for PS5 games. KytyPS5 is downloaded separately from its official releases, is not part of this repository, and remains under its own license (GPL-2.0).
- **[shadPS4](https://github.com/shadps4-emu/shadPS4)** — the emulator that does the real work for PS4 games. shadPS4 is downloaded separately from its official releases, is not part of this repository, and remains under its own license (GPL-2.0).
- **Gamepad Prompt Asset Pack** by AL2009man (MIT) — controller button prompts.
- Interface artwork and icons in this project are drawn from scratch.

## License

PiesFive is free for personal use under the [PiesFive Freeware License](LICENSE): free to download and use, but it may not be sold, claimed as someone else's work, or modified and redistributed. PiesFive is not open source at this time; an open source release is planned for the future.
