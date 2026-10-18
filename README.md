# AfterWIP by VisionWIP

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Current downloads — AfterWIP 0.3.3 Beta

| Platform | Installer | Release |
| --- | --- | --- |
| Windows x64 Developer Beta | [Download EXE](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.3-windows-dev-beta/AfterWIP-0.3.3-38a16a43c77fe611eac4ee39c4c0a126be3649443a0fa39ee4a62501048d6497-win-x64.exe) | [Windows beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.3-windows-dev-beta) |
| macOS Universal | [Download PKG](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.3-beta/AfterWIP-0.3.3-e3623ed067f9bc50a0afed1f4cb9a4af6776f967ae6269281497b2b12bd3d447-macOS-universal.pkg) | [Mac beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.3.3-beta) |

Fixes Windows update-cache ancestor validation and recognizes the exact Codex MCP name without inventing identity. Existing client SVGs, technical sessions, Safe Mode and update checks remain. See [release notes](RELEASE_NOTES_0.3.3.md) and [checksums](SHA256SUMS_0.3.3.txt).

## Manual beta installation

Windows EXE is **Authenticode unsigned Developer Beta**. macOS PKG is **Apple Developer ID unsigned / unnotarized beta**. Adobe CEP/RSA verification does not replace OS signing. Keep UAC, SmartScreen and Gatekeeper enabled. Use Updates to check/download, save work, quit After Effects/MCP and install manually. No installer runs automatically. Live Adobe loading/install and Intel execution NOT RUN.

## Signed channels

| Channel | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS beta | 0.3.3 | 9 | [beta.json](channels/beta.json) |
| Windows Developer Beta | 0.3.3 | 6 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

RSA key ID `beta-2026-01`; expires **2026-11-17T13:11:10.846Z**. Strict expiry, rollback, package hash, Adobe pins and closed production gates remain.

## Previous releases

[0.3.2 notes](RELEASE_NOTES_0.3.2.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This public repository contains approved installers, public metadata/checksums and brand assets. Private Git history and signing keys stay private; source archives contain public metadata only. Original MIT notices remain in the application.
