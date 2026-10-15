# HMC Uploader downloads

Desktop companion for the **Hotel Motel Colibri** guild on World of Warcraft: Forever.

**Release status:** this repository is being prepared privately. No public release is available yet.

HMC Uploader watches the addon's saved data, keeps pending uploads when the website is unavailable, and sends them to the guild website. Only members who relay data for the guild need it. The addon itself is installed and updated separately through CurseForge after its release is approved; the uploader does not manage addon updates.

## Release packages

| Platform | Package |
| --- | --- |
| macOS — Apple Silicon | `darwin-aarch64.dmg` |
| macOS — Intel | `darwin-x86_64.dmg` |
| Windows — x64 | `windows-x86_64-setup.exe` |

Full filenames include the application name and version. Release builds use **https://hotel-motel-colibri.vercel.app** as their intended production destination. Production availability and the first public release require the guild owner's approval.

Updates are cryptographically signed and checked before installation. The app offers **Install and restart** when an update is available and preserves settings and queued saves. Updater signatures are separate from Apple notarization and Windows Authenticode; the initial installers are not notarized or Authenticode-signed.

Once the first release is approved and published, installers, release notes and checksums will be available under [Releases](https://github.com/royaux70/hotel-motel-colibri-downloads/releases), with the current version at [Latest release](https://github.com/royaux70/hotel-motel-colibri-downloads/releases/latest).

This repository is reserved for download documentation and release artifacts. It contains no private application source code, credentials or real game data. Never attach saved-game files or upload tokens to issues here.
