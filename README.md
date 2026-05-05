# Smart-system-code-using-ESP8266-to-control-8-devices
My DIY Smart Home Hub with Telegram Bot &amp; Music Sync
# 🚀 ESP8266 Smart AI Hub (Telegram + Voice Control)

A completely DIY Smart LED Controller built on ESP8266 (NodeMCU). This project transforms a basic LED setup into a multi-functional Smart Hub controlled via a Local Web Server, Voice Commands, and a Telegram Bot.

## ✨ Key Features
* 🌐 **WiFi Multi:** Automatically connects to the strongest available network.
* 🤖 **Telegram Bot Integration:** Control the system remotely from anywhere via 4G using a Telegram Bot. Secure login using Chat ID checking.
* 🎙️ **Voice Control:** Built-in Speech Recognition on the web interface.
* 🎵 **Music Sync (Club Mode):** Strobe lighting effect that strictly reacts to Kick Bass frequencies.
* ⚡ **Hardware Timer (Ticker):** Smooth 60FPS LED transitions without being blocked by network requests.
* 🌈 **28+ Auto Effects:** Including Matrix, Rainbow, Meteor, Heartbeat, Police, etc.

## 🛠️ Hardware Requirements
* 1x ESP8266 (NodeMCU 1.0 or similar)
* 1x OLED Display SSD1306 (128x32)
* 8x LEDs (or a relay module for real home appliances)

## 📦 Required Libraries
Make sure to install these via Arduino IDE Library Manager:
* `UniversalTelegramBot` (by Brian Lough)
* `ArduinoJson` (v6.x.x recommended)
* `Adafruit SSD1306` & `Adafruit GFX Library`

## 🚀 How to Use
1. Edit the `#define BOT_TOKEN` and `#define CHAT_ID` with your own Telegram Bot credentials.
2. Update the `setupWiFi()` function with your WiFi credentials.
3. Flash to your ESP8266 and send `/start` to your Telegram Bot!

---
*Built for fun and smart home automation learning.*
