# Imaracore for Android

The operating core for community finance.

## Download

**Current version: 0.4.1 (build 5)**

**[Download imaracore-v0.4.1-build.5.apk](https://github.com/philwamba/imaracore-downloads/releases/download/v0.4.1-build.5/imaracore-v0.4.1-build.5.apk)**

[Release notes and all versions](https://github.com/philwamba/imaracore-downloads/releases)

Requires Android 8.0 or later. Download the APK on your Android device, open it,
and allow installation from your browser when Android prompts you. Future
versions install over the existing app and retain its data.

## Versioning

Releases are tagged `vMAJOR.MINOR.PATCH-build.NUMBER` (for example, `v0.4.1-build.5`)
and every APK carries its version in its file name (for example, `imaracore-v0.4.1-build.5.apk`).
Features increment MINOR; fixes increment PATCH; breaking changes increment
MAJOR. Both the displayed version and the Android build number increase for
each published release. While below 1.0, the app is in initial development.

Each release includes the versioned APK, `SHA256SUMS`, and `release.json` with
the source commit, package version, API endpoint, and signing certificate
fingerprint. Published releases are retained; APKs are never overwritten, and
this page is updated with every release to link to the newest APK. All updates
use the same signing certificate.

To verify a download, obtain its `SHA256SUMS` from the same release and compare
the APK's SHA-256 checksum using `sha256sum` (Linux) or `shasum -a 256` (macOS).

This repository contains public downloads only. Source code and signing keys
are maintained separately.
