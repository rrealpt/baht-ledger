# Baht Ledger

A personal expense tracker in Thai Baht. It runs in the browser and saves to your own Google Sheet through your Google sign-in.

## Files

- `index.html`: the whole app
- `config.js`: your Google OAuth Client ID (not a secret)
- `manifest.webmanifest`, `icon-*.png`: name and icon for the iPhone Home Screen

## Where data lives

- Entries: your Google Sheet (tabs Transactions, Planned, Settings, Monthly summary)
- Sheet link, sign-in token, offline copy: this phone's browser only
- Nothing is stored in this repository
