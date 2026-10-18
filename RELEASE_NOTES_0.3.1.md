# AfterWIP 0.3.1 — Connection Bugfix Beta

Fixes the Refresh/port conflict race, Node-owned listener cleanup and a late aborted-probe race. Technical MCP leases are grouped by reported client label: multiple Codex sessions show Connected to Codex, with separate session counts in Settings. Names are self-reported, not cryptographic provider identities. Retry is bounded, unknown processes stay untouched and no tool/write is replayed.

Existing 0.3.0 artwork, features, 50 tools/34 writes, Safe Mode, RSA/Adobe pins and disabled production gates remain.

Tests: Windows **507 PASS / 50 SKIP**, Mac **638 PASS / 9 SKIP**, zero failures. Includes 24 connection tests and 0.3.0 upgrade/reinstall-refusal/rollback fixtures. 15 responsive cases, four Node17 checks and native Mac Node24 socket/runtime checks PASS. Final installer inventories/hashes, Adobe CEP publisher/timestamp and secret-content audits PASS.

Windows is **Authenticode-unsigned Developer TEST BUILD**. Mac Universal PKG is **Apple Developer ID unsigned / unnotarized beta**. Adobe/RSA checks do not replace OS signing. Keep OS protections enabled. Download through Updates, save projects, quit AE/render jobs/MCP clients, then install manually; no automatic installation.

Live native Adobe refresh and actual installation/upgrade: **NOT RUN**. Mac arm64 runtime smoke PASS; Intel archive/Mach-O PASS, execution NOT RUN.

[AfterWIP 0.3.1 - Windows Developer Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.1-windows-dev-beta/AfterWIP-0.3.1-c1b6e93dbead5f6088d8fb976c3da9cdbf4957e1b4b9bfd87cb0a0e27611fc3f-win-x64.exe) — 48666343 bytes.
SHA-256: `c1b6e93dbead5f6088d8fb976c3da9cdbf4957e1b4b9bfd87cb0a0e27611fc3f`

[AfterWIP 0.3.1 - macOS Universal Beta](https://github.com/artyns0/afterwip-releases/releases/download/v0.3.1-beta/AfterWIP-0.3.1-2a05b764e2ce6b19c1c4da36d89841da0e2887178da74af0a8ebe5c8b08f1fa7-macOS-universal.pkg) — 80744361 bytes.
SHA-256: `2a05b764e2ce6b19c1c4da36d89841da0e2887178da74af0a8ebe5c8b08f1fa7`

RSA channels: Mac **7**, Windows Developer **4**; expiry **2026-11-18 10:05:49 UTC**. Only installer/checksums are release assets. Public source archives contain public metadata, not private application history or signing material.
