# AfterWIP — by Artyns

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Download AfterWIP 1.0.2

| Platform | Installer |
| --- | --- |
| Windows 10/11 x64 | [Download for Windows](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.2-windows-dev-beta/AfterWIP-1.0.2-a246fa00ac5b62152d3d4d6f3c9636cdf534cad4c143c5baf259d064ff2b8a0b-win-x64.exe) |
| macOS 13.5+ (Apple silicon and Intel) | [Download for macOS](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.2-beta/AfterWIP-1.0.2-0efebfa3990c16b8bc8f1d0e01857f43812e07ca5f463ea6adaefc1c6ac86af1-macOS-universal.pkg) |

See [what's new in 1.0.2](RELEASE_NOTES_1.0.2.md), [1.0.0 notes](RELEASE_NOTES_1.0.0.md) and [checksums](SHA256SUMS_1.0.2.txt).

Windows may show a SmartScreen prompt for a new installer (**More info → Run
anyway**). If macOS blocks the package, open **System Settings → Privacy &
Security → Open Anyway**. Installers never run automatically from the
AfterWIP panel; updates are signature-verified before they are offered.

## Update channels

The AfterWIP panel reads these RSA-signed manifests (key `beta-2026-01`):

| Platform | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS | 1.0.2 | 33 | [beta.json](channels/beta.json) |
| Windows | 1.0.2 | 33 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

Channel file names are technical identifiers kept for compatibility.

Real installer/Adobe/Google lifecycle acceptance tests for 1.0.2 were not completed; publication proceeded at the owner's request. See the release notes for the validation scope. Previous 1.0.1 packages remain available.

## Previous releases

[0.3.3 notes](RELEASE_NOTES_0.3.3.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This repository contains installers, checksums, release notes and brand assets
only. AfterWIP is licensed under the AfterWIP End User License Agreement; the
open-source notices are installed with the application.
