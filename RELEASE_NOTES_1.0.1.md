# AfterWIP 1.0.1 — by Artyns

## Fixed

- **Windows installation on a fresh PC.** On Windows' default PowerShell
  policy (Restricted), setup stopped with "preflight stopped" and sign-in,
  update checks and upgrades could fail. AfterWIP now runs its own bundled
  scripts for that process only; your computer's policy is not changed.
- If setup cannot continue, it now shows the reason.
- The Updates window says "AfterWIP is up to date" when no newer version is
  published, instead of reporting a failure.

Existing 1.0.0 installations can update from the panel's Updates menu.

## Checksums

See [SHA256SUMS_1.0.1.txt](SHA256SUMS_1.0.1.txt).
