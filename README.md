# 🔧 UAMT – Ultimate Android App Modding Toolkit

UAMT is a powerful Termux-based Android modding toolkit that allows you to inject Frida Gadget and custom native libraries, patch APKs, rebuild, align, and sign them directly on your Android device.

It is designed to be fast, stable, and easy to use, featuring a full-screen interactive TUI, smart auto-detection, and automatic dependency installation.

Run with:
```uamt```


---

✨ Features

🧩 Injection

Inject Frida Gadget

Listen mode

Wait mode

Pre-injected script


Inject any custom .so native library

Download and inject Frida Gadget for multiple ABIs at once


🧠 Smart Detection

Automatically detects the best injection method:

🔵 Native injection using patchelf

🟣 Smali injection using APKEditor


Detects main native libraries such as:

libil2cpp.so

libunity.so

and more



🛠️ Tools & Build System

Auto-download and unpack Frida Gadget

Full APK rebuild pipeline:

zipalign

v1 / v2 / v3 signing



🎨 Interface

Colorful curses-based full-screen TUI

Built-in file picker

Improved layout and visual polish


🛡️ Safe Modding

Automatically adds missing INTERNET permission

Reduces common APK breaking issues


⚙️ Automation

One-time automatic installation of all required dependencies

One-tap connection to Frida Gadget

Optimized for Termux environments



---

🆕 What’s New

Improved UI design

Multi-ABI Frida Gadget injection support

File picker added (no manual path input)

Overall performance and stability improvements



---

📱 Requirements

Termux (latest version)


Run once:

termux-setup-storage

> On first launch, go through the Install / Update option and then download frida gadget option with an active internet connection to automatically set up all dependencies.




---

📦 Installation

Install via pip:

```pip install uamt```

Then run:

```uamt```


---

🔍 Use Cases

Android APK modding

Frida Gadget injection

Native library injection

Reverse engineering

Android security research

Termux-based workflows



---

⚠️ Disclaimer

UAMT is intended for educational, research, and authorized testing purposes only.
Do not use this tool on applications you do not own or have permission to modify.
