# AfterWIP 0.2.8 Beta — Release Notes

**Published:** October 16, 2026  
**Platforms:** macOS (Apple Silicon and Intel) and Windows x64 (Developer Beta)  
**Installation:** Manual only

## What's new

- Refined compact AfterWIP panel with the neon Updates popover.
- Removed Restart Bridge, Open Library and Advanced Options cards from the home screen while retaining underlying functionality required elsewhere.
- ChatGPT/Claude indicators reflect self-reported active MCP client session names, with timeout and multiple-session handling; those labels are never used for authorization.
- Repeatable Windows-to-Mac native build pipeline with independently checked Adobe CEP signing evidence.
- Retained 50 MCP tools, 34 write functions, Safe Mode and manual download flow.

## Download the beta installers

- [macOS Universal 0.2.8 Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.8-beta)
  - File: `AfterWIP-0.2.8-e08de3c55879d7f9ae5426449b1234be7999207e9d5847519517f8b86ae42cc0-macOS-universal.pkg`
  - SHA-256: `e08de3c55879d7f9ae5426449b1234be7999207e9d5847519517f8b86ae42cc0`
  - Size: 80,430,837 bytes
- [Windows x64 0.2.8 Developer Beta](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.8-windows-dev-beta)
  - File: `AfterWIP-0.2.8-238aafd6985d9aca63fe71a286a507b0dadc72fde9b738302d36e14709ea1e24-win-x64.exe`
  - SHA-256: `238aafd6985d9aca63fe71a286a507b0dadc72fde9b738302d36e14709ea1e24`
  - Size: 48,130,701 bytes

## Security and installation limitations

**These are beta installers, not production code-signed distributions.**

- **macOS:** Apple Developer ID Installer signature and notarization are absent. The embedded Adobe CEP component carries a separately verified Adobe signature.
- **Windows:** The EXE lacks Authenticode publisher signing. It is explicitly a Developer TEST BUILD, not a trusted production release.
- Both signed beta update manifests verify installer metadata and Adobe CEP signing evidence, but this is not a substitute for operating-system-level signing.
- Save your work and close After Effects and MCP clients before installation. Open and install packages manually only if permitted by local security policy; do not disable SmartScreen, Gatekeeper or other system protections.
- Neither updater automatically launches or installs installers.

## Release and update channels

- [macOS beta manifest](channels/beta.json): **version 0.2.8, sequence 4**.
- [Windows Developer Beta manifest](channels/windows-dev-beta.json): **version 0.2.8, sequence 1**, developer-only, separate from any trusted Windows channel.
- Both manifests expire **October 23, 2026 at 08:54:13 UTC**. They must be renewed through an authorized signing workflow after expiry; released assets remain independently downloadable.
- Version 0.2.8 will not be offered as a new update to a currently installed 0.2.8 client.

## Verification status

Reported automated tests: macOS 602 passed, 0 failed, 9 skipped; Windows 392 passed, 0 failed, 50 skipped; release qualification 22 passed, 0 failed, 2 skipped. The owner reports successful live After Effects installation and use on one Windows and one Mac system; this does not amount to certification across all configurations.

[All releases](https://github.com/artyns0/afterwip-releases/releases)
