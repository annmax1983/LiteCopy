# LiteCopy

English | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

A lightweight browser extension that removes copy restrictions, unblocks right-click, and unlocks text selection on any website.

> Chromium-based · Manifest V3 · Minimal Permissions · 100% Local

---

## Why LiteCopy?

Ever tried to copy text from a website but couldn't select it, right-click was blocked, or Ctrl+C did nothing? LiteCopy fixes all of that with one click.

| Advantage | Detail |
|-----------|--------|
| 🔓 **One-Click Unlock** | Remove all copy/select restrictions instantly — no page refresh needed |
| 🔒 **Minimal Permissions** | Only `activeTab` + `scripting` — no unnecessary access |
| ⚡ **Lightweight** | Under 15KB source, 10KB packaged. No frameworks, no dependencies |
| 🌍 **6 Languages** | English, Chinese, Spanish, German, Japanese, French |
| 🚫 **Zero Tracking** | No analytics, no network requests, no data upload |
| 🎯 **Simple Toggle** | Click icon to enable/disable, clear ON/OFF state indicator |

---

## Features

| Feature | Description |
|---------|-------------|
| 🔓 **Remove CSS Restrictions** | Overrides `user-select:none` and `-webkit-user-select:none` |
| 🖱️ **Unblock Right-Click** | Restores context menu on sites that block it |
| ⌨️ **Unblock Shortcuts** | Restores Ctrl+C, Ctrl+V, Ctrl+A and other copy/paste keys |
| 🛡️ **Remove Overlays** | Disables transparent overlay divs that block text selection |
| 🔄 **Toggle ON/OFF** | Click toolbar icon to enable/disable, page reloads when disabled |
| 💬 **Toast Notification** | Auto-dismissing notification shows activation status |
| 📋 **Copy Page Info** | Popup buttons to copy page title, URL, or both |

---

## Preview

<p align="center">
  <img src="icons/icon128.png" alt="LiteCopy Icon" width="80">
</p>

---

## Supported Browsers

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Fully supported |
| Microsoft Edge | ✅ Fully supported |
| Other Chromium-based browsers | ✅ Should work |

---

## Installation

1. Open your browser's extension page:
   - **Chrome**: `chrome://extensions/`
   - **Edge**: `edge://extensions/`
2. Enable **Developer mode** (top-right toggle)
3. Click **Load unpacked** and select the `lite-copy` folder
4. The LiteCopy icon appears in your toolbar

---

## Usage

1. Visit any website that blocks copying or text selection
2. Click the **LiteCopy** icon in your toolbar
3. All restrictions are removed instantly
4. Click the icon again to disable (page reloads to restore original behavior)

**Copy Page Info:**
- Click the icon → popup opens
- Use buttons to copy page title, URL, or both

---

## Privacy

- ✅ **Zero data upload** — All processing happens locally
- ✅ **No analytics** — No tracking, no telemetry
- ✅ **No network requests** — Extension works completely offline
- ✅ **Minimal permissions** — Only `activeTab` + `scripting`
- ✅ **No site memory** — No blacklist/whitelist, no site preferences stored

---

## License

Copyright © 2026 LiteCopy. All rights reserved.

---

## ❤️ Support

If you find LiteCopy helpful, consider supporting the project!

**[👉 Click here to support](https://annmax1983.github.io/LiteCopy/)**

---

> **Note:** This repository is for **project showcase purposes only**. It does not contain the full source code, manifest, icons, or build scripts. Full source code will **not** be published here.
