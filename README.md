# Imaracore for Android

The operating core for community finance.

**[Download the latest APK](https://github.com/philwamba/imaracore-downloads/releases/latest/download/imaracore.apk)**

[Release notes and all versions](https://github.com/philwamba/imaracore-downloads/releases)

Requires Android 8.0 or later. Download the APK on your Android device, open it,
and allow installation from your browser when Android prompts you. Future
versions install over the existing app and retain its data.

## Versioning

Releases use `vMAJOR.MINOR.PATCH-build.NUMBER` (for example, `v0.1.0-build.1`).
Features increment MINOR; fixes increment PATCH; breaking changes increment
MAJOR. Both the displayed version and Android build number increase for each
published release. While below 1.0, the app is in initial development.

Each release includes a versioned APK, the identical `imaracore.apk` for the
stable latest-download link, `SHA256SUMS`, and `release.json` with the source
commit, package version, API endpoint, and signing certificate fingerprint.
Published releases are retained; APKs are never overwritten. All updates use
the same signing certificate.

To verify a download, obtain its `SHA256SUMS` from the same release and compare
the APK's SHA-256 checksum using `sha256sum` (Linux) or `shasum -a 256` (macOS).

This repository contains public downloads only. Source code and signing keys
are maintained separately.
