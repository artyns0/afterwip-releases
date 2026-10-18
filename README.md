# AfterWIP by VisionWIP

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Current downloads — AfterWIP 0.3.1 Beta

| Platform | Installer | Release |
| --- | --- | --- |
| Windows x64 Developer Beta | [Download EXE](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.1-windows-dev-beta/AfterWIP-0.3.1-c1b6e93dbead5f6088d8fb976c3da9cdbf4957e1b4b9bfd87cb0a0e27611fc3f-win-x64.exe) | [Windows beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.1-windows-dev-beta) |
| macOS Universal (Apple Silicon / Intel) | [Download PKG](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.1-beta/AfterWIP-0.3.1-2a05b764e2ce6b19c1c4da36d89841da0e2887178da74af0a8ebe5c8b08f1fa7-macOS-universal.pkg) | [Mac beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.1-beta) |

0.3.1 fixes panel Refresh/port recovery and groups technical MCP sessions by reported client label. Existing 0.3.0 artwork/features and security remain. See [release notes](RELEASE_NOTES_0.3.1.md) and [SHA-256 checksums](SHA256SUMS_0.3.1.txt).

## Manual beta installation

Windows EXE is an **Authenticode-unsigned Developer TEST BUILD**; Mac PKG has **no Apple Developer ID signature or notarization**. Adobe CEP and RSA signatures do not replace OS signing. Keep SmartScreen, Gatekeeper and other protections enabled.

Use an eligible beta channel in AfterWIP Updates to check/download. Save projects, quit After Effects/render jobs/active MCP clients and install manually. No installer is launched automatically. Native Adobe refresh and actual install/upgrade were **NOT RUN**.

## Signed beta channels

| Channel | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS beta | 0.3.1 | 7 | [beta.json](channels/beta.json) |
| Windows Developer Beta | 0.3.1 | 4 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

RSA key ID `beta-2026-01`; expiry **2026-11-18 10:05:49 UTC** (2026-11-18 13:05:49 Türkiye time). Renewal requires a new signature and higher sequence. Existing 31-day limit, beta/build eligibility, trust pins and all disabled production gates remain.

## Previous releases

[0.3.0 notes](RELEASE_NOTES_0.3.0.md) · [0.2.9 notes](RELEASE_NOTES_0.2.9.md) · [0.2.8 notes](RELEASE_NOTES_0.2.8.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This public repository contains approved installers, metadata/checksums and brand assets. Private Git history and signing material stay private; version tags/source archives reference public metadata only. Packaged runtime JavaScript and original MIT notices remain part of the application.
