# AfterWIP 1.0.2 — by Artyns

## Changes

- Improved account verification diagnostics across the panel and MCP bridge without logging API tokens or user sessions.
- Verified execution-permit lifetimes use monotonic request timing to reduce false expiry caused by a constant local clock offset. Signature, account/device binding and rollback protections remain enforced.
- Operations rejected before Adobe submission can close their quota reservation safely. Unknown execution outcomes remain counted and are not automatically refunded or replayed.
- Session fencing, token renewal and device authorization are preserved. Free remains 10 operations per server UTC day, Pro has no daily quota, and Beta Access stays independent.

## Validation and known limitations

Native packages for both platforms were built from the same source commit: `8c11a74c8ec47d75e62bb0b890858c849458637e`.

Completed checks: Windows 609 Node + 169 Python cases, macOS 654 Node + 373 Python cases, and 15 Chromium panel scenarios. Platform skips remain recorded separately. Adobe CEP publisher/timestamp verification, package inventories, SHA-256, and RSA-signed update manifests were verified.

**Real clean-install, native installer upgrade/rollback, Adobe panel/MCP end-to-end and Google login/logout acceptance tests for v1.0.2 were not completed. Publication proceeded at the owner's explicit request to skip the remaining tests.** Automated filesystem rollback checks passed; these are not evidence of an actual OS installer rollback. The original failure trigger on the unavailable second Windows computer remains unverified. Intel runtime is bundled; execution on a physical Intel Mac was not verified.

Windows EXE has no Authenticode publisher signature. macOS PKG has no Apple Developer ID signature or notarization. SmartScreen/Gatekeeper may show a warning. Adobe CEP signatures and update-manifest RSA signatures are separate and remain verified. Do not disable operating-system security protections.

Previous 1.0.1 installers remain available. No customer rights, license assignments, Billing Manager, Gumroad sales or purchases were changed for this release.

## Downloads and checksums

Download the installer matching your platform and compare it with `SHA256SUMS_1.0.2.txt` attached to the release. Update-channel/tag names are retained for compatibility with existing clients.
