<div align="center">

# PiesFive

**A console-style game launcher for PC, inspired by the PlayStation 5 interface.**
Organize your own game library and play it through the KytyPS5 emulator, with an original interface built from scratch to make emulation feel like a console.

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![License](https://img.shields.io/badge/license-freeware-blue)
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

Under the hood, PiesFive does not emulate anything itself. It launches your games through **[KytyPS5](https://github.com/KytyPS5/KytyPS5)**, the open source PlayStation 5 emulator, and handles the tedious parts for you: installing and updating the emulator, passing the right settings to it, and keeping every profile's saves and trophies organized.

## Features

- **Console-like home screen** — your games front and center, with recently played titles first.
- **Multiple user profiles** — each profile has its own name, avatar, saves and trophies.
- **Safe profiles** — saves and trophies are tied to a numeric user ID, so renaming a profile never moves or deletes your progress.
- **Full emulator control from the UI** — resolution, fullscreen, microphone selection, cursor behavior, trophy notifications and more, without touching config files.
- **Automatic emulator updates** — PiesFive fetches KytyPS5 from its official releases and keeps it up to date.
- **Trophy viewer** — browse the trophies you have unlocked in each game.
- **Game library** — covers and artwork are read from your own game files, right on your PC.
- **Controller-first navigation** — designed to be used from the couch, gamepad in hand.

## How it works

1. You add games you have dumped from **your own console and your own discs/downloads**.
2. PiesFive reads each game's own metadata and artwork from the game files themselves.
3. When you press Play, PiesFive starts KytyPS5 with your profile and settings applied.
4. KytyPS5 stores saves and trophies per user ID, and PiesFive shows them back to you in the interface.

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
      <img src="docs/screenshots/emulator-settings.png" width="420" alt="Emulator Settings"/><br/>
      <strong>Emulator Settings</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/emulator-version-manager.png" width="420" alt="Emulator Version Manager"/><br/>
      <strong>Emulator Version Manager</strong>
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
      <img src="docs/screenshots/checking-updates.png" width="420" alt="Checking for Updates"/><br/>
      <strong>Checking for Updates</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/update-available.png" width="420" alt="Emulator Update Available"/><br/>
      <strong>Emulator Update Available</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/profile-menu.png" width="420" alt="Profile Menu"/><br/>
      <strong>Profile Menu</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/edit-profile.png" width="420" alt="Edit Profile and Avatars"/><br/>
      <strong>Edit Profile and Avatars</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/updating-piesfive.png" width="420" alt="Updating PiesFive"/><br/>
      <strong>Updating PiesFive</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/choose-avatar.png" width="420" alt="Choose Your Avatar"/><br/>
      <strong>Choose Your Avatar</strong>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/boot-screen.png" width="420" alt="Boot Screen"/><br/>
      <strong>Boot Screen</strong>
    </td>
  </tr>
</table>

</details>

## Requirements

- Windows 10 or 11 (64-bit)
- A PC capable of running KytyPS5 (see the emulator's own requirements)
- Your own legally dumped games — **PiesFive includes no games and no emulator binaries**

## Roadmap

- Cloud saves (optional, using your own cloud account)
- Per-game emulator settings
- DLC / add-on support
- Emulator version manager with one-click rollback
- Compatibility badges from the official KytyPS5 compatibility list

## Credits

- **[KytyPS5](https://github.com/KytyPS5/KytyPS5)** — the emulator that does the real work. KytyPS5 is downloaded separately from its official releases, is not part of this repository, and remains under its own license (GPL-2.0).
- **Gamepad Prompt Asset Pack** by AL2009man (MIT) — controller button prompts.
- Interface artwork and icons in this project are drawn from scratch.

## License

PiesFive is free for personal use under the [PiesFive Freeware License](LICENSE): free to download and use, but it may not be sold, claimed as someone else's work, or modified and redistributed. PiesFive is not open source at this time; an open source release is planned for the future.
