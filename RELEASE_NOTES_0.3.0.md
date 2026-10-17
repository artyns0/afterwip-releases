# AfterWIP 0.3.0 — Smart Connection Beta

The connection card keeps the existing purple/blue design and approved AfterWIP logo. It now focuses on the actual AI connection, with local ChatGPT/Claude marks and a neutral mark for listening or multiple clients. Technical address and project details move to Settings; redundant bridge-active/Local Only badges are removed.

Authenticated MCP leases expire after 65 seconds and renew every 20 seconds. Provider names remain client-reported labels, not cryptographic provider identities. An owned healthy listener can survive short panel reloads; unexpected loss uses bounded exponential backoff. Other open panels can observe authenticated read-only status without taking over the listener. Occupied foreign ports remain untouched, and no write/tool call is replayed.

Safe Mode, token/localhost authorization, 50 tools/34 write functions, Settings/Updates/Activity Log, RSA/Adobe pins and disabled production gates are preserved.

## Test results

| Qualification | Result |
| --- | --- |
| Windows Node/Python suites | 496 PASS / 0 FAIL / 48 SKIP |
| macOS Node/Python suites | 625 PASS / 0 FAIL / 9 SKIP |
| Responsive Chromium adapter scenarios (260/320/400/480/520px, 2x) | 15 PASS |
| Node 17 compatibility checks | 4 PASS |
| Native Windows build and separate Adobe CEP flavors | PASS |
| Native Universal Mac PKG; arm64 runtime/MCP metadata (50 tools/23 prompts) | PASS |
| Independently extracted final EXE/PKG exact inventory/modes, hashes, Adobe signatures, secrets/content audits | PASS; 277 EXE files / 175 PKG files |
| Intel runtime archive and Mach-O architecture | PASS; execution NOT RUN |
| Live After Effects first launch, native CEP close/reopen and actual install/upgrade | NOT RUN |

The same committed application source produced both packages. Browser adapters and portable model tests do not claim live Adobe or Windows SCM/security deployment validation.

## Manual beta installation

Windows EXE is an **Authenticode-unsigned Developer TEST BUILD**. macOS PKG is **Apple Developer ID unsigned and not notarized**. Adobe CEP signing and RSA metadata verification do not replace OS publisher signing. Keep SmartScreen, Gatekeeper and other OS protections enabled.

Use Updates to check/download on an eligible beta channel, then install manually. Save projects and quit After Effects, render jobs and active MCP clients first. No automatic installation or production gate enablement is included.

## Downloads and SHA-256

[AfterWIP 0.3.0 - Windows Developer Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.0-windows-dev-beta/AfterWIP-0.3.0-b9d42125c38c01dddfc90e1801637c2fda8d562e8befa5ecca48160851c3d481-win-x64.exe)

`b9d42125c38c01dddfc90e1801637c2fda8d562e8befa5ecca48160851c3d481` — 48654827 bytes

[AfterWIP 0.3.0 - macOS Universal Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.0-beta/AfterWIP-0.3.0-a847964c7eb287c0476391439c5e2d2f0d73444ead4dca3d3ea55a6fb51238c3-macOS-universal.pkg)

`a847964c7eb287c0476391439c5e2d2f0d73444ead4dca3d3ea55a6fb51238c3` — 80738298 bytes

## Signed update channels

macOS beta sequence **6**, Windows Developer Beta sequence **3**; RSA key ID `beta-2026-01`. Expires **2026-11-17 22:58:35 UTC** (2026-11-18 01:58:35 Türkiye time). A renewal requires a higher sequence and a new RSA signature. Existing 31-day client policy is unchanged.

Release assets contain installers and checksums only. This public repository and its source archives contain public metadata/approved brand assets; private Git history and private signing material are excluded. Packaged runtime JavaScript and original MIT notices remain part of the application.
