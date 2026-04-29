# AGB-IPS-MAX-Display-Logos
![Commodore 64 Logo](/preview.JPG)

This repository contains fan‑made, original logos designed for the Funnyplaying Max IPS display.
All artwork here is hand‑created, redrawn, or stylized, no copyrighted assets were extracted from games, ROMs, or firmware.

The goal is to build a clean, community‑friendly collection of splash screens, boot logos, and themed graphics for the Funnyplaying Max display.

# 📤 How to Upload a Custom Logo to the Funnyplaying Max IPS Display

The Funnyplaying Max IPS display stores **up to 15 custom logos** directly on the driver board.  
To upload a new 960×80 BMP logo, you can use either the **online tool** or the **official Windows tool**.

---



## 🌐 Method 1: Upload via Browser (Recommended)

This is the easiest method. No drivers, no COM port selection.

**Website:**  
https://gba-max-tool.chipoftheseus.shop/

### Steps

1. Connect the Funnyplaying Max display driver board to your PC via USB.
2. Open the website above.
3. Click **Connect to screen**.
4. Select the **CH340** device when prompted.
5. Click **Choose file** and select your **960×80 BMP**.
6. Select a **slot (1-15)**.
7. Click **Upload**.
8. Wait for the confirmation message.

Your logo is now stored on the display board.

---

## 🖥️ Method 2: Upload via LogoUpdater.exe (Offline Tool)

This is the official Funnyplaying Windows tool.

### Steps

1. Connect the display driver board to your PC via USB.
2. Open **Device Manager** → expand **Ports (COM & LPT)**.
3. Find **CH340** and note the COM port number (e.g., COM5).
4. Open **LogoUpdater.exe**.
5. Under **The UART Port**, select the COM port you found.
6. Under **The index of logo to upload**, choose a slot (1–15).
7. Click **Choose File** and select your **960×80 BMP**.
8. Click **Start Upload**.
9. Wait until the progress bar completes.

Your logo is now flashed to the selected slot.

---

## 📝 Notes & Requirements

- Logos **must** be **960×80 BMP** (4‑bit / 16‑color, but only 4 colors are actually used).
- The display can store **15 logos** at once.
- Uploading a new logo to a slot **overwrites** the previous one.
- You can switch logos on the device using the Funnyplaying button combo.

---

## 🛠️ Troubleshooting

**CH340 does not appear:**

- Try a different USB cable (some are charge‑only).
- Try a different USB port.
- Install the CH340 driver if needed.

**Upload fails:**

- Disconnect and reconnect the USB cable.
- Close any program using the COM port.
- Try another slot.


[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
