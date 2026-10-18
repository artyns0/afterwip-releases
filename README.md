# AfterWIP by VisionWIP

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Current downloads — AfterWIP 0.3.2 Beta

| Platform | Installer | Release |
| --- | --- | --- |
| Windows x64 Developer Beta | [Download EXE](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.2-windows-dev-beta/AfterWIP-0.3.2-0735f0fcb3102779cb0d966ac0920adea4def0ae4bb3337706a1651a11e3de35-win-x64.exe) | [Windows beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.2-windows-dev-beta) |
| macOS Universal (Apple Silicon / Intel) | [Download PKG](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.2-beta/AfterWIP-0.3.2-c4608dcd9107dd0f84698a216674f164bfa482317f30eec2536eacee2690652a-macOS-universal.pkg) | [Mac beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.2-beta) |

0.3.2 displays Codex and ChatGPT under the ChatGPT name and existing local SVG. Technical session labels/counts and all 0.3.1 connection fixes, artwork and security remain. See [release notes](RELEASE_NOTES_0.3.2.md) and [SHA-256 checksums](SHA256SUMS_0.3.2.txt).

## Manual beta installation

Windows EXE is an **Authenticode-unsigned Developer TEST BUILD**; Mac PKG has **no Apple Developer ID signature or notarization**. Adobe CEP and RSA signatures do not replace OS signing. Keep SmartScreen, Gatekeeper and other protections enabled.

Use an eligible beta channel in AfterWIP Updates to check/download. Save projects, quit After Effects/render jobs/active MCP clients and install manually. No installer is launched automatically. Native Adobe refresh and actual install/upgrade were **NOT RUN**.

## Signed beta channels

| Channel | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS beta | 0.3.2 | 8 | [beta.json](channels/beta.json) |
| Windows Developer Beta | 0.3.2 | 5 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

RSA key ID `beta-2026-01`; expiry **2026-11-18 12:07:10 UTC** (2026-11-18 15:07:10 Türkiye time). Renewal requires a new signature and higher sequence. Existing 31-day limit, beta/build eligibility, trust pins and all disabled production gates remain.

## Previous releases

[0.3.1 notes](RELEASE_NOTES_0.3.1.md) · [0.3.0 notes](RELEASE_NOTES_0.3.0.md) · [0.2.9 notes](RELEASE_NOTES_0.2.9.md) · [0.2.8 notes](RELEASE_NOTES_0.2.8.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This public repository contains approved installers, metadata/checksums and brand assets. Private Git history and signing material stay private; version tags/source archives reference public metadata only. Packaged runtime JavaScript and original MIT notices remain part of the application.
