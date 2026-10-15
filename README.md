# HMC Uploader downloads

Desktop companion for the **Hotel Motel Colibri** guild on World of Warcraft: Forever.

**Release status:** publication of HMC Uploader 0.2.0 is approved. The release packages are being built and verified; download links will appear here when they are ready.

HMC Uploader watches the addon's saved data, keeps pending uploads when the website is unavailable, and sends them to the [guild website](https://hotel-motel-colibri.vercel.app). Only members who relay data for the guild need it. Addon installation and updates are handled separately through CurseForge; the uploader does not manage addon updates.

## Release packages

Packages are being prepared for macOS Apple Silicon, macOS Intel and Windows x64. Check [Releases](https://github.com/royaux70/hotel-motel-colibri-downloads/releases) for availability.

Updates are cryptographically signed and checked before installation. The app offers **Install and restart** when an update is available and preserves settings, upload tokens and queued saves. Version 0.1.0 installations need one manual installer upgrade to gain automatic update discovery.

Updater signatures are separate from Apple notarization and Windows Authenticode. These initial installers are not notarized or Authenticode-signed, so the operating system may show a warning on first installation.

This repository contains download documentation and release artifacts. It contains no private application source code, credentials or real game data. Never attach saved-game files or upload tokens to issues here.
