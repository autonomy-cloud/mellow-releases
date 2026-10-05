# Mellow for macOS

This repository hosts signed Mellow downloads and the app-update feed. Application source, debug symbols, account information, and signing keys are not published here.

## Downloads

Use the published release assets. Pre-releases are qualification builds and are not yet a recommendation for general installation.

Apps built before automatic updates were configured need one manual installation of an updater-enabled release. Later versions can be reviewed and installed through Mellow’s update prompt.

## Update feed

https://raw.githubusercontent.com/autonomy-cloud/mellow-releases/main/docs/appcast.xml

Updates are signed with Mellow’s dedicated Ed25519 key and macOS Developer ID. Versioned downloads are immutable; corrections receive a new version number.
