# AfterWIP 0.3.3 beta

Windows manual updates now validate native directory attributes when walking
cache ancestors. PowerShell's provider-only `PSIsContainer` property disappears
on `DirectoryInfo.Parent`; this previously rejected safe profile ancestors after
UAC was restored. Normal-user, ownership, protected ACL and reparse-point checks
remain mandatory. The error for an elevated token now explains how to use a
normal user session without exposing private helper output.

The connection card recognizes the exact MCP initialize name `codex-mcp-client`,
which [Codex reports in its own source](https://github.com/openai/codex/blob/main/codex-rs/codex-mcp/src/rmcp_client.rs).
The transport continues sending that original name. Technical provider and lease
counts remain Codex; only the card displays ChatGPT with the existing local SVG.
Missing, unrecognized and substring-only names remain generic. Client labels
are authenticated self-reported metadata, not provider attestation.

Install manually after saving work and quitting After Effects/MCP. Windows EXE
is an Authenticode-unsigned Developer Beta. macOS universal PKG has no Apple
Developer ID signature or notarization. Adobe CEP signatures and RSA update
metadata are separate checks; Windows/macOS protections remain enabled.
No installer is launched by checking or downloading an update.

Validation: Windows 515 PASS / 54 SKIP; macOS 648 PASS / 11 SKIP; 15 Chromium scenarios PASS. Exact package inventories, Adobe and secret checks PASS. Live Adobe loading/install and Intel execution NOT RUN.
