# 🧾 Payo

**Split trip costs with just a link.** No server, no account, no app to install.

👉 **[Open Payo](https://alessiopin1997-ship-it.github.io/payo/)**

## The trick: the link *is* the database

Your whole trip (people, expenses, who owes whom) is compressed into the URL itself. Nothing is ever uploaded anywhere.

1. Create a trip and add what you paid.
2. **Copy link** and drop it in the group chat.
3. Friends open it, add their own expenses and send their link back.
4. Paste any link you get back. Payo **merges** everyone's edits, in any order, with no duplicates.

## What's inside

- 💸 **Fewest payments.** Settle-up works out the minimum number of transfers.
- 🧮 **Math in the amount field.** `3×14,50` or `120/4` both work.
- 📱 **QR code** so friends at the same table can just scan it.
- 💾 **Backup to a text file.** Drag it back onto the page to restore.
- 🌗 **Light and dark mode.** Works on iPhone, and you can add it to your Home Screen.
- ⌨️ **Keyboard shortcuts.** Press `?` in the app to see them.

## Under the hood

One `index.html` file, about 50 KB, with zero dependencies and zero network requests. The QR encoder is hand-written, and expenses are stored as whole cents. Every copy of a trip merges cleanly, because each change carries a timestamp and the newest one wins.

Download `index.html` and double-click it: Payo runs offline too.
