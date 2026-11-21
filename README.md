# ClientLedger Trial Balance

ClientLedger Trial Balance is a desktop app for CPAs: trial balances, book and
tax adjusting entries, bank import and reconciliation, tax codes, financial
statements, tax-software and Excel exports, workpaper packages, and easy backup
and restore. It runs on your own computer, for one practitioner, with no server
and no sign-in. All data stays on your computer, except what you choose to send
to an AI service.

This repository holds the releases (installers and checksums), the changelog
and the place to report problems. It does not hold source code.

## Download

The newest version is always at:

**https://github.com/KisaesDevLab/clientledger-tb-releases/releases/latest**

Download `ClientLedger-TB-Setup-x64.exe` (the installer) or
`ClientLedger-TB-windows-x64.zip` (a portable copy: unzip it and run
`clientledger-tb.exe` in the `ClientLedger Trial Balance` folder).

Every version, test versions (with a suffix such as `-beta.1`) included, is on
https://github.com/KisaesDevLab/clientledger-tb-releases/releases

## Requirements

- Windows 10 (22H2) or Windows 11, 64-bit (x64).
- No administrator rights: the installer installs for your Windows user only.

## Check the download

Each release has a `SHA256SUMS.txt`. In PowerShell, in the folder you
downloaded to:

```powershell
Get-FileHash .\ClientLedger-TB-Setup-x64.exe -Algorithm SHA256
```

The hash shown must match the line for that file in `SHA256SUMS.txt` (upper
or lower case letters do not matter).

## Windows SmartScreen warning

Beta builds are not code-signed yet, so Windows SmartScreen may say
"Windows protected your PC". Click **More info**, then **Run anyway**. Check
the download's SHA-256 first (above) to be sure the file is the one published
here.

## Your data

Installing, updating and uninstalling never touch your clients, documents,
backups or settings (kept in `%LOCALAPPDATA%\ClientLedgerTrialBalance`). Back
up before updating anyway: File > Back up now.

## Updates

The app does not check for updates on its own. Help > Check for updates opens
this repository's releases page in your browser.

## Report a problem

Open an issue: https://github.com/KisaesDevLab/clientledger-tb-releases/issues/new/choose

**Do not attach or paste client data, tax documents, company files, backups
(`.tbak`) or screenshots showing them.** Issues are public. For anything that
involves client data, email support@kisaes.com instead.

Security problems: see [SECURITY.md](SECURITY.md).

## Source code

Source code is available on request to licence holders (firms using an
official build of ClientLedger Trial Balance): email support@kisaes.com.

## Licence

See [LICENSE.md](LICENSE.md). The desktop app is under the MIT License; the
bundled engine is under the PolyForm Small Business License 1.0.0 with an
additional permission from Kisaes LLC for official builds.

Copyright 2025-2026 Kisaes LLC.
