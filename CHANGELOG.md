# Changelog

What changed in each version of ClientLedger Trial Balance, newest first.
Versions with a suffix such as `-beta.1` are test versions (GitHub
pre-releases).

## 0.1.0

First release (an early version for testing), Windows x64 only.

- Clients and periods: roll forward into the next year (carry balances or
  close income to retained earnings, recurring entries, W/P references),
  edit, lock and unlock a period; deleting a period or a client asks you to
  type its name and backs up everything first.
- Trial balances with book and tax adjusting entries, prior-year comparison,
  a flux flag column, lead sheets, W/P references, tickmarks and notes, and
  Export to Excel.
- Chart of accounts: add, change and remove accounts (removed accounts are
  kept and can be brought back), change many at once, import a chart from
  CSV or Excel, copy from another client, units and tickmarks.
- Compare the open period with any other period of the client, and a
  general ledger with running balances, both exportable.
- Bank transactions: import OFX, QFX, QBO, QIF and CSV files (and PDF
  statements read by AI, when you ask), payee rules and payee memory, key in
  checks and deposits by hand, read a scanned sheet, classify, and
  reconcile.
- Tax codes for UltraTax CS, CCH Axcess, Lacerte, GoSystem Tax RS and a
  generic export; M-1 adjustments and their workbooks.
- Financial statements and reports as PDF, the Statement Writer, workpaper
  packages with all fifteen statements and reports, documents and
  checklists.
- A ten-key adding-machine tape beside every PDF: key in amounts or pick
  them from the page, check a total, keep the tape with the period.
- Stamp tickmarks and notes onto attached PDFs.
- Chart of accounts templates, the program's and your firm's, all editable.
- AI review and the assistant with your own Anthropic key, a local Ollama or
  an OpenAI-compatible server; Claude Desktop and other MCP apps can work in
  the app (never deleting a client or period, never your settings).
- Firm server (off unless you turn it on): open a period from your firm's
  Vibe Trial Balance server, work offline, and send it back.
- Backup and restore: on close and daily, a second copy folder (OneDrive,
  Dropbox, USB), optional passphrase, a restore wizard, and moving to a new
  computer.
- Help > Check for updates opens this releases page; the app makes no update
  check of its own.
