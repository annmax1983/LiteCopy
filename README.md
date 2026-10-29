# LiteCopy

English | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

A lightweight browser extension that restores native text selection, right-click menu, and copy shortcuts on any website.

> Chrome · Edge · Firefox · Manifest V3 · Unlimited free copying · Premium cross-device site rules

---

## Why LiteCopy?

Ever tried to copy text from a website but couldn't select it, right-click was blocked, or Ctrl+C did nothing? LiteCopy fixes all of that with one click.

| Advantage | Detail |
|-----------|--------|
| 🔓 **One-Click Activate** | Restore native text selection instantly — no page refresh needed |
| ♾️ **Free & Unlimited** | Copy, select and right-click as much as you want — no daily cap, no copy counter |
| 🔄 **Cross-Device Site Rules** | Premium keeps the sites you enable in sync through your browser's own account sync (Chrome Sync / Edge Sync / Firefox Sync) |
| 🔒 **Local by Design** | Unlocking runs locally with `activeTab` + `scripting`; site access is used only on the pages you enable |
| ⚡ **Lightweight** | No frameworks, no runtime dependencies |
| 🌍 **6 Languages** | English, Chinese, Spanish, German, Japanese, French |
| 🚫 **No Tracking** | No analytics, no telemetry. The developer has no server that stores your browsing or site list |
| 🎯 **Simple Toggle** | Open the popup and hit Enable/Disable — clear ON/OFF state indicator |

---

## Features

### 🆓 Free — unlimited

| Feature | Description |
|---------|-------------|
| 🔓 **Restore Text Selection** | Restores default text selection on sites that disable it |
| 🖱️ **Restore Right-Click Menu** | Recovers browser right-click menu on restricted sites |
| ⌨️ **Restore Keyboard Shortcuts** | Recovers Ctrl+C, Ctrl+V, Ctrl+A and other standard shortcuts |
| 🛡️ **Fix Overlay Interference** | Fixes transparent overlay divs that interfere with text selection |
| 🔄 **Toggle ON/OFF** | Enable/Disable from the popup, page reloads when disabled |
| 🧠 **Remembered Sites** | Sites you enable are remembered locally and auto-enabled on your next visit |
| 💬 **Toast Notification** | Auto-dismissing notification shows activation status |
| 📋 **Copy Page Info** | Popup buttons to copy page title, URL, or both |

> All features above are free with no copy limit and no daily reset.

### ⭐ Premium — site rules across devices

| Feature | Description |
|---------|-------------|
| 🔄 **Cross-Device Site Rules** | Enable a site once and the rule follows your browser account, so it is auto-enabled on your other signed-in devices |
| 🔐 **Browser-Account Sync** | The list is stored by your browser in `storage.sync` (Chrome Sync, Edge Sync or Firefox Sync). No LiteCopy account, no developer-hosted copy, and the developer cannot read it |
| 💻 **Per-Device Access** | Browser host permissions cannot be synced. On a new device, click Enable once on the synced site to grant access — the saved rule is already there |
| 🧭 **Manual Sync** | A **Sync now** button in Settings pulls the latest list from your browser account at any time |

> 💡 One-time purchase or monthly subscription. [Get License →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Preview

<p align="center">
  <img src="assets/favicon.png" alt="LiteCopy Icon" width="80">
</p>

---

## Supported Browsers

| Browser | Status | Notes |
|---------|--------|-------|
| Google Chrome | ✅ Fully supported | Manifest V3 |
| Microsoft Edge | ✅ Fully supported | Manifest V3 |
| Mozilla Firefox | ✅ Fully supported | Manifest V3, Firefox 140+ (desktop) |
| Other Chromium-based browsers | ✅ Should work | Manifest V3 |

> **Firefox note:** unlocking works exactly the same way. Premium sync uses **Firefox Sync** — sign in to your Mozilla account in Firefox and the site rules follow you to other signed-in profiles.

---

## Installation

| Store | Link |
|---|---|
| Chrome Web Store | [Install for Chrome](https://chromewebstore.google.com/detail/opckcochfnlfcdoblnmgeebeeggfnilg) |
| Microsoft Edge Add-ons | [Install for Edge](https://microsoftedge.microsoft.com/addons/detail/acpfcfipfalphidhmpflecncacgldggl) |
| Firefox Add-ons (AMO) | 🔜 Under review — link will be added once the listing is live |

> Install only from the official stores above — avoid third-party download sites.

---

## Usage

1. Visit any website that blocks copying or text selection
2. Click the **LiteCopy** icon in your toolbar — the popup opens
3. Click **Enable** — text selection is restored instantly
4. To disable, open the popup again and click **Disable** (the page reloads to restore original behavior)

> **Note:** Some browser-restricted pages cannot be modified — `chrome://` pages and the Chrome Web Store on Chrome / Edge, or `about:` pages and addons.mozilla.org on Firefox. The popup shows an error.

**Site rules and sync (Premium):**
- Enable a site on one device — the rule is added to your browser account's sync storage
- On another device signed into the same browser account, the site appears as a saved rule; click **Enable** once to grant that device's host permission
- Open **Settings** to see how many sites are synced and use **Sync now** if you want to refresh immediately

**Copy Page Info:**
- Click the icon → popup opens
- Use buttons to copy page title, URL, or both

---

## Privacy

- ✅ **No analytics** — No tracking, no telemetry
- ✅ **Free features: zero network requests** — All processing happens locally; nothing is sent unless you activate Premium
- ✅ **Focused permissions** — `activeTab` + `scripting` + `storage` run the unlock, plus site access used solely to inject it on the pages you enable, and the license API host
- ✅ **Site list stays local by default** — Enabling LiteCopy records that domain in `storage.local`. The list is never sent to the developer
- ✅ **Premium sync uses your browser account** — With an active license the site list is also mirrored to `storage.sync` (Chrome Sync / Edge Sync / Firefox Sync), which is your browser vendor's account sync. The developer has no access to it and receives no copy. Sync stops if the license is removed; existing local rules keep working
- ✅ **License verification only** — Activating a Premium license sends a minimal install ID and your license key to `api.annmax1983.com` for verification. No data is sent if you don't activate a license

---

## Copyright Disclaimer

This tool only restores basic browser built-in text operation capabilities for users' personal learning, reference and offline reading. All text, pictures and content copyright of the website belong to the original author and website operator. Users shall not use this tool for commercial reproduction, mass crawling, content reprinting and other copyright-infringing behaviors. All legal liabilities arising from improper use shall be borne solely by the user.

---

## Source Code Notice

> ⚠️ **This repository does not publish source code.** It contains only usage documentation and support resources. The extension is distributed exclusively through the Chrome Web Store, Microsoft Edge Add-ons and Firefox Add-ons (AMO). No offline installation packages or end-user source code are provided.

---

## Privacy Policy

See the full [Privacy Policy](privacy-policy.html) — free features are fully offline with zero network requests.

---

## License

Copyright © 2026 LiteCopy. All rights reserved.

---

## ❤️ Support

If you find LiteCopy helpful, consider supporting the project!

**[👉 Click here to support](https://ko-fi.com/annmax?ref=litecopy)**
