# TeslaUSB Config Generator (Unofficial)

This is a web-based tool designed to easily generate the configuration file (`teslausb_setup_variables.conf`) required for the **TeslaUSB** project.

## 🔗 Related Project
This tool creates configuration files specifically for:
**[marcone/teslausb](https://github.com/marcone/teslausb)** - The Raspberry Pi Tesla Dashcam archiving project.

## 🚀 How to use
1. Go to the live generator: **https://grodcur22.github.io/teslausb-config-generator/**
2. Fill out the form with your desired settings (WiFi, Archive settings, Push notifications, etc.).
3. Click "Generate Config".
4. Rename the downloaded file to `teslausb_setup_variables.conf`.
5. Place the file in the `boot` folder of your Raspberry Pi SD card.

## 🛠 Features
- User-friendly interface to avoid syntax errors.
- Supports all major configuration options (CIFS, Rsync, Rclone, Pushover, Telegram, etc.).
- Includes descriptions and hints for each variable.
- Client-side only: No data is sent to any server; everything is generated in your browser.

---
*This project is a fan-made contribution and is not officially affiliated with Tesla or the maintainers of teslausb.*
