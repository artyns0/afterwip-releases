# AfterWIP — by Artyns

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Download AfterWIP 1.0.0

| Platform | Installer |
| --- | --- |
| Windows 10/11 x64 | [Download for Windows](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.0-windows-dev-beta/AfterWIP-1.0.0-7638d4536e17d16795d8ca3d8bbcd6381aeb31f16e8cbd0dfaa448b6d286b626-win-x64.exe) |
| macOS 13.5+ (Apple silicon and Intel) | [Download for macOS](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.0-beta/AfterWIP-1.0.0-b6c04571927677596d8b41ad728ee81903ff34c189d7c11a08220a57727acf6f-macOS-universal.pkg) |

See [what's new](RELEASE_NOTES_1.0.0.md) and [checksums](SHA256SUMS_1.0.0.txt).

Windows may show a SmartScreen prompt for a new installer (**More info → Run
anyway**). If macOS blocks the package, open **System Settings → Privacy &
Security → Open Anyway**. Installers never run automatically from the
AfterWIP panel; updates are signature-verified before they are offered.

## Update channels

The AfterWIP panel reads these RSA-signed manifests (key `beta-2026-01`):

| Platform | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS | 1.0.0 | 31 | [beta.json](channels/beta.json) |
| Windows | 1.0.0 | 31 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

Channel file names are technical identifiers kept for compatibility.

## Previous releases

[0.3.3 notes](RELEASE_NOTES_0.3.3.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This repository contains installers, checksums, release notes and brand assets
only. AfterWIP is licensed under the AfterWIP End User License Agreement; the
open-source notices are installed with the application.
