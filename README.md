# AfterWIP Releases

This repository hosts **public beta installers and signed update-channel metadata** for AfterWIP, an Adobe After Effects companion application with Model Context Protocol (MCP) integration. The application source repository remains private and is **not** distributed here.

## Current downloads — AfterWIP 0.2.8 Beta

| Platform | Beta release | Installation |
| --- | --- | --- |
| macOS (Apple Silicon / Intel) | [AfterWIP 0.2.8 Universal Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.8-beta) | Manual PKG installation |
| Windows x64 (Developer Beta) | [AfterWIP 0.2.8 Windows Developer Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.8-windows-dev-beta) | Manual EXE installation; developer/test use only |

Read the [0.2.8 Beta release notes](RELEASE_NOTES_0.2.8.md) for exact SHA-256 checksums, file sizes, changes, and important installation limitations. Earlier [0.2.6 Beta notes](RELEASE_NOTES_0.2.6.md) and [0.2.5 Beta notes](RELEASE_NOTES.md) remain available.

## Important security notice

**These installers are beta builds, not production-signed releases.**

- The macOS PKG is **not Apple Developer ID Installer-signed or notarized**.
- The Windows Developer Beta EXE is **not Authenticode-signed**. This public prerelease is not a trusted Windows update distribution.
- Adobe CEP signature validation and RSA-SHA256-signed update manifests bind release metadata and verified CEP evidence, but **do not replace operating-system signing**.
- Do not disable or bypass SmartScreen, Gatekeeper, or system-wide security protections to install.
- Save projects, quit After Effects, and stop active render jobs/MCP clients before manual installation.
- AfterWIP never automatically opens or installs downloaded update packages.

## Signed beta update channels

| Channel | Version | Sequence | Manifest |
| --- | --- | --- | --- |
| macOS beta | 0.2.8 | 4 | [channels/beta.json](channels/beta.json) |
| Windows Developer Beta (developer-only) | 0.2.8 | 1 | [channels/windows-dev-beta.json](channels/windows-dev-beta.json) |

Both current manifests expire **2026-10-23 08:54:13 UTC** (11:54 Türkiye time). Renew them with an authorized RSA-signed higher-sequence manifest before expiration if continuing update availability. Expiration does not remove previously released installer files. Updater eligibility, beta opt-in, and client version policies still apply. A client already running 0.2.8 will not be offered the same version as a new update.

## Release policy

- Public repo holds approved installer downloads, notes, and signed channel metadata only; no private source, credentials, RSA or Adobe private keys.
- The Windows Developer Beta channel is distinct from the **disabled** trusted Windows production update channel.
- No automatic installation or production update gates are enabled.
- New packages are immutable, versioned, and published with their real SHA-256 digests.

[Browse all releases](https://github.com/artyns0/afterwip-releases/releases)
