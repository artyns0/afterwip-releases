# AfterWIP 0.3.2 — Connection Bugfix Beta

Codex and ChatGPT display Connected to ChatGPT using the existing local ChatGPT SVG. Claude, unknown-client and disconnected states keep their appropriate existing icons/status. Only the UI display changes; technical Codex labels, signed status and session counts remain intact. Names are self-reported, not cryptographic provider identities. Retry is bounded, unknown processes stay untouched and no tool/write is replayed.

Existing 0.3.1 artwork, features, 50 tools/34 writes, Safe Mode, RSA/Adobe pins and disabled production gates remain.

Tests: Windows **508 PASS / 52 SKIP**, Mac **641 PASS / 9 SKIP**, zero failures. Includes 24 connection tests and 0.3.1 upgrade/reinstall-refusal/rollback fixtures. 15 responsive cases, four Node17 checks and native Mac Node24 socket/runtime checks PASS. Final installer inventories/hashes, Adobe CEP publisher/timestamp and secret-content audits PASS.

Windows is **Authenticode-unsigned Developer TEST BUILD**. Mac Universal PKG is **Apple Developer ID unsigned / unnotarized beta**. Adobe/RSA checks do not replace OS signing. Keep OS protections enabled. Download through Updates, save projects, quit AE/render jobs/MCP clients, then install manually; no automatic installation.

Live native Adobe refresh and actual installation/upgrade: **NOT RUN**. Mac arm64 runtime smoke PASS; Intel archive/Mach-O PASS, execution NOT RUN.

[AfterWIP 0.3.2 - Windows Developer Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.2-windows-dev-beta/AfterWIP-0.3.2-0735f0fcb3102779cb0d966ac0920adea4def0ae4bb3337706a1651a11e3de35-win-x64.exe) — 48659292 bytes.
SHA-256: `0735f0fcb3102779cb0d966ac0920adea4def0ae4bb3337706a1651a11e3de35`

[AfterWIP 0.3.2 - macOS Universal Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.2-beta/AfterWIP-0.3.2-c4608dcd9107dd0f84698a216674f164bfa482317f30eec2536eacee2690652a-macOS-universal.pkg) — 80744356 bytes.
SHA-256: `c4608dcd9107dd0f84698a216674f164bfa482317f30eec2536eacee2690652a`

RSA channels: Mac **8**, Windows Developer **5**; expiry **2026-11-18 12:07:10 UTC**. Only installer/checksums are release assets. Public source archives contain public metadata, not private application history or signing material.
