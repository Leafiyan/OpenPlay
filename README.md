<div align="center">

<img src="https://openplaylauncher.com/images/openplay-icon.png" width="96" alt="OpenPlay logo">

# OpenPlay

**All your PC games in one clean, simple library.**

[![Latest version](https://img.shields.io/github/v/release/Leafiyan/OpenPlay?label=version&color=7c6cf5&style=flat-square)](https://github.com/Leafiyan/OpenPlay/releases/latest)
![Windows 10 and 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square)
[![Downloads](https://img.shields.io/github/downloads/Leafiyan/OpenPlay/total?color=28aa3d&style=flat-square)](https://github.com/Leafiyan/OpenPlay/releases)
[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white&style=flat-square)](https://discord.gg/U6gvrYwXPp)

[Discord](https://discord.gg/U6gvrYwXPp) &nbsp;·&nbsp; [Website](https://openplaylauncher.com) &nbsp;·&nbsp; [Roadmap](https://openplaylauncher.com/roadmap) &nbsp;·&nbsp; [FAQ](https://openplaylauncher.com/faq) &nbsp;·&nbsp; [Support](#community-and-support)

<br>

<img src="https://openplaylauncher.com/images/screenshots/library.webp" alt="The OpenPlay library" width="860">

</div>

## Why OpenPlay?

Modern PC gaming is spread across multiple storefronts, each with its own launcher. OpenPlay unifies Steam, Epic Games, Battle.net, Xbox / PC Game Pass, your own console games through emulators and games installed from anywhere else into a single, fast library. Games are detected automatically, enriched with high-quality artwork and metadata, and launched through their original platform, giving you one place to browse, organise and play your entire collection, with no plugins or configuration required.

## Features

### Your library
- **Every store in one place**, installed or not, with games you own on several stores shown once.
- **Favourites and completed** to keep track of what you love and what you've finished.
- **Collections** to group games your way, plus filters by store and genre.
- **Play time** for every game: first played, last played and total hours.

### Artwork and details
- **Found automatically** from each game's store, Steam, SteamGridDB and IGDB, and refreshed every week.
- **Clean banners** with the game's logo on top, plus covers, icons, descriptions, genres and release dates.
- **Fully editable**: rename a game, fix its details or choose your own pictures.

### Emulators
- **One-click install** for NES, SNES, Nintendo 64, GameCube & Wii, Game Boy, Nintendo DS and 3DS, PlayStation 1 to 3, PSP and Dreamcast, straight from each emulator's own project.
- **Your ROMs in your library**: choose a games folder and every game in it appears, ready to play.
- **Already have an emulator?** OpenPlay finds it on your PC, or you can locate it yourself.
- **Uninstall cleanly**: removing an emulator keeps your games and saves.

### Accounts and storage
- **Sign in safely** on each store's own website. OpenPlay never sees your password.
- **See your drives** at a glance, with the space each store's games use.
- **Find any install folder** in one click.

## Supported stores

| Store | Installed games | Owned games | Launch and install |
| --- | :---: | :---: | :---: |
| Steam | ✅ | ✅ | ✅ |
| Epic Games | ✅ | ✅ | ✅ |
| Battle.net | ✅ | ✅ | ✅ |
| Xbox / PC Game Pass | ✅ | Planned | ✅ |
| Emulators (your own console games) | ✅ | – | ✅ |
| Your own games | ✅ | – | ✅ |

<details>
<summary><b>More screenshots</b></summary>
<br>

| | |
| :---: | :---: |
| <img src="https://openplaylauncher.com/images/screenshots/favourites.webp" alt="Favourites"> | <img src="https://openplaylauncher.com/images/screenshots/platforms.webp" alt="Store page"> |
| Favourites | Store pages |
| <img src="https://openplaylauncher.com/images/screenshots/emulators.webp" alt="Emulators"> | <img src="https://openplaylauncher.com/images/screenshots/edit-game.webp" alt="Edit Game"> |
| Emulators | Edit Game |
| <img src="https://openplaylauncher.com/images/screenshots/collections.webp" alt="Collections"> | <img src="https://openplaylauncher.com/images/screenshots/accounts.webp" alt="Accounts"> |
| Collections | Accounts |
| <img src="https://openplaylauncher.com/images/screenshots/storage.webp" alt="Storage"> | |
| Storage | |

</details>

## How it works

- **Uses your stores' own apps.** Steam, Epic, Battle.net and Xbox still download, update and run your games. OpenPlay starts each game through the right one, and console games through their emulator.
- **Bring your own games.** OpenPlay never provides games, BIOS files or firmware for emulators.
- **Your data stays on your PC.** No accounts, ads or tracking. [Privacy policy](https://openplaylauncher.com/privacy)
- **Lightweight.** A small download that starts quickly and keeps artwork cached for offline use.
- **Safe updates.** Every update is signed and checked, and OpenPlay asks before installing one.

## Getting started

1. Download and run **[OpenPlay-Setup.exe](https://github.com/Leafiyan/OpenPlay/releases/latest/download/OpenPlay-Setup.exe)**.
2. Open **Settings → Accounts** and connect your stores.
3. Pick a game and press **Play**.

Requires Windows 10 or 11.

## FAQ

<details>
<summary><b>Is OpenPlay free?</b></summary>
<br>Yes, completely. There's nothing to buy, no subscription and no ads.
</details>
<details>
<summary><b>Can I add games that aren't from a store?</b></summary>
<br>Yes. Scan a folder to add the games in it, or add a library folder so OpenPlay picks up new games automatically. You can also set your own cover, banner and icon for any game.
</details>
<details>
<summary><b>Can I play console games?</b></summary>
<br>Yes, the ones you own. Open <b>Add Platform → Emulators</b>, install an emulator in one click (or locate one you already have), then choose the folder your games are in. Some consoles, such as PlayStation, also need a BIOS file from your own console.
</details>
<details>
<summary><b>Why does Windows show a warning when I install it?</b></summary>
<br>Windows SmartScreen warns about new apps from independent developers until enough people have installed them. To continue, click <b>More info</b>, then <b>Run anyway</b>.
</details>
<details>
<summary><b>Is there a Mac or Linux version?</b></summary>
<br>Not yet. Both are on the <a href="https://openplaylauncher.com/roadmap">roadmap</a>.
</details>
<details>
<summary><b>How do I uninstall OpenPlay?</b></summary>
<br>Delete <code>OpenPlay.exe</code> from the folder you installed it to (by default <code>%LOCALAPPDATA%\Programs</code>), along with any desktop or Start menu shortcuts. Your library and settings are kept in <code>%APPDATA%\openplay</code>, so delete that folder too if you want to remove everything.
</details>

More answers are in the [full FAQ](https://openplaylauncher.com/faq).

## What's next

GOG, EA app and Ubisoft Connect support and a controller-friendly mode are planned. See the [roadmap](https://openplaylauncher.com/roadmap) for what's coming.

## Community and support

Report bugs and share ideas with **Send Feedback** in the app or on [Discord](https://discord.gg/U6gvrYwXPp). OpenPlay is free and made by an independent developer. If you'd like to help it grow:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-FF5E5B?logo=kofi&logoColor=white&style=for-the-badge)](https://ko-fi.com/leafiyan)
[![Patreon](https://img.shields.io/badge/Patreon-Join-FF424D?logo=patreon&logoColor=white&style=for-the-badge)](https://www.patreon.com/cw/Leafiyan)

---

<sub>Game details from IGDB. Steam, Epic Games, Battle.net, Xbox and the console names above are trademarks of their respective owners. OpenPlay is not affiliated with any of them, or with the emulators it can install.</sub>
