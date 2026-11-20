# RayuCode Releases

Official public binary releases and installers for **RayuCode CLI (v3+)** — the standalone Rust AI coding agent.

## Install

**macOS / Linux:**
```bash
curl -fsSL https://rayucode.com/install | bash
```

**Windows (PowerShell):**
```powershell
irm https://rayucode.com/install.ps1 | iex
```

## Updating

```bash
rayu update
```

## Legacy Node CLI (v2)

If you need the legacy Node/Bun CLI:
- macOS / Linux: `curl -fsSL https://rayucode.com/install-rayu-legacy.sh | bash`
- Windows: `irm https://rayucode.com/install-rayu-legacy.ps1 | iex`

## Verification

Every release includes a `SHA256SUMS` manifest. Both `install.sh` / `install.ps1` and `rayu update` verify SHA-256 checksums automatically before installing.

Documentation: <https://rayucode.com/docs>
