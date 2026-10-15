# HMC Uploader downloads

Desktop companion for the **Hotel Motel Colibri** guild on World of Warcraft: Forever.

**Current release: [HMC Uploader 0.2.0](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/tag/uploader-v0.2.0).**

HMC Uploader watches the addon's saved data, keeps pending uploads when the website is unavailable, and sends them to the [guild website](https://hotel-motel-colibri.vercel.app). Only members who relay data for the guild need it. Addon installation and updates are handled separately through CurseForge; the uploader does not manage addon updates.

## Download version 0.2.0

| Platform | Installer |
| --- | --- |
| macOS — Apple Silicon | [Download DMG](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/download/uploader-v0.2.0/HMC-Uploader_0.2.0_darwin-aarch64.dmg) |
| macOS — Intel | [Download DMG](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/download/uploader-v0.2.0/HMC-Uploader_0.2.0_darwin-x86_64.dmg) |
| Windows — x64 | [Download installer](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/download/uploader-v0.2.0/HMC-Uploader_0.2.0_windows-x86_64-setup.exe) |

[SHA-256 checksums](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/download/uploader-v0.2.0/SHA256SUMS) · [Release notes](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/tag/uploader-v0.2.0) · [Latest release](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/latest)

Install the package for your computer, select your World of Warcraft folder, and connect it using your personal upload token from the guild website. Release builds use **https://hotel-motel-colibri.vercel.app** as their production destination.

Updates are cryptographically signed and checked before installation. The app offers **Install and restart** when an update is available and preserves settings, upload tokens and queued saves. Version 0.1.0 installations need one manual installer upgrade to gain automatic update discovery.

Updater signatures are separate from Apple notarization and Windows Authenticode. These initial installers are not notarized or Authenticode-signed, so the operating system may show a warning on first installation.

This repository contains download documentation and release artifacts. It contains no private application source code, credentials or real game data. Never attach saved-game files or upload tokens to issues here.
