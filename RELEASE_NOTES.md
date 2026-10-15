# AfterWIP 0.2.5 Beta — Release Notes

**Published:** October 13, 2026  
**Channel:** macOS beta  
**Platforms:** macOS (Apple Silicon / Intel), universal package  
**Installation:** Manual only

## About this beta

AfterWIP is an Adobe After Effects companion with MCP connectivity for supported AI clients. This release is intended for controlled beta evaluation and for eligible manual upgrades to version 0.2.5.

The opt-in macOS beta update flow checks an RSA-SHA256-signed manifest, verifies the package URL, size and SHA-256 digest, and reveals the verified package in Finder. **It does not install automatically.**

### Before installing

1. Save your projects and quit After Effects, render jobs, and active AfterWIP MCP clients.
2. Obtain the macOS package from the [0.2.5 Beta release](https://github.com/artyns0/afterwip-releases/releases/tag/v0.2.5-beta).
3. Confirm the release asset matches the signed [beta channel manifest](channels/beta.json).
4. Open the package manually only if your Mac permits it under its security settings.
5. Relaunch After Effects and verify the AfterWIP extension and MCP connection.

**Security notice:** This `.pkg` is **not signed with an Apple Developer ID Installer certificate and is not notarized**. Apple Gatekeeper may refuse it. Do not bypass or disable system-wide security controls. Adobe CEP verification evidence and the RSA-signed update manifest are distinct from Apple's package trust requirements.

**Test status:** The update and rollback mechanisms have regression coverage, but end-to-end installation, CEP loading and client behavior across real Mac models and macOS releases are not fully certified. Keep installation backups and evaluate beta changes on a test Mac.

## Availability

- **macOS:** 0.2.5 Beta `.pkg` is publicly downloadable.
- **Windows:** No public Windows update installer or update manifest in this channel yet. Windows unattended installation remains disabled.
- **Stable:** No production stable release/update channel has been published.

## Immutable release information

Published artifact: `AfterWIP-0.2.5-5822adacfc89973044e3cea891e7f8f4eb6b4e3725e2e32dcf7e19bbf8252ae5-macOS-universal.pkg`

SHA-256: `5822adacfc89973044e3cea891e7f8f4eb6b4e3725e2e32dcf7e19bbf8252ae5`

Size: `80,275,250` bytes

The signed beta channel pointer was safely renewed to **sequence 2** on October 15, 2026, with an expiry of **2026-11-14 13:41:07 UTC**. The immutable 0.2.5 package asset has not changed, and sequence renewal does not represent a new application version. After expiry, update checks require another correctly signed, higher-sequence manifest; do not modify the signed payload without authorization.

[All releases](https://github.com/artyns0/afterwip-releases/releases)
