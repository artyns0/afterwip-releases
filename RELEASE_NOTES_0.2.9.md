# AfterWIP 0.2.9 Beta — Release Notes

- Updated AfterWIP branding with the owner-approved transparent raster logo kit.
- Wide panels show the horizontal logo; compact panels retain a square icon and single title.
- Updated Windows Setup/uninstall icon. ChatGPT, Claude and After Effects icons are unchanged.
- Settings, Updates, Activity Log, Safe Mode, local authentication and 50 MCP tools/34 write functions retained.
- Manual installation only. Windows EXE is an Authenticode-unsigned Developer TEST BUILD; macOS PKG has no Apple Developer ID signature or notarization. Adobe CEP signatures are verified separately.
- Live After Effects loading and actual installation/upgrade were not run.

Signed channel manifests use the existing RSA/Adobe pins, exactly the next verified sequence per channel, and the maximum existing 31-day policy validity. After expiry a new signature and higher sequence are required.

## Verified downloads

| Platform | Download | Bytes | SHA-256 |
| --- | --- | ---: | --- |
| macOS Universal | [Installer](https://github.com/artyns0/afterwip-releases/releases/download/v0.2.9-beta/AfterWIP-0.2.9-6a9d2bf7228de1a87c1e7aa65f4ecbb59a686035f3fc415ba1680322ffc5cd26-macOS-universal.pkg) | 80728334 | `6a9d2bf7228de1a87c1e7aa65f4ecbb59a686035f3fc415ba1680322ffc5cd26` |
| Windows x64 Developer Beta | [Installer](https://github.com/artyns0/afterwip-releases/releases/download/v0.2.9-windows-dev-beta/AfterWIP-0.2.9-0447ed74eee19efaf57d6cbed0aa9fa6d38ad1122ccac172488f744a133de971-win-x64.exe) | 48650588 | `0447ed74eee19efaf57d6cbed0aa9fa6d38ad1122ccac172488f744a133de971` |

## Validation

- Windows: 484 PASS, 0 FAIL, 46 platform SKIP.
- Mac: 611 PASS, 0 FAIL, 9 platform SKIP.
- 15 responsive Chromium scenarios at 2x pixel density and 3 Node17.7.1 compatibility fixtures passed.
- Native Windows and arm64 Mac runtime/launcher/MCP smoke passed: 50 tools, 34 write functions; Mac 23 prompts. The x64 Mac runtime was not executed on the arm64 host; its pinned archive and Mach-O architecture were verified.
- Final EXE independently extracted: 274 files exactly matched staged payload/helpers. Final PKG expanded: 171 script/payload files exactly matched staged modes/hashes.
- Actual Adobe CEP signature, timestamp, publisher, source/logos and private-material/incorrect-content scans passed.
- Actual installation/upgrade, native Windows SCM/security deployment and live After Effects CEP loading were NOT RUN.

## Signed update channels

macOS beta sequence **5**, Windows developer-beta sequence **2**. Both RSA-signed manifests expire **2026-11-16 20:21:48 UTC** (2026-11-16 23:21:48 Türkiye time). Validity is 31 days within the unchanged client policy. After expiry, a fresh signature and strictly newer sequence are required; immutable installer downloads remain available. Beta opt-in, channel/build gates, version eligibility and manual installation still apply.
