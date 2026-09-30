# 🤖 PaPita — Custom Pwnagotchi

**PaPita** is a Pwnagotchi setup with a few small personal customizations made to the original configuration.

The core Pwnagotchi functionality remains unchanged. The changes are mainly focused on making the device feel more personal and convenient to use, including:

* Custom device name and configuration
* Custom devil-inspired display faces
* Small personality adjustments
* Waveshare 3 display configuration
* Bluetooth tethering support
* Internet connection monitoring
* Additional plugin configuration
* Minor logging and memory optimizations
* A few quality-of-life changes

This project is **not a complete rewrite or new Pwnagotchi implementation**. It is mainly a lightly customized configuration built on top of the existing Pwnagotchi project.

---

## ✨ What I Changed

The modifications are intentionally small and focused on personalization and usability.

### 🎨 Custom Faces

PaPita has a custom devil-inspired face theme:

```text
(¬‿¬)
(ಠ‿ಠ)
(≖‿≖)
(⌐■‿■)
(╬ಠ益ಠ)
```

### 📡 Bluetooth Tethering

Bluetooth tethering has been enabled so PaPita can use a paired phone for Internet connectivity.

```toml
main.plugins.bt-tether.enabled = true
main.plugins.bt-tether.auto_reconnect = true
```

### ⚙️ Small Configuration Changes

A few settings have been adjusted for:

* Display behavior
* Personality
* Channel configuration
* Logging
* Memory usage
* Plugin management
* Internet connectivity

The rest of the project continues to rely on the existing Pwnagotchi functionality.

---

## 🧩 Project Philosophy

The idea behind PaPita is simple:

> **Keep Pwnagotchi recognizable, but give it a small personal touch.**

Rather than changing the underlying Pwnagotchi system, this project focuses on configuration-level customization and a few additional plugins.

---

## 🔐 Responsible Use

PaPita is intended for educational purposes, personal experimentation, and authorized wireless-security testing.

Only use it with networks and devices that you own or have explicit permission to test.

---

## 👨‍💻 Author

**Anuj Kumar Sahu**

**PaPita — Lightly Customized Pwnagotchi**

A small personal customization of the Pwnagotchi experience.
