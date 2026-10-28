# AfterWIP — by Artyns

<img src="assets/afterwip-horizontal-1200.png" alt="AfterWIP" width="360">

## Download AfterWIP 1.0.5

| Platform | Installer |
| --- | --- |
| Windows 10/11 x64 | [Download for Windows](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.5-windows-dev-beta/AfterWIP-1.0.5-1c027e80d008a6041b748e712d45e8e0bfab1224330bd73bdd797a558341b42a-win-x64.exe) |
| macOS 13.5+ (Apple silicon and Intel) | [Download for macOS](https://github.com/artyns0/afterwip-releases/releases/download/v1.0.5-beta/AfterWIP-1.0.5-e9e7d30fcc9387a5f1596c1e83e3ee62c89e6fde30767dbc92af220096f9e752-macOS-universal.pkg) |

See [what's new in 1.0.5](RELEASE_NOTES_1.0.5.md), [1.0.2 notes](RELEASE_NOTES_1.0.2.md), [1.0.0 notes](RELEASE_NOTES_1.0.0.md) and [checksums](SHA256SUMS_1.0.5.txt).

Windows may show a SmartScreen prompt for a new installer (**More info → Run
anyway**). If macOS blocks the package, open **System Settings → Privacy &
Security → Open Anyway**. Installers never run automatically from the
AfterWIP panel; updates are signature-verified before they are offered.

## Update channels

The AfterWIP panel reads these RSA-signed manifests (key `beta-2026-01`):

| Platform | Version | Sequence | Manifest |
| --- | --- | ---: | --- |
| macOS | 1.0.5 | 36 | [beta.json](channels/beta.json) |
| Windows | 1.0.5 | 36 | [windows-dev-beta.json](channels/windows-dev-beta.json) |

Channel file names are technical identifiers kept for compatibility.

1.0.5 adds the reference blue panel using static CSS gradients, compact profile-only Free/Pro usage, responsive vector icon cards and the original high-resolution logo. Existing simultaneous AI connections and automatic per-user MCP setup remain intact. It includes the 1.0.3 raw-batch security fix. Adobe CEP and RSA manifest signatures are verified; Windows Authenticode and Apple Developer ID/notarization remain unavailable. The owner authorized publication with these OS-signature limits. Manual installer/Adobe/Google acceptance remains for the owner. Previous 1.0.3 and 1.0.2 packages remain available.

## Previous releases

[0.3.3 notes](RELEASE_NOTES_0.3.3.md) · [All releases](https://github.com/artyns0/afterwip-releases/releases)

This repository contains installers, checksums, release notes and brand assets
only. AfterWIP is licensed under the AfterWIP End User License Agreement; the
open-source notices are installed with the application.
