# AfterWIP 0.2.6 Beta — Release Notes

**Published:** October 15, 2026  
**Channel:** macOS beta (opt-in)  
**Platforms:** macOS Apple Silicon and Intel, universal package  
**Installation:** Manual only

## What changed

- AfterWIP 0.2.6 adds the manual update flow: check for updates, verify available version, download with progress, and reveal the installer in Finder.
- Downloads are subject to RSA-SHA256 manifest signature and package SHA-256 checks. The beta manifest binds the verified Adobe CEP signing evidence.
- The updater never automatically launches or installs a package. Existing MCP, Safe Mode and recovery functionality is retained.
- The macOS 0.2.6 package supports upgrade from an installed older version using the verified transaction/recovery workflow.

## Download

[AfterWIP 0.2.6 Beta release](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.6-beta)

File: `AfterWIP-0.2.6-efa23e54f4ff726c336920243848caa206c0cc5ad3645adc1cbfaec98ba4bce7-macOS-universal.pkg`

SHA-256: `efa23e54f4ff726c336920243848caa206c0cc5ad3645adc1cbfaec98ba4bce7`

Size: **80,408,999 bytes**.

This PKG is **not Apple Developer ID Installer-signed or notarized**. Adobe CEP package signing and the RSA-signed update manifest are not substitutes for Apple's package-level trust. Do not disable macOS security protections to force an installation.

## Manual installation

1. Save projects; close After Effects, renders and connected MCP clients.
2. Download the exact linked package from the release page or use the opt-in beta panel to check, verify, download and show the installer in Finder on eligible older versions.
3. Open the PKG manually only if your macOS security policy permits it. Do not remove quarantine or bypass Gatekeeper.
4. Reopen After Effects and verify the AfterWIP extension and MCP connection.

The owner reports a successful manual 0.2.6 installation and panel launch on a Mac. This does not establish broad compatibility or prove the panel's end-to-end update download flow on older installations.

## Signed update channel

[channels/beta.json](channels/beta.json) has **sequence 3**, product version **0.2.6**, and expires **2026-11-14 18:47:32 UTC**. It is signed with the existing pinned RSA key `beta-2026-01`.

Windows update distribution is not yet public: Windows requires an approved Authenticode-signed EXE, publisher policy pins, and an authorized Windows manual manifest. The locally built Windows 0.2.6 EXE is a development/test installer, not a trusted updater release. Automatic installation remains disabled.

[All releases](https://github.com/artyns0/afterwip-releases/releases)
