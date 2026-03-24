# 🔮 Ishiguro's Vault

> *"Insignificant creatures... at least your data is organized."*

A personal all-in-one dashboard inspired by **The Herta** from Honkai: Star Rail. Track your savings, manage your game and social accounts, and keep everything in one place — no server, no database, no nonsense. Just open the file and it works.

---

## ✨ Features

- **💰 Savings Counter** — Track your PHP balance with add/subtract operations. Integers only (as it should be). Includes a full transaction log.
- **🗂️ The Vault** — A scattered-button gallery of all your apps and accounts. Click any to view your stored info.
- **📋 App Detail Views** — Each app has a tailored display:
  - *Payment apps* (GCash, BDO) → QR code image + account number
  - *Social profiles* (Roblox, Discord, Steam) → Profile screenshot + clickable profile link
  - *Game accounts* (Wuthering Waves, PGR, MLBB, etc.) → UID, server/region, and a showcase image grid
  - *Custom entries* → Freeform label/value fields
- **⚙️ Full CRUD** — Add, rename, edit, and delete any entry from the Manage page. No touching the code.
- **📷 Quick Icon Upload** — Hover over any app icon and click 📷 to swap in your own image instantly.
- **💾 Manual Save + Page Persistence** — Hit the Save button to write everything to localStorage. Refreshing the page brings you back to wherever you were.
- **🖼️ Custom Background** — Set your own background image via the Set BG button (bottom-right corner).
- **🎨 Herta-themed UI** — Deep purples, gold accents, blurred background on navigation, starfield overlay.

---

## 🚀 Setup

No installation. No npm. No backend. Truly zero dependencies (besides a Google Fonts CDN call for typography).

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/herta-vault.git
   ```
2. **Open** `herta-dashboard.html` in any modern browser
3. That's it. You're in.

> **First time?** Click **🖼️ Set BG** in the bottom-right corner to upload your background image (the Herta library wallpaper works great). All data saves to your browser's `localStorage` automatically when you hit 💾 Save.

---

## 📸 Screenshots

> *(Add your own screenshots here — main menu, vault page, a detail view, etc.)*

| Main Menu | The Vault | Savings Counter |
|-----------|-----------|-----------------|
| ![main](screenshots/main.png) | ![vault](screenshots/vault.png) | ![savings](screenshots/savings.png) |

---

## 🛠️ Tech Stack & Notes

| Thing | What it is |
|-------|-----------|
| **Structure** | Single `.html` file — HTML, CSS, and JS all in one |
| **Styling** | Vanilla CSS with custom properties (no Tailwind, no frameworks) |
| **Logic** | Vanilla JavaScript — no libraries, no bundler |
| **Fonts** | Cinzel Decorative, Crimson Pro, Rajdhani via Google Fonts |
| **Storage** | Browser `localStorage` — data lives in your browser, stays offline |
| **Images** | Converted to base64 and stored in localStorage |
| **Backend** | None. Intentionally. |

### ⚠️ A few things to know

- **Data is local** — Everything is stored in your browser's `localStorage`. Clearing browser data will wipe it. If you want backups, export isn't built in yet — just don't clear your site data.
- **Image storage** — Uploading lots of large images may approach localStorage limits (~5MB). Resize images before uploading if you run into issues.
- **Single user** — This is built as a personal tool. There's no auth, no accounts, no sync across devices.

---

## 📁 File Structure

```
herta-vault/
├── herta-dashboard.html   # The entire app lives here
├── README.md
└── screenshots/           # Add your own screenshots here
    ├── main.png
    ├── vault.png
    └── savings.png
```

---

## 🌸 Credits

- Inspired by **The Herta** — Honkai: Star Rail (HoYoverse)
- Background art: The Herta's library wallpaper (HoYoverse)
- Built for personal use, shared for fun

---

*Made with 💜 and an unreasonable amount of purple.*
