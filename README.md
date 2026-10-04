# BakiBook
A Bangla customer credit ledger for small businesses. Built for Zahirul Islam's portfolio.

## Run
Open `index.html` in a modern browser. No build or external dependencies. For stable storage, use a local web server or GitHub Pages; file URL storage varies between browsers.

## Features
- Customer name, phone, address and search
- Credit and payment entry with date and description
- Outstanding balances and transaction history
- Integer paisa accounting and overpayment prevention
- Local browser storage; JSON backup and validated restore
- Printable customer statement / Save as PDF through the print dialog
- Responsive mobile layout

## GitHub upload
Keep your portfolio repository intact. Create a separate repository named `BakiBook`, upload the contents of this folder to its root, and enable GitHub Pages from the main branch root in repository Settings → Pages. Alternatively upload this folder as `bakibook/` inside your existing portfolio repository and link to `./bakibook/` from the portfolio. Never upload your customer backup JSON to GitHub.

## Important limits
Data belongs to the browser and origin used. No cloud synchronization, authentication, encryption, SMS sending, or multi-user support. Clearing site data removes records. Download backups regularly, especially before changing URL, browser or device. Restore replaces all current records after confirmation. Entries are immutable in this version; correction/deletion and customer editing are future work. Print produces a customer statement, not a numbered tax invoice. On a loaded page, calculations do not need internet; offline reload/install is not implemented.

## Suggested next commits
1. Customer editing and audited corrections
2. CSV export
3. Service worker for offline reload
4. English interface toggle
5. Explicitly shared payment reminders

## License
MIT — see LICENSE.
