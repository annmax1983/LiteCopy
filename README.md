# LiteCopy

English | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

A lightweight browser extension that restores native text selection, right-click menu, and copy shortcuts on any website.

> Chromium-based · Manifest V3 · Minimal Permissions · Free + Premium tiers

---

## Why LiteCopy?

Ever tried to copy text from a website but couldn't select it, right-click was blocked, or Ctrl+C did nothing? LiteCopy fixes all of that with one click.

| Advantage | Detail |
|-----------|--------|
| 🔓 **One-Click Activate** | Restore native text selection instantly — no page refresh needed |
| 🔒 **Minimal Permissions** | `activeTab` + `scripting` + `storage` — nothing beyond what the feature needs |
| ⚡ **Lightweight** | No frameworks, no runtime dependencies |
| 🌍 **6 Languages** | English, Chinese, Spanish, German, Japanese, French |
| 🚫 **No Tracking** | No analytics, no telemetry. Free tier sends zero data; Premium activation verifies only a device ID + your key against api.annmax1983.com |
| 🎯 **Simple Toggle** | Open the popup and hit Enable/Disable — clear ON/OFF state indicator |

---

## Features

### 🆓 Free (100 unlocks/day)

| Feature | Description |
|---------|-------------|
| 🔓 **Restore Text Selection** | Restores default text selection on sites that disable it |
| 🖱️ **Restore Right-Click Menu** | Recovers browser right-click menu on restricted sites |
| ⌨️ **Restore Keyboard Shortcuts** | Recovers Ctrl+C, Ctrl+V, Ctrl+A and other standard shortcuts |
| 🛡️ **Fix Overlay Interference** | Fixes transparent overlay divs that interfere with text selection |
| 🔄 **Toggle ON/OFF** | Enable/Disable from the popup, page reloads when disabled |
| 💬 **Toast Notification** | Auto-dismissing notification shows activation status |
| 📋 **Copy Page Info** | Popup buttons to copy page title, URL, or both |

> **Free tier limit:** 100 site unlocks per day. The counter resets at midnight (local time). Copy Page Info buttons (title/URL) are always free and do not count toward the limit.

### ⭐ Premium (License Required — Unlimited)

| Feature | Description |
|---------|-------------|
| ♾️ **Unlimited Unlocks** | No daily limit — enable on as many sites as you want |
| 📤 **Export/Import Settings** | Backup and restore your preferences (coming soon) |

> 💡 One-time purchase or monthly subscription. [Get License →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Pricing

| Plan | Price | Details |
|------|-------|---------|
| Free | $0 | 100 unlocks/day, all core features |
| Single Tool Monthly | $2.99/mo | Unlimited unlocks for LiteCopy |
| Single Tool Lifetime | $9.99 | One-time payment, permanent access |
| Full Suite Monthly | $3.99/mo | All VKT extensions, unlimited |
| Full Suite Lifetime | $19.99 | All VKT extensions, permanent |

See [VKT Pricing](https://www.annmax1983.com/pricing.html) for details.

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
2. Click the **LiteCopy** icon in your toolbar — the popup opens
3. Click **Enable** — text selection is restored instantly
4. To disable, open the popup again and click **Disable** (the page reloads to restore original behavior)

> **Note:** Some browser-restricted pages (`chrome://`, the Chrome Web Store, etc.) cannot be modified. The popup shows an error and no daily unlock is consumed.

**Copy Page Info:**
- Click the icon → popup opens
- Use buttons to copy page title, URL, or both

**Check Usage:**
- The usage bar at the top shows your daily unlock count
- Free users: 100/day, resets at midnight
- Premium users: ⭐ Unlimited

---

## Privacy

- ✅ **No analytics** — No tracking, no telemetry
- ✅ **Free tier: zero network requests** — All processing happens locally; nothing is sent unless you activate Premium
- ✅ **Minimal permissions** — `activeTab` + `scripting` + `storage`, plus the license API host
- ✅ **No site memory** — No blacklist/whitelist, no site preferences stored
- ✅ **License verification only** — If you activate a Premium license, a minimal device ID and your license key are sent to `api.annmax1983.com` for verification. No data is sent if you don't activate a license.

---

## Copyright Disclaimer

This tool only restores basic browser built-in text operation capabilities for users' personal learning, reference and offline reading. All text, pictures and content copyright of the website belong to the original author and website operator. Users shall not use this tool for commercial reproduction, mass crawling, content reprinting and other copyright-infringing behaviors. All legal liabilities arising from improper use shall be borne solely by the user.

---

## Source Code Notice

> ⚠️ **This repository does not publish source code.** It contains only usage documentation, release notes, and support resources. The extension is distributed exclusively through the Chrome Web Store. No offline installation packages or end-user source code are provided.

---

## License

Copyright © 2026 LiteCopy. All rights reserved.

---

## ❤️ Support

If you find LiteCopy helpful, consider supporting the project!

**[👉 Click here to support](https://ko-fi.com/annmax?ref=litecopy)**
