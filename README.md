# Reveris Releases

This repository hosts only the publicly downloadable, cryptographically signed
release artifacts for the Reveris desktop application, plus the `latest.json`
manifest the app uses to auto-update.

**The Reveris source code is not here.** It is private and proprietary. This
repository contains no source, no build configuration, and no secrets: only
finished, signed installers and the update manifest.

Reveris is proprietary software. Use is governed by the End User License
Agreement presented within the application on first run. See [LICENSE.txt](LICENSE.txt).

Windows installers are published on the [Releases](../../releases) page.

## Security

Every artifact here is signed during the build with a private key that never
leaves the build environment. Installed copies of Reveris carry the matching
public key and install only updates whose signature matches; this check cannot
be disabled.
