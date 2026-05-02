# Ultimate Custom Tray

Adds your own icons to the system tray. Each icon can run an
action on left-click and/or show a context menu on right-click.

---
## Installation

1. Install [Windhawk](https://windhawk.net/).
2. Open **Windhawk** and go to **Explore** → **Search**.
3. Enter **Ultimate Custom Tray** in the search field.
4. In the results, select [Ultimate Custom Tray](https://windhawk.net/mods/ultimate-custom-tray).
5. Click the "Install" button.

---

## Quick start

1. Open Windhawk settings for this mod.
2. Add one or more **Items** to the list.
3. Fill in **Label**, **Icon** and **Action** for each item.
4. Save — the icons appear in the tray immediately.

---

## Action formats

Actions run on **left-click** (or from a context menu item).

| Prefix | Example | Description |
|--------|---------|-------------|
| `" "` | `"C:\Program Files\app.exe"` | Opens a file or folder by absolute path. |
| `~` | `~Downloads` | Opens a folder or file by name. |
| `cmd:` | `cmd:control` | Runs a command through `cmd.exe`. |
| `shell:` | `shell:shutdown /r /f /t 0` | Runs through `powershell.exe`. |
| `web:` | `web:https://windhawk.net/` | Opens a URL in the default browser. |
| `ms-settings:` | `ms-settings:bluetooth` | Opens a Windows Settings page. |

---

## Icon field

| Type | Example | Description |
|---|---|---|
| **Glyph** | `E774` | Hex code of a [Segoe Fluent Icons](https://learn.microsoft.com/en-us/windows/apps/design/iconography/segoe-ui-symbol-font) glyph. 4-digit hex only, no `\u` prefix. |
| **Image file** | `C:\Icons\name.png` | Full path to an image. Supported: `.png` `.ico` `.jpg` `.bmp`. Recommended: 32x32 px, transparent background. |

---

## Icon color

Use the **Icon color** setting to choose **White** (for dark taskbar) or **Black** (for light taskbar).

---

## Context menus

Each tray icon can show a right-click context menu.

- Add items under **Context menu** for the icon.
- Each item has its own **Name**, **Icon** and **Action**.
- If no items are defined, right-clicking does nothing.
- Left-click always runs the main **Action**, regardless of whether a context menu exists.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
