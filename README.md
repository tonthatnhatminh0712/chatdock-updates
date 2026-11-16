# ChatDock releases

**Latest Windows installer:** [ChatDock Releases](https://github.com/tonthatnhatminh0712/chatdock-updates/releases/latest)

ChatDock combines Messenger, Zalo, and Telegram in one Windows window with three tabs.

- The compiled Windows installer is public. The source repository remains private.
- Version 0.1.9 and later check this repository for newer releases, download the installer, verify its SHA-256 digest, and offer an in-app **Cập nhật** button.
- Initial installation requires downloading the installer once. Future upgrades use the in-app update flow when a new release is published.
- Your chat account profiles and messages stay on your own computer and the original chat services; this repository stores only installer releases and update metadata.
- These installers are not code-signed, so Windows may show an unknown publisher warning.

For publishing maintainers: release automation from the private source repository requires its `CHATDOCK_UPDATES_TOKEN` Actions secret with Contents write access to this repository. An alternative verified upload-branch workflow (`.github/workflows/publish-upload.yml`) can publish an already-built installer without exposing the source; it checks SHA-256 before publishing and removes the temporary branch.
