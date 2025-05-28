#  DotBot – External Colorbot + Triggerbot (Arduino Leonardo + Python)
---
>**Note:** This is not a release but only a trailer/showcase.

[![Image](https://github.com/user-attachments/assets/b3ea058b-d56b-4db2-a7a5-5acecb47c079)](https://youtu.be/iI8W8aszt50)

> 🔗 Click the image above to watch the full showcase on YouTube.

![image](https://github.com/user-attachments/assets/f15b8f96-1a38-476b-81b7-827f7dae043b)


##  Features
-  **Colorbot / Aim Assist** – Tracks and aims at colored dots using screen detection and FOV targeting.
-  **Triggerbot** – Automatically fires when the crosshair overlaps a target.
-  **Smart GUI** – PyQt5 GUI lets you adjust:
  - Aimbot speed
  - Detection color
  - Triggerbot toggle
  - FOV radius and offset
  - Spectator ChatBot
  - Draw Line & Box
  - Configure Offsets
  - Save & Load Config
  - Select Window (only apply to specific window)
  - Customize Menu Color & Name
  - About Information
-  **Arduino Leonardo + USB Host Shield** – Used for raw HID mouse input emulation.
-  **Stealth Mode** – Hide the interface while the bot continues running.
-  **Spoofing Utility** – Optional VID/PID spoofing tool to mask Arduino as a real HID device.
-  **Unspoof Option** – Restores your original boards.txt settings easily.

##  How It Works
1. Run `spoofer.py` to change the Arduino's VID/PID (or unspoof).
2. Launch `launcher`, via `spoofer.py` type your COM port. (ex. COM3)
3. Adjust aimbot parameters via the GUI.
4. Aim on/near dot color targets and let DotBot assist.

>**Note:** This feature list as-well as file being python is **subject to change** as development continues.

## ⚠️ Disclaimer
This is a **proof-of-concept tool for educational and research purposes only**.  
Do not use DotBot in online multiplayer or competitive games. Use at your own risk.

---

**GitHub**: `@DXXTHLY`  
**Discord**: `DXXTHLY.`  
**Community**: [https://dsc.gg/143x](https://dsc.gg/143x)
