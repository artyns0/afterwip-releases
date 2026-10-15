# AfterWIP Releases

This public repository hosts release metadata and installer downloads for **AfterWIP**, an Adobe After Effects companion that connects to AI assistants via the Model Context Protocol (MCP). The application source repository is private and is **not** distributed here.

## Available downloads

| Platform | Public release | Installation |
| --- | --- | --- |
| macOS (Apple Silicon and Intel) | [AfterWIP 0.2.5 Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.5-beta) | Download and install manually |
| Windows | No public Windows update release yet | Existing development installers are separate from this public release channel |

**This is a beta distribution, not a production-ready or automatically installing updater.**

Read the [0.2.5 Beta release notes](RELEASE_NOTES.md) for integrity information, manual installation steps, and known limitations.

### macOS beta: important notices

- The macOS `.pkg` is **not Apple Developer ID Installer-signed or notarized**. macOS Gatekeeper may refuse installation. Do not disable or bypass system-wide security protections.
- The opt-in AfterWIP beta updater can check the signed beta channel, download and verify an eligible package, and **reveal it in Finder**. It does not launch the installer or install in the background.
- Before manually installing, save projects and quit After Effects, render jobs, and AfterWIP MCP clients.
- Version 0.2.5 is offered as an update only to eligible installations running an older version; it will not be offered as a same-version reinstall.
- Real-world macOS installation, Adobe CEP loading, and upgrade compatibility are still subject to validation. Keep backups and use a test Mac for beta evaluation.

## Update manifest and integrity

The macOS beta channel pointer is [`channels/beta.json`](channels/beta.json). Its RSA-SHA256 signature binds the version and exact installer URL, size, SHA-256 digest, and Adobe CEP verification evidence. These checks **do not replace Apple's signing and notarization**.

The currently published beta manifest has **sequence 2** and is valid until **2026-11-14 13:41:07 UTC** (16:41 Türkiye time). It renews the original 0.2.5 package metadata without publishing a new application version. Once the manifest expires, update checks will require another correctly signed, higher-sequence manifest, even though the existing release asset remains downloadable. Never edit the manifest payload without renewing its valid signature.

The package linked from the beta manifest is the published immutable `v0.2.5-beta` release asset. Do not replace published installers or change their digest.

## Release policy

- Public repository: distribution metadata and approved installer assets only.
- No private source files, code-signing private keys, credentials, personal data, or internal build logs.
- Windows unattended/automatic updates are **disabled**. No Windows update channel is published yet.
- Future releases must be reviewed, signed as appropriate, and published with version-specific notes and integrity information.

For current downloads, use the [Releases page](https://github.com/artyns0/afterwip-releases/releases).
