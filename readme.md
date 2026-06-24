# Trello Helper

> Focus your boards, filter your cards, and see the big picture — without leaving Trello.

<!-- Replace YOUR_STORE_LINK once the extension is published -->
<p>
  <a href="YOUR_STORE_LINK"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Install-4285F4?logo=googlechrome&logoColor=white" alt="Chrome Web Store"></a>
  <img src="https://img.shields.io/badge/version-1.0.0-blue" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/Manifest-V3-success" alt="Manifest V3">
  <img src="https://img.shields.io/badge/license-MIT-lightgrey" alt="License">
</p>

**Trello Helper** is a lightweight productivity extension that adds the board controls Trello is missing. Hide the lists you don't need, spotlight the ones you do, filter cards by name or custom field, and turn any board into instant charts — all without leaving the page. Everything runs locally in your browser and saves automatically per board.

---

## 📸 Screenshots

<!--
Add your screenshots here. Tip: drag images into the GitHub README editor,
or commit them to a /screenshots folder and reference them like below.
-->

| Hide & Highlight | Card Filter | Reports & Charts |
|---|---|---|
| ![Hide and highlight lists](screenshots/highlight.png) | ![Filter cards](screenshots/filter.png) | ![Reports](screenshots/report.png) |

---

## ✨ Features

### 🙈 Hide lists
Remove clutter by hiding entire lists from the board. Hidden lists take up no space — the remaining lists snap neatly to the left. Perfect for archiving "Done" columns or focusing on the work that matters today.

### 🔦 Highlight (focus) lists
Dim every list except the ones you care about so they stand out at a glance. Choose what to focus by:
- **Manual selection** — pick lists yourself
- **Keyword** — focus lists whose name matches one or more keywords
- **Card count** — e.g. show only lists with 5 or more cards

A live preview shows how many lists will be focused as you set the rule.

### 🔍 Card filter
A one-click **Filter** button right in the board header. Hide cards that don't match your conditions on **card name** or **custom field** (AND logic).
- Scope the filter to **only certain lists** — or **every list except a few**
- Optionally **search inside hidden lists** too, revealing any that contain a match

### 📊 Reports & charts
Visualize your board instantly with built-in charts — no external services:
- **Pie chart** of card count per list
- **Pie chart** of card distribution by any custom field value
- **Cumulative Flow Diagram (CFD)** built from automatic daily snapshots, so you can track how work flows over time

Exclude lists from any report by name rule or manual selection, and **scan the whole board** to include every card, not just the ones on screen.

### 🗂️ Card detail default
Open cards the way you like them. Automatically collapse a card to "Comments and activity" (or expand it to full details) every time you open one — your choice, set once in **Settings**. Manual toggles are always respected.

---

## 🚀 Getting started

1. Install **Trello Helper** from the [Chrome Web Store](YOUR_STORE_LINK).
2. Pin the Trello Helper icon and open any Trello board.
3. Click the extension icon to manage **Hide**, **Highlight**, and **Settings**.
4. Use the **Filter** and **Report** buttons in the board header for card filtering and charts.

> The extension only activates on Trello board pages (`https://trello.com/b/...`).

---

## 💡 Why you'll like it

- **Per-board settings** — every preference is remembered independently for each board
- **Fast & flicker-free** — hidden lists never flash on reload
- **Works with Trello's dynamic interface** — re-applies automatically as the board updates
- **No account, no sign-up, no tracking**

---

## 🔒 Privacy

Trello Helper does **not** collect, transmit, or sell any data. All your settings are stored locally in your browser using Chrome storage and never leave your device. The extension only runs on `trello.com` board pages.

---

## 🗺️ Roadmap

- [x] Hide lists (no layout gap)
- [x] Highlight lists — manual / keyword / card-count rules
- [x] Card filter — by name & custom field, with list scoping
- [x] Reports — per-list pie, custom-field pie, Cumulative Flow Diagram
- [x] Card detail default (auto hide/show on open)
- [ ] Border / outline color per list
- [ ] More features — suggestions welcome!

Have an idea? [Open an issue](../../issues) and let me know.

---

## 🐞 Support & feedback

Found a bug or have a feature request? Please [open an issue](../../issues) — it's the fastest way to get help and helps other users too.

---

## 📄 License

Released under the [MIT License](LICENSE).

---

<sub>Trello is a trademark of Atlassian. This extension is an independent project and is not affiliated with, endorsed by, or sponsored by Atlassian.</sub>
