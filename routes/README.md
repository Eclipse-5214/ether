# Stella Secret Routes Guide

This guide explains how to manage, download, and share secret routes for the Stella mod.

---

### How Routes Work
Stella stores routes in your `.minecraft` folder under:
`../config/stella/routes/`

The mod looks for the specific file defined in your settings. If that file is missing locally, Stella will automatically attempt to fetch it from the **Stella Ether** asset server.

---

### Downloading & Updating Routes

#### 1. Automatic Sync
If you are using a standard route name like `default.json`, Stella attempts to download it automatically on startup if it doesn't exist.

#### 2. Manual Redownload / Updating
To force an update when server-side routes are changed:
1. Open the **Stella Menu**.
2. Navigate to **Secret Routes**.
3. Click **Update Routes**.

---

### Community & Discord Routes
Check the **#routes-sharing** channel in the **Stella Discord** for specialized sets (Mage-specific, experimental paths, etc).

**To install a custom route:**
1. Download the `.json` file.
2. Place it in `.minecraft/config/stella/routes/`.
3. Update your **Route File** name in the Stella config to match.
4. Use the **Reload Routes** button.

---

### Official Route Repository

| File Name | Description |
| :--- | :--- |
| `default.json` | Standard community routes. Recommended for most players. |
| `nexd.json` | Personal routes of NEXD_. |
| | |

---

> **Note:** To have your routes hosted on **ether.stellarskys.co** for automatic distribution, submit a request in the Discord.
