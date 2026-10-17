# AfterWIP by VisionWIP

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

Public beta installers and signed manual update metadata for the AfterWIP Adobe After Effects MCP companion.

## Current downloads — AfterWIP 0.3.0 Smart Connection Beta

| Platform | Installer | Release |
| --- | --- | --- |
| Windows x64 Developer Beta | [Download EXE](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.0-windows-dev-beta/AfterWIP-0.3.0-b9d42125c38c01dddfc90e1801637c2fda8d562e8befa5ecca48160851c3d481-win-x64.exe) | [Windows developer beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.0-windows-dev-beta) |
| macOS Universal (Apple Silicon / Intel) | [Download PKG](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.0-beta/AfterWIP-0.3.0-a847964c7eb287c0476391439c5e2d2f0d73444ead4dca3d3ea55a6fb51238c3-macOS-universal.pkg) | [macOS beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.0-beta) |

A simpler connection card shows authenticated, unexpired AI sessions with local provider icons and bounded bridge recovery. Client names remain self-reported labels; tool calls/writes are never replayed. The approved AfterWIP logo, Safe Mode, Settings, Updates and Activity Log remain. See [0.3.0 release notes](RELEASE_NOTES_0.3.0.md) for test results and limits, or [SHA-256 checksums](SHA256SUMS_0.3.0.txt).

## Manual beta installation

- Windows EXE is an **Authenticode-unsigned Developer TEST BUILD**. macOS PKG has **no Apple Developer ID signature or notarization**.
- Adobe CEP signatures and RSA-signed metadata are separately verified and do not replace OS publisher signing. Retain SmartScreen, Gatekeeper and system protections.
- Use the eligible beta channel in AfterWIP Updates to check/download, then install manually. Installers are never launched automatically.
- Save projects and quit After Effects, render jobs and active MCP clients before installation.
- Live After Effects loading, native CEP close/reopen and actual installation/upgrade were **NOT RUN** for this release.

## Signed beta update channels

| Channel | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS beta | 0.3.0 | 6 | [beta.json](channels/beta.json) |
| Windows Developer Beta | 0.3.0 | 3 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

Both manifests expire **2026-11-17 22:58:35 UTC** (2026-11-18 01:58:35 Türkiye time). Renewal requires a new RSA signature and higher sequence; expiry does not remove released installer files. The maximum existing 31-day policy is unchanged. Beta opt-in, installed version and build/channel eligibility apply. The trusted Windows production channel and all three production gates remain disabled.

## Previous releases

[0.2.9 notes](RELEASE_NOTES_0.2.9.md) · [0.2.8 notes](RELEASE_NOTES_0.2.8.md) · [0.2.6 notes](RELEASE_NOTES_0.2.6.md) · [0.2.5 notes](RELEASE_NOTES.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

## Distribution policy

Only approved installers, public notes/checksums, brand assets and signed channel metadata are published here. Private implementation history and signing material remain private. Public version tags reference this metadata repository, and installer assets are immutable and hash-bound. Packaged CEP/MCP runtime JavaScript and original MIT notices remain part of the distributable application.
