# AfterWIP Releases

This public repository hosts release metadata and installer downloads for **AfterWIP**, an Adobe After Effects companion that connects to AI assistants via the Model Context Protocol (MCP). The application source repository is private and is **not** distributed here.

## Available downloads

| Platform | Public release | Installation |
| --- | --- | --- |
| macOS (Apple Silicon and Intel) | [AfterWIP 0.2.6 Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.6-beta) | Download and install manually |
| Windows | No public Windows update release yet | Existing development installers are separate from this public release channel |

**This is a beta distribution, not a production-ready or automatically installing updater.**

Read the [0.2.6 Beta release notes](RELEASE_NOTES_0.2.6.md) for manual installation, integrity information and limitations. Older [0.2.5 Beta notes](RELEASE_NOTES.md) are kept for reference.

### macOS beta: important notices

- The macOS `.pkg` is **not Apple Developer ID Installer-signed or notarized**. macOS Gatekeeper may refuse installation. Do not disable or bypass system-wide security protections.
- The opt-in AfterWIP beta updater can check the signed beta channel, download and verify an eligible package, and **reveal it in Finder**. It does not launch the installer or install in the background.
- Before manually installing, save projects and quit After Effects, render jobs, and AfterWIP MCP clients.
- Version 0.2.6 is offered as an update only to eligible installations running an older version; it will not be offered as a same-version reinstall.
- An owner-reported macOS 0.2.6 manual installation opened successfully; broad device compatibility and automated client-side downloading remain to be validated. Keep backups and use a test Mac for beta evaluation.

## Update manifest and integrity

The macOS beta channel pointer is [`channels/beta.json`](channels/beta.json). Its RSA-SHA256 signature binds the version and exact installer URL, size, SHA-256 digest, and Adobe CEP verification evidence. These checks **do not replace Apple's signing and notarization**.

The currently published beta manifest has **sequence 3** (version **0.2.6**) and is valid until **2026-11-14 18:47:32 UTC** (21:47 Türkiye time). The signed manifest points to the immutable 0.2.6 beta release package. After expiry, update checks will require a newly signed, higher-sequence manifest; the current installer remains separately downloadable.

The package linked from the beta manifest is the published immutable `v0.2.6-beta` release asset. Older `v0.2.5-beta` files remain available as historical releases. Do not replace published installers or change their digest.

## Release policy

- Public repository: distribution metadata and approved installer assets only.
- No private source files, code-signing private keys, credentials, personal data, or internal build logs.
- Windows unattended/automatic updates are **disabled**. No Windows update channel is published yet.
- Future releases must be reviewed, signed as appropriate, and published with version-specific notes and integrity information.

For current downloads, use the [Releases page](https://github.com/artyns0/afterwip-releases/releases).
