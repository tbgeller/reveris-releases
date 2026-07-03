# Reveris Releases

This repository hosts **only** the publicly downloadable, cryptographically
signed release artifacts for the Reveris desktop application, along with the
`latest.json` update manifest that Reveris uses to auto-update over the open web.

**The Reveris source code is not here.** It is private and proprietary. This
repository contains no source, no build configuration, and no secrets; it holds
only finished, signed installers and the update manifest.

## What is Reveris

Reveris is a desktop application for authoring, previewing, and publishing
electronic-learning content. It is proprietary software; use is governed by the
End User License Agreement presented within the application on first run. See
[LICENSE.txt](LICENSE.txt).

## Downloading and installing

1. Open the [Releases](../../releases) page and download the latest Windows
   installer (`.exe`) from the newest release.
2. Run the installer. On a first install, Windows may show a
   "Windows protected your PC" notice; choose **More info**, then **Run anyway**.
3. Launch Reveris. Once installed, the app checks this repository for updates and
   installs them automatically. Every update is signature-verified against the
   key built into the app, so a tampered or unofficial build is refused.

## Security

Each artifact published here is signed during the build with a private key that
never leaves the build environment. Installed copies of Reveris carry the
matching public key and will only install updates whose signature matches. This
check cannot be disabled.
