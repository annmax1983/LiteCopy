# LiteCopy

English | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

A lightweight browser extension that restores native text selection, right-click menu, and copy shortcuts on any website.

> Chromium-based · Manifest V3 · Minimal Permissions · Local Only

---

## Why LiteCopy?

Ever tried to copy text from a website but couldn't select it, right-click was blocked, or Ctrl+C did nothing? LiteCopy fixes all of that with one click.

| Advantage | Detail |
|-----------|--------|
| 🔓 **One-Click Activate** | Restore native text selection instantly — no page refresh needed |
| 🔒 **Minimal Permissions** | Only `activeTab` + `scripting` — no unnecessary access |
| ⚡ **Lightweight** | Under 15KB source, 10KB packaged. No frameworks, no dependencies |
| 🌍 **6 Languages** | English, Chinese, Spanish, German, Japanese, French |
| 🚫 **No Tracking** | No analytics, no network requests, no data upload |
| 🎯 **Simple Toggle** | Click icon to enable/disable, clear ON/OFF state indicator |

---

## Features

| Feature | Description |
|---------|-------------|
| 🔓 **Restore Text Selection** | Restores default text selection on sites that disable it |
| 🖱️ **Restore Right-Click Menu** | Recovers browser right-click menu on restricted sites |
| ⌨️ **Restore Keyboard Shortcuts** | Recovers Ctrl+C, Ctrl+V, Ctrl+A and other standard shortcuts |
| 🛡️ **Fix Overlay Interference** | Fixes transparent overlay divs that interfere with text selection |
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
3. Text selection is restored instantly
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

## Copyright Disclaimer

This tool only restores basic browser built-in text operation capabilities for users' personal learning, reference and offline reading. All text, pictures and content copyright of the website belong to the original author and website operator. Users shall not use this tool for commercial reproduction, mass crawling, content reprinting and other copyright-infringing behaviors. All legal liabilities arising from improper use shall be borne solely by the user.

---

## License

Copyright © 2026 LiteCopy. All rights reserved.

---

## ❤️ Support

If you find LiteCopy helpful, consider supporting the project!

**[👉 Click here to support](https://annmax1983.github.io/LiteCopy/)**

---

> **Note:** This repository is for **project showcase purposes only**. It does not contain the full source code, manifest, icons, or build scripts. Full source code will **not** be published here.
