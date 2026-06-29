# ❄️ Windows 11 Start Menu Styler: Frosty Glass Edition
> A refined, translucent "Frosty" experience for the redisigned Windows 11 Start Menu via Windhawk.

[![Windhawk](https://img.shields.io/badge/Requires-Windhawk-blue?style=flat-square)](https://windhawk.net/)
[![Style](https://img.shields.io/badge/Style-Frosty_Glass-lightgrey?style=flat-square)](#)

This configuration provides a modern **Frosty Glass** aesthetic for your Windows 11 Start Menu and Lock Screen. It utilizes custom translucent `AcrylicBrush` effects to create a soft, blurred interface that feels perfectly integrated with the desktop environment.

---

## 📋 Prerequisites

1. Download and install [Windhawk](https://windhawk.net/).
2. Inside Windhawk, search for and install the **Windows 11 Start Menu Styler** mod by Ramen Software.
3. Search for and install the **Start Menu Size** mod by Ramen Software.

---

## 🛠️ Installation Guide

### Step 1: Base Mod Settings
Before pasting the code, you need to set up the correct base layout. Open the settings for the "Windows 11 Start Menu Styler" mod and configure it exactly like this:
* **Theme:** `None`
* **Start menu layout:** `Windows Default`

### Step 2: Configure Start Menu Size
To ensure the Start Menu and Search Menu have a uniform, seamless look:
1. Open the settings for the **Start Menu Size** mod.
2. Apply these exact values:

| Setting | Value |
| :--- | :--- |
| **Start menu width** | `666` |
| **Start menu height** | `597` |
| **Search menu width** | `666` |
| **Search menu height** | `597` |

### Step 3: Import the Frosty Theme
1. **Mod Selection:** Open **Windows 11 Start Menu Styler** in Windhawk.
2. **Download Config:** Copy the raw code from [`start-menu-config.json`](https://github.com/guidolamanna/win11-startmenu-styler-frostyglass-windhawk/blob/main/start-menu-config.json).
3. **Advanced Tab:** Go to the **Advanced** tab of the mod settings, delete all text in the text box, and paste the copied code.
4. **Save:** Click **Save** to apply the frosty effects instantly.

---

## 🔒 Bonus: Apply Styling to the Lock Screen
This theme includes custom styling for the Windows 11 Lock Screen (Clock, Date and Media Controls styling). To enable it, you need to allow the mod to target the lock screen process:

1. Open the "Windows 11 Start Menu Styler" mod settings in Windhawk.
2. Go to the **Advanced** tab.
3. Scroll down to **Custom process inclusion list**.
4. Type exactly this in the box: `LockApp.exe`
5. Click **Save**. Press `Win + L` to lock your PC and enjoy your new Frosty Lock Screen!

> **🔤 Important Note on Fonts:** 
> This theme uses specific fonts to achieve the clean, modern look shown in image_e6d7c2.png. Please install them before applying the mod:
> * **Clock Font:** [Quicksand](https://fonts.google.com/specimen/Quicksand?preview.script=Latn) 
> * **Date Font:** [Vivo Sans En VF](https://1drv.ms/u/c/67fedd4420ed716d/EXRoW1f5dABJrO2dPj0tbM0Bm1uYiGeoKyAYA7X7er2Zww?e=cLsiJJ)
>
> **How to apply them:**
> Open the mod settings in Windhawk, scroll through the styles list to find the Lock Screen targets, and update the `FontFamily` property. You must use the **exact name of the font as it appears installed in your Windows system** (for example, in my setup I use `Quicksand SemiBold` for the clock and `vivo Sans EN VF` for the date).

---

## 📸 Showcase

### ❄️ Start Menu & Search Style

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/1a0ed3f8-f85b-49a8-8026-756e9196a5e9" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/c3e8af26-712d-44bb-856a-17c200b1d983" />

### 🔒 Lock Screen Style

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/5d85068d-f56e-43a2-9e93-f9c5aa5a02d6" />

---

## 🔗 Related Projects

Complete the look across your entire UI! Check out my other Frosty Glass styling repositories:
* [❄️ Frosty Glass Taskbar Styler](https://github.com/guidolamanna/win11-taskbar-styler-frostyglass-windhawk) to apply this exact same aesthetic to your Taskbar, Alt+Tab menu, volume sliders, and more!
* [❄️ Frosty Glass Notification Center Styler](https://github.com/guidolamanna/win11-notificationcenter-styler-frostyglass-windhawk) to theme your Notifications, Calendar, and Control Center flyouts!

---

## 🙌 Credits & Inspiration

A huge thank you to [Ramen Software](https://github.com/ramensoftware) for creating Windhawk. This configuration was heavily inspired by the official [Windows 11 Start Menu Styling Guide](https://github.com/ramensoftware/windows-11-start-menu-styling-guide) and the Windhawk modding community.

---

*Created by [Guido Lamanna](https://github.com/guidolamanna)*
