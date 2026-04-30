# ❄️ Windows 11 Start Menu Styler: Frosty Glass Edition

A clean, minimalist, and highly customizable frosted glass/acrylic theme for the Windows 11 Start Menu. This theme unifies the UI with smooth translucent borders, rounded corners, and a frosty aesthetic, extending even to the Windows Lock Screen.

This theme is built to be used with the **Windhawk** application and the **Windows 11 Start Menu Styler** mod.

## 📋 Prerequisites

1. Download and install [Windhawk](https://windhawk.net/).
2. Inside Windhawk, search for and install the **Windows 11 Start Menu Styler** mod by Ramen Software.

---

## 🛠️ Installation Guide

### Step 1: Base Mod Settings
Before pasting the code, you need to set up the correct base layout. Open the settings for the "Windows 11 Start Menu Styler" mod and configure it exactly like this:
* **Theme:** `NoRecommendedSection`
* **Disable the new start menu layout:** `Disable new layout and Phone Link`

### Step 2: Import the Frosty Theme
1. **Mod Selection:** Open **Windows 11 Start Menu Styler** in Windhawk.
2. **Download Config:** Copy the raw code from [`start-menu-config.json`](https://github.com/guidolamanna/win11-startmenu-styler-frostyglass-windhawk/blob/main/start-menu-config.json).
3. **Textual Mode:** Click on the **Textual mode** button at the top of the settings and paste the code.
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
> This theme uses the **"Quicksand"** font for the Lock Screen to achieve a specific clean, modern look. 
> * **To get the exact look from the screenshots:** Download and install the "Quicksand" font family (freely available on Google Fonts) before applying the mod.
> * **To use a native/custom font:** Open the mod settings in Windhawk, scroll through the styles list to find the Lock Screen targets (`TextBlock#Time` and `TextBlock#Date`), and change the `FontFamily` property to your preferred system font (e.g., `Segoe UI Variable`).

---

## 📸 Showcase

### ❄️ Start Menu Style

<img width="2879" height="1799" alt="Screenshot 2026-04-29 133342" src="https://github.com/user-attachments/assets/d0b63421-bb3a-465e-b176-bcf847707161" />
<img width="2879" height="1799" alt="Screenshot 2026-04-29 133353" src="https://github.com/user-attachments/assets/17941aaf-a62f-4566-9c96-5bf769f56957" />

### 🔒 Lock Screen Style

<img width="2344" height="1662" alt="IMG_8893" src="https://github.com/user-attachments/assets/7e065d0d-8d3e-407c-87f9-3f3debcbde2c" />

> *Note: This is a photo captured with a phone, as standard screenshots on the lock screen can be difficult. It provides a perfect representation of the clean aesthetic.*

---

## 🔗 Related Projects

Complete the look across your entire OS! Check out my other Frosty Glass styling repositories:
* [❄️ Frosty Glass Taskbar Styler](https://github.com/guidolamanna/win11-taskbar-styler-frostyglass-windhawk) to apply this exact same aesthetic to your Taskbar, Alt+Tab menu, volume sliders, and more!
* [❄️ Frosty Glass Notification Center Styler](https://github.com/guidolamanna/win11-notificationcenter-styler-frostyglass-windhawk) to theme your Notifications, Calendar, and Control Center flyouts!

---

## 🙌 Credits & Inspiration

A huge thank you to [Ramen Software](https://github.com/ramensoftware) for creating Windhawk. This configuration was heavily inspired by the official Start Menu styling capabilities and the Windhawk modding community.

---

*Created by [Guido Lamanna](https://github.com/guidolamanna)*
