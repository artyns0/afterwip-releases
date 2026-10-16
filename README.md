# AfterWIP by VisionWIP

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

Public beta installers and signed manual update metadata for the AfterWIP Adobe After Effects MCP companion.

## Current downloads — AfterWIP 0.2.9 Beta

| Platform | Installer | Release |
| --- | --- | --- |
| macOS Universal (Apple Silicon / Intel) | [Download PKG](https://github.com/artyns0/afterwip-releases/releases/download/v0.2.9-beta/AfterWIP-0.2.9-6a9d2bf7228de1a87c1e7aa65f4ecbb59a686035f3fc415ba1680322ffc5cd26-macOS-universal.pkg) | [macOS beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.9-beta) |
| Windows x64 Developer Beta | [Download EXE](https://github.com/artyns0/afterwip-releases/releases/download/v0.2.9-windows-dev-beta/AfterWIP-0.2.9-0447ed74eee19efaf57d6cbed0aa9fa6d38ad1122ccac172488f744a133de971-win-x64.exe) | [Windows developer beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.9-windows-dev-beta) |

The new approved transparent raster logo adapts to compact and wide panels; Windows Setup uses the new icon. ChatGPT, Claude and After Effects marks, Settings, Updates and Activity Log are retained. See [0.2.9 release notes](RELEASE_NOTES_0.2.9.md) for SHA-256 values, test results and limitations, or [checksums](SHA256SUMS_0.2.9.txt).

## Manual beta installation

- Windows EXE is an **Authenticode-unsigned Developer TEST BUILD**. macOS PKG has **no Apple Developer ID signature or notarization**.
- Adobe CEP signatures and RSA-signed metadata are separately verified and do not replace OS publisher signing. Retain SmartScreen, Gatekeeper and system protections.
- Save projects and quit After Effects, render jobs and active MCP clients before manual installation. Installers are never launched automatically by the updater.
- Live After Effects loading and actual installation/upgrade were NOT RUN for this release.

## Signed beta update channels

| Channel | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS beta | 0.2.9 | 5 | [beta.json](channels/beta.json) |
| Windows Developer Beta | 0.2.9 | 2 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

Both manifests expire **2026-11-16 20:21:48 UTC** (2026-11-16 23:21:48 Türkiye time). Renewal requires a new RSA signature and higher sequence; expiry does not remove released installer files. The maximum existing 31-day policy is unchanged. Beta opt-in, installed version and build/channel eligibility apply. The trusted Windows production channel and all three production gates remain disabled.

## Previous releases

[0.2.8 notes](RELEASE_NOTES_0.2.8.md) · [0.2.6 notes](RELEASE_NOTES_0.2.6.md) · [0.2.5 notes](RELEASE_NOTES.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

## Distribution policy

Only approved installers, public notes/checksums, brand assets and signed channel metadata are published here. Private implementation history and signing material remain private. Public version tags reference this metadata repository, and installer assets are immutable and hash-bound. Packaged CEP/MCP runtime JavaScript and original MIT notices remain part of the distributable application.
