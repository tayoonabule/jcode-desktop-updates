# JCode Desktop Updates

This public repository contains only signed update artifacts for JCode Desktop. The application source, build configuration, and CI implementation remain private.

## Install a community build

1. Download the latest `JCodeDesktop-*.dmg` from [Releases](../../releases).
2. Open the DMG and drag `JCodeDesktop.app` to Applications.
3. Open it once from Applications. This community build is not registered with Apple, so macOS requires an explicit first-launch approval: **System Settings → Privacy & Security → Open Anyway → Open**.

Only approve a build downloaded from this repository. After initial approval, Sparkle verifies its Ed25519-signed appcast and each update archive before extraction. That cryptographic verification protects the update path but does not represent Apple review or notarization.
