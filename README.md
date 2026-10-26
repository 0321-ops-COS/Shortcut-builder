# Shortcut Builder

**Open the page:** https://0321-ops-cos.github.io/Shortcut-builder/

Shortcut Builder is a mobile-friendly guide for building, checking, and tracking the actions in your iOS Shortcuts. It currently focuses on the **DoorDash Offer Analyzer v2** and **Shift Logging** shortcuts.

## What it does

- One combined app: a color-coded blueprint (green = add, amber = change, red = remove) with a **Whole shortcut** view, section chips to jump between steps, and an **Edits to make** view. Only colored rows have a checkbox.
- Drop in a `.shortcut` file (unsigned or binary plist) to get its full action list. Signed exports are detected and explained.
- One library page: type a name, drop a file (optional), and tap Create blueprint. There is no separate import page.
- Blueprints can be deleted, so the old example is gone.
- Breaks each shortcut into sections and individual actions, with notes on what to add, rename, fix, or remove.
- Tracks completed steps and bookmarks so you can pick up where you left off.
- Includes checks for common setup issues and guidance for testing the shortcuts.
- Provides a handoff/export view so you can copy or save progress and share it with an AI assistant, then apply returned progress.

The page is a companion checklist and troubleshooting guide; it does not automatically install or edit shortcuts on your iPhone. Follow the instructions in Shortcuts to make the changes.

## Repository files

- [`index.html`](https://github.com/0321-ops-COS/Shortcut-builder/blob/main/index.html) — main Shortcut Blueprint Builder app.
- [`doordash-offer-analyzer-v2.html`](https://github.com/0321-ops-COS/Shortcut-builder/blob/main/doordash-offer-analyzer-v2.html) — standalone DoorDash Offer Analyzer v2 guide.
- [`manifest.webmanifest`](https://github.com/0321-ops-COS/Shortcut-builder/blob/main/manifest.webmanifest) — web app manifest.
- `icon-180.png`, `icon-192.png`, and `icon-512.png` — app icons.
