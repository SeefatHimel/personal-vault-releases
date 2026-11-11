# Personal Vault Android previews

This repository contains preview APK downloads, checksums and signed update metadata. The application source repository and private signing keys are separate.

[Download build 12](https://github.com/SeefatHimel/personal-vault-releases/releases/tag/android-preview-12) · [All previews](https://github.com/SeefatHimel/personal-vault-releases/releases)

## Install once, then use App updates

1. Keep an encrypted recovery export and install the updater-enabled APK over the compatible existing Personal Vault test app. Do not uninstall to update.
2. Open Settings → App updates. Automatic checks are optional; Check now is always available. Downloads start only when you choose.
3. Future builds offer Download update, then Install update. The vault locks and Android controls permission and installation approval.

In-app release information is signed; APK integrity, package/version and signing continuity are checked before installation. The app remains usable offline or if update checks fail.

These are internal previews signed with the existing local Android test certificate, for fictional-data testing. They are not production/store releases or independently certified security builds. Physical-device installer/data-preservation and live Google acceptance remain pending. Google Drive is limited to configured testing accounts; local vault use works offline.

Public update requests expose ordinary network metadata to GitHub, not vault entries, master phrases or Google access tokens. Disable automatic checks in App updates if you prefer manual checks.

`preview.json` is signed channel metadata for the app. Its expiry is maintained separately from APK publication; no private key belongs in this repository.
