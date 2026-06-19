# 🔍 Simon Recon

**Simon Recon** is a lightweight browser extension for **Firefox** and **Chromium** that helps you discover and analyze **all URLs, APIs, and parameters** on any webpage.

Designed for **web developers**, **security researchers**, and **Bug Bounty hunters**.

**Author:** Simon

---

## ✨ Features

- 🚀 **Auto URL Discovery** – Collects all links from DOM, scripts, and resources
- 🔍 **Advanced Search** – Filter URLs by keyword in real-time
- 📊 **Smart Categorization** – Groups URLs into: All, Params, API, Files, Special
- 🎯 **Auto API Detection** – Identifies API endpoints using intelligent patterns
- 📋 **Quick Copy** – Copy single or bulk URLs
- 🌐 **Scope Restriction** – Shows only URLs relevant to the main domain
- 💜 **Purple-Dark Theme** – Clean dark theme with purple accents

---

## 🎯 Why Simon Recon?

In Bug Bounty and penetration testing, **Attack Surface Discovery** is critical. Simon Recon automates this:

> **Just click a button and see all the URLs and APIs on the page.**

Perfect for:
- Finding hidden APIs
- Identifying input parameters
- Discovering sensitive files (`robots.txt`, `sitemap.xml`, `.env`)
- Finding entry points for XSS, SQLi, IDOR testing

---

## 📦 Downloads

| Browser | File | Download |
|---------|------|----------|
| 🦊 **Firefox** | `.xpi` | [Download](https://github.com/itsimonsec/simon-recon/blob/main/extensions/Simon-Recon(Fire%20Fox).xpi) |
| 🌐 **Chrome / Edge / Brave** | `.crx` | [Download](https://github.com/itsimonsec/simon-recon/blob/main/extensions/Simon-Recon.crx) |

### How to Install
```
git clone https://github.com/itsimonsec/simon-recon.git
```
**Firefox:**
1. ```cd simon-recon```
2. Drag and drop it into Firefox
3. Click **Add**

> **Note:** If Firefox shows a warning, go to `about:config` and set `xpinstall.signatures.required` to `false`.

**Chrome / Edge / Brave:**
1.```cd simon-recon```
2. Go to `chrome://extensions/`
3. Enable **Developer mode** (top right)
4. Drag and drop the `.crx` file

---

## 🚀 How to Use

1. Click the extension icon in the toolbar
2. Click **Run on Current Tab**
3. Page reloads and **Simon Recon** opens
4. Browse, search, and copy URLs!

---
## ⚠️ Firefox Installation Notes

If you see the error **"This add-on could not be installed because it appears to be corrupt"** when installing the `.xpi` file:

1. Open Firefox and go to `about:config`
2. Click **Accept the Risk and Continue**
3. Search for `xpinstall.signatures.required`
4. Double-click to set it to **false**
5. Try installing the `.xpi` file again

> **Note:** This is only required for unsigned add-ons. The official Mozilla-signed version will install without this step.


**⭐ Star this repo if you find it useful!**
