# AfterWIP 1.0.3 — by Artyns

Security update.

## Changes

- `ae_batch` no longer runs `ae_run_jsx` or `ae_menu_command` steps. Raw ExtendScript and menu commands must be called directly, so the panel's "Allow raw ExtendScript and menu commands" switch always applies to them. Before this fix a batch could run raw ExtendScript (which can reach `system.callSystem`) even with the switch off.
- No other behaviour changes. Direct `ae_run_jsx` / `ae_menu_command` calls, skills and ordinary batches work as in 1.0.2. Account, quota, update key and channel rules are unchanged.

## Validation and known limitations

Native packages for both platforms were built from the same source commit: `ceb40a122efe4ca7fe49d959d9c8824cbe4aae55`.

Completed checks: Windows 312 Node + 179 Python cases and macOS 363 Node + 373 Python cases passed with no failures; platform skips remain recorded separately. The Windows installer was unpacked without running it: its 190 application and 100 CEP files match the build inventory, the bundled MCP server reports version 1.0.3 with 50 tools, and the fixed files are the ones shipped. Adobe CEP publisher/timestamp verification, SHA-256 and RSA-signed update manifests were verified; the signed manifests were accepted by the existing update verifier when moving from 1.0.2.

**Real clean-install, native installer upgrade/rollback, Adobe panel/MCP end-to-end and Google login/logout acceptance tests for v1.0.3 were not run, as for 1.0.2.** Intel runtime is bundled; execution on a physical Intel Mac was not verified.

Windows EXE has no Authenticode publisher signature. macOS PKG has no Apple Developer ID signature or notarization. SmartScreen/Gatekeeper may show a warning. Adobe CEP signatures and update-manifest RSA signatures are separate and remain verified. Do not disable operating-system security protections.

Previous 1.0.2 installers remain available. No customer rights, license assignments, Billing Manager, Gumroad sales or purchases were changed for this release.

## Downloads and checksums

Download the installer matching your platform and compare it with `SHA256SUMS_1.0.3.txt` attached to the release. Update-channel/tag names are retained for compatibility with existing clients.
