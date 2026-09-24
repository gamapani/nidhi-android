# Nidhi for Android

An offline Carnatic music catalog with compositions, rāgams, composers, and lyrics in six scripts.

**[Download the latest APK](https://github.com/gamapani/nidhi-android/releases/latest/download/nidhi-release.apk)**

[Release notes and previous versions](https://github.com/gamapani/nidhi-android/releases) · [Source code](https://github.com/gamapani/nidhi)

## Install

1. Download `nidhi-release.apk` on your Android phone or tablet (Android 6.0 or later).
2. Open the downloaded file. If Android asks, allow your browser or file manager to install apps from this source.
3. Tap **Install**, then open **Nidhi**.

The app includes the catalog and all six lyric scripts: English/romanized, Kannada, Malayalam, Sanskrit/Devanāgarī, Tamil, and Telugu. No internet connection is needed to read the bundled library.

## Update

Download the latest APK and install it over your existing release installation. Releases use the same signing key. If you previously installed a debug build, uninstall it before installing a release build; uninstalling clears that app's local data.

## Verify a download

Each release includes `SHA256SUMS` alongside the APK. Download both into the same folder and run `sha256sum --check SHA256SUMS` on Linux, or `shasum -a 256 -c SHA256SUMS` on macOS.

## Source and licenses

This repository distributes the Android APK. Development and builds live in [gamapani/nidhi](https://github.com/gamapani/nidhi). Each release links to its exact application source commit; this repository's tags identify download releases, not application source revisions.

The original application code is licensed under [AGPL-3.0-only](https://github.com/gamapani/nidhi/blob/main/LICENSE). The bundled third-party catalog and lyrics have [separate permissions and rights](https://github.com/gamapani/nidhi/blob/main/DATA-LICENSE.md) and are not covered by that application license. [Third-party software notices](https://github.com/gamapani/nidhi/blob/main/public/THIRD_PARTY_NOTICES.txt) are also included in the app.
