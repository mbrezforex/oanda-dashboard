# Test-C Generation 2 Prop Dashboard

PowerShell-driven, mobile-friendly, read-only dashboard for the OANDA practice bot.

## Generate data
```powershell
.\Export-TestCDashboard.ps1
```

## Preview
```powershell
.\Preview-TestCDashboard.ps1
```

## Publish to GitHub
Initialize this folder as a Git repository, push it to GitHub, then set GitHub Pages to deploy from `/docs`. After that:
```powershell
.\Publish-TestCDashboard.ps1
```

The exporter reads the bot's existing `config\.env` but never writes the OANDA API token or full account ID into `docs/data/dashboard.json`.
