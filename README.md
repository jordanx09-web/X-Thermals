# ❄️ X Thermals

**Advanced thermal and performance management module with WebUI control.**

---

> **X Thermals** is a root module designed to balance performance, temperature, and battery behavior across different usage styles.  
> It provides profile-based control with a clean WebUI and boot-persistent behavior for daily use, gaming, and battery saving.

---

## 🚀 Features

- 🎮 **Gaming Mode**  
  Unlocks high performance CPU/GPU behavior for maximum smoothness and FPS.

- ⚖️ **Balanced Mode**  
  Optimized daily profile for stable performance and controlled thermals.

- 🔋 **Power Save Mode**  
  Prioritizes lower heat and reduced battery drain for longer usage time.

- 🧠 **AI Mode**  
  Automatically switches profiles using battery level, charging state, load, temperature, and screen activity.

- 🌐 **Built-in WebUI**  
  Clean interface for changing modes quickly without editing files manually.

- 🔁 **Boot Persistence**  
  Selected behavior is automatically re-applied after reboot.

- 🛠️ **Cross Root Support**  
  Compatible module workflow for **Magisk**, **KernelSU**, and **APatch**.

---

## 📦 Requirements

- Rooted Android device
- One of:
  - Magisk
  - KernelSU
  - APatch
- Recommended: recent Android/HyperOS build

---

## 📥 Installation

1. Download the latest `X-Thermals` module zip.
2. Open your root manager (**Magisk / KernelSU / APatch**).
3. Go to **Modules**.
4. Select **Install from storage**.
5. Flash the zip.
6. Reboot device.
7. Open the module WebUI and select your preferred mode.

---

## 🧭 Usage

- Choose one profile from WebUI:
  - `gaming`
  - `balanced`
  - `powersave`
  - `ai`
- Changes are applied by the background service.
- Reboot is recommended after first install for full initialization.

---

## ⚠️ Important Notes

- Thermal and power behavior depends on kernel + ROM implementation.
- Some OEM thermal components may be encrypted/closed-source.
- Real-world results vary by chipset, ambient temperature, charger type, and battery health.
- Always test new settings gradually.

---

## 🧪 Troubleshooting

- If mode changes are not applying:
  - Reboot once
  - Re-open WebUI and re-select mode
- If behavior seems inconsistent:
  - Check service log:
    - `/data/local/tmp/xthermals.log`
- If needed, clean flash module and reboot again.

---

## 🔒 Disclaimer

This module changes low-level thermal/performance behavior.  
Use at your own risk. The author is not responsible for device damage, overheating, data loss, or misuse.

---

## 🤝 Credits

Developed by **Jordanx_09**  
Community and updates via GitHub and Telegram.
