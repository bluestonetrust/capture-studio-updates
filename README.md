# Capture Studio for macOS

This repository contains published installers, release notes and the signed Sparkle update feed. It does not contain personal captures, signing keys or the app source code.

[Download the latest release](https://github.com/bluestonetrust/capture-studio-updates/releases/latest)

## Install or upgrade from 1.3 / 1.4

Download the universal `.dmg` from the release assets. Finish recording and quit Capture Studio, keep a rollback copy of the old app, then drag the new app into the same folder as the old one and choose Replace. Open the installed app after ejecting the disk image. Your library in `Pictures/Capture Studio` and your settings stay in place; do not replace or delete the library.

Requires macOS 15 or later. The app includes Apple silicon and Intel binaries; testing has been performed on Apple silicon. The app is ad-hoc signed and is not Apple-notarized. macOS may request approval to open it or refresh Screen & System Audio Recording permission. Microphone permission is needed only for narration.

## Updates from 1.5 onward

Choose **Capture Studio → Check for Updates…**, then **Install Update → Install and Relaunch**. Automatic checks default on and can be disabled in the same menu. Installing requires confirmation; active captures, recordings and unsaved edits defer the update.

The feed and update archive are signed and verified before extraction. Update checks and downloads contact GitHub; captures stay on your Mac, and system profiling is disabled. `.zip` and `appcast.xml` release assets are used by the updater; choose the `.dmg` for manual installation. `SHA256SUMS.txt` lists release-file checksums.

Signed feed: `https://github.com/bluestonetrust/capture-studio-updates/releases/latest/download/appcast.xml`
