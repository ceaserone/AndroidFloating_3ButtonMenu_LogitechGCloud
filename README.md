<h1 align="center">Android Floating Menu!</h1>

<p align="center">
  <b>Floating Back / Home / Recents buttons for android! Built for the Logitech G Cloud.</b><br>
  Fixes the missing 3-button navigation bar Logitech G Cloud has removed.
</p>

<p align="center">
  <img src="setup.jpg" alt="SynAck Menu Setup" width="75%">
</p>

<p align="center">
  <a href="menu.apk">
    <img src="https://img.shields.io/badge/Download-APK-blueviolet?style=for-the-badge" alt="Download APK">
  </a>
</p>

---

## 🕹 What is Android Menu?

**"SynAck Menu"** is a small Android overlay app that adds a floating bubble with:

- **Back**
- **Home**
- **Recents**

It was built specifically for the **Logitech G Cloud**, which does **not** have the standard 3-button navigation bar in there firmware.  
This app gives you those buttons back, as a movable, theme-matched, neon bubble. (you must enable multi running apps in the G Cloud, dont forget) This also works for any android system obviously.

Works great for:

- **Dolphin Emulator** – hide the on-screen controller, Back/Home/Recents is needed to do this...
- **Strato / AetherSX2** – full-screen PS2/Switch emulation with a way to exit menus  
- **RetroArch / Lemuroid** – no more getting stuck in cores or settings  
- Full-screen Android games that hide navigation  
- Browser/launcher setups where gesture nav is flaky or disabled  

No root. No ads. No shit! Just install the APK, grant permissions, and go.

---

## 📸 Screenshots

### Setup Screen
<p align="center">
  <img src="setup.jpg" alt="SynAck Menu Setup" width="75%">
</p>

### Floating Menu (Collapsed)
<p align="center">
  <img src="menu.jpg" alt="SynAck Menu Bubble" width="75%">
</p>

### Floating Menu (Expanded)
<p align="center">
  <img src="menu2.jpg" alt="SynAck Menu Expanded" width="75%">
</p>

---

## ✨ Features
  
- 🟦 **Floating draggable bubble** that stays above apps  
- 🔲 **Back / Home / Recents** available everywhere  
- 🎮 Tuned for **Logitech G Cloud** handheld  
- 🚫 No ads, no tracking, no analytics  
- 🪶 Lightweight foreground service  
- 📱 Works on other Android devices too (phones, tablets, handhelds)

---

## 📥 Download

The compiled APK is included in this repository:

- **[`menu.apk`](menu.apk)**

You can download it directly from the GitHub repo’s file list or via the link above.

---

## 🔧 Installation

1. Download **`menu.apk`** to your device.
2. Enable **Install unknown apps** for your browser or file manager (one-time step).
3. Install the APK and open **SynAck Menu**.
4. On the setup screen, grant:
   - **Overlay / Draw over apps**
   - **Accessibility Service**
   - **YOU MIGHT NEED TO ENABLE RESTRICTED ACCESS!|UNDER APPS->menu.apk->too right 3 dots->enable restricted access..under new android OS this is required.**
   - (Optional) **Ignore battery optimizations**

5. Tap **Start Menu**.

You’ll now see a small floating bubble:

- **Drag** to move it anywhere on screen.  
- **Tap** to expand Back / Home / Recents.  
- Tap again or outside the panel to collapse.

---

The app is designed to run locally and simply provide navigation buttons.

---

## 📦 Repo Contents

This repo ships the **APK only** plus assets for the GitHub page:

```text
menu.apk          # Compiled SynAck Menu app
images/
  setup.jpg       # Setup screenshot
  menu.jpg        # Bubble screenshot
  menu2.jpg       # Expanded menu screenshot
README.md         # This file

