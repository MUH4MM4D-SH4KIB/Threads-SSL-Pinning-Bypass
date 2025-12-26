# 🔐 SSL Pinning Bypass — Thrrads App

This repository demonstrates how SSL/TLS **certificate pinning** works in the **Threads** app, along with a **practical example** of bypass techniques and HTTPS traffic capture.

---

## 🎥 Demo Video

▶️ [Watch the demonstration](https://github.com/user-attachments/assets/d286a3c0-3da3-4788-ad04-f730a42a8630)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Threads App Version 
- **411.0.0.0.75**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)

---

## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator

---

## 🚀 Bypass Procedure

1. Replace patched `libstartup.so with /data/data/com.instagram.barcelona/lib-compressed/libstartup.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libstartup.so /data/data/com.instagram.barcelona/lib-compressed/libstartup.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libstartup.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
