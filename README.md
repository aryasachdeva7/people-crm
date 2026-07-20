# 🧠 People — Personal CRM

A personal CRM for remembering people you meet. No accounts, no servers, no subscriptions. Just open the file and start adding people.

Built as a single self-contained HTML file that runs entirely in your browser.

---
https://aryasachdeva7.github.io/people-crm/people-crm-arya.html
## What it does

Whenever you meet someone new, open the app, add them in under 15 seconds, and find them again later. That's it.

This is **not** a business CRM. It's a personal memory tool, like a digital notebook for people.

---

## Features

- **Add people fast:** Name, what they do, where you met, what you liked about them, notes
- **Instant search:** Searches across name, role, where you met, notes, and liked
- **Sort** by Recently Added, Name, or Last Interaction
- **Interaction log:** Log coffee, calls, dinners, events, follow-ups with a date and note
- **Reminders:** Set follow-up reminders with quick presets (Follow up, Check in, Next month, In 3 months)
- **Dark and light mode:** Follows your system preference, toggleable anytime
- **Keyboard shortcuts:** `Ctrl+K` to add, `/` to search, `Escape` to close
- **Your photo:** Click the avatar in the top-left to set your own profile picture
- **All data stays local:** Saves in your browser's localStorage, nothing goes to any server

---

## How to use

### Option 1 - Open directly
Download `people-crm-arya.html` and double-click it. Opens in any browser. Done.

### Option 2 - GitHub Pages (live URL)
If you've forked or cloned this repo:

1. Go to your repo **Settings > Pages**
2. Set source to **main** branch > **/ (root)**
3. Save. Your app will be live in ~60 seconds at:

```
https://YOUR-USERNAME.github.io/people-crm/people-crm-arya.html
```

---

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + K` | Add a new person |
| `/` | Focus search |
| `Ctrl + Enter` | Save (inside add form) |
| `Escape` | Close panel / modal |

---

## Data and privacy

All data is stored in your **browser's localStorage** and never leaves your device. No backend, no database, no cloud sync.

> ⚠️ Clearing your browser data will erase your people. If you want a backup, keep the file on a cloud drive like Google Drive or iCloud.

---

## Tech

No frameworks. No build step. No dependencies.

- Plain HTML, CSS, and vanilla JavaScript
- All in a single `.html` file (~48KB)
- Works in Chrome, Edge, Firefox, Safari

---

## Customisation

Want to change the name or accent colour? Open the file in any text editor and search for:

- `Arya Sachdeva` to update the owner name
- `#B8845A` to change the accent colour (warm brown by default)

---
