# 🎧 TuneDAC

**Hardware Parametric Equalizer Manager for KT Micro KT02H20 USB DACs**  
*(FiiO JadeAudio JA11 and compatible dongles)*

<p align="center">
  <img src="assets/screenshot.png" alt="TuneDAC Screenshot" width="360">
</p>

---

## 📥 Downloads

Download the latest version directly from the [**Releases Page**](https://github.com/khaidox/TuneDAC/releases/latest):

| Platform | Download File | Requirements | Description |
| :--- | :--- | :--- | :--- |
| 💻 **Windows** | [`TuneDAC-Standalone.exe`](https://github.com/khaidox/TuneDAC/releases/latest) | Windows 10 / 11 (64-bit) | **Single standalone `.exe`** — No install needed, just double-click! |
| 📱 **Android** | [`TuneDAC-Release.apk`](https://github.com/khaidox/TuneDAC/releases/latest) | Android 8.0+ (USB Type-C) | Standalone APK, no Google Play Services or Root required. |
| 🐧 **Linux** | [`TuneDAC-Linux-x64.tar.gz`](https://github.com/khaidox/TuneDAC/releases/latest) | 64-bit Linux (GTK 3, ALSA/PipeWire) | Extract and run `./TuneDAC-Linux-x64`. |

---

## ✨ Features

- **Direct Hardware DSP Control**: Communicates directly with the onboard KT02H20 DSP via USB HID protocols — no Root or Accessibility permissions needed.
- **5 Curated Audiophile Sound Profiles**:
  1. 🌸 **Pure Flat**: 0dB reference response straight from DAC hardware.
  2. 💣 **Deep Sub-Bass**: Punchy sub-bass boost at 80Hz (+4dB) with tight transient attack.
  3. 🎤 **Sweet Vocals**: Intimate forward midrange at 2kHz (+2.5dB) for crystal-clear vocals.
  4. 🔴 **Harman Target**: Internationally acclaimed target curve with deep sub-bass and clear treble.
  5. ⚡ **Energetic V-Shape**: Fun and dynamic profile with punchy bass and sparkling highs.
- **Instant A/B Comparison**: 1-Tap toggling between **Slot A** (Active Tuning) and **Slot B** (Reference Flat 0dB) while listening to effortlessly evaluate sonic differences in real time.
- **Real-Time Frequency Response Curve**: Interactive logarithmic graph (20Hz–20kHz) showing both active response and comparative dashed curves.
- **Multi-Layer Soft Micro-Mute**: Eliminates 100% of loud "pop" or "click" sound artifacts during IIR biquad filter parameter updates.
- **L/R Channel Balance**: Smooth stereo balance adjustment (-12dB to +12dB) across Android and Windows (powered by Windows Core Audio COM endpoints).
- **Smart Connection Feedback**: Real-time notifications and diagnostics when connecting to USB DACs.

---

## 🔌 Compatible Devices

TuneDAC supports USB DAC dongles equipped with the **KT Micro KT02H20** DSP chipset:

- **FiiO JadeAudio JA11**
- Other compatible KT02H20-based USB Type-C Audio adapters

---

## 💻 Windows Quick Start

1. Download **`TuneDAC-Standalone.exe`**.
2. Plug in your USB DAC dongle.
3. Double-click `TuneDAC-Standalone.exe` to run immediately!  
   *(Portable single-file binary — zero installation, setup, or external DLLs required).*

---

## 📱 Android Setup & Permissions

1. Download and install `TuneDAC-Release.apk`.
2. Connect your USB DAC dongle via Type-C.
3. When prompted: *"Allow TuneDAC to access USB device?"*, tap **OK**.

---

## 🐧 Linux Quick Start

```bash
tar -xzf TuneDAC-Linux-x64.tar.gz
./TuneDAC-Linux-x64
```

---

## 🛡️ Privacy & Security

- **100% Offline**: Zero network requests, zero telemetry, zero analytics.
- **No Background Drain**: The app only interacts with the DAC when active on screen.
- **Safe Hardware Operation**: Flash write operations are locked in this edition to prevent Flash ROM wear-out.

---

## 👨‍💻 Author & Developer

**TuneDAC** is developed and maintained by **[khaidox (Khai Do)](https://github.com/khaidox)**.

- 🌐 GitHub Profile: [@khaidox](https://github.com/khaidox)
- 📦 Repository: [https://github.com/khaidox/TuneDAC](https://github.com/khaidox/TuneDAC)
- 🎧 Hardware: KT Micro KT02H20 USB Audio DSP
- 💬 Feedback & Issues: [TuneDAC Issues](https://github.com/khaidox/TuneDAC/issues)
