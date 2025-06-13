# AstroBox Pi 5 Community Fork

**⚠️ This is an unofficial, community-maintained fork of AstroBox, created to support the Raspberry Pi 5. It is *not* affiliated with AstroPrint or its developers.**

---

## 📦 What is this?

This is a modified version of the official **AstroBox** image.  
The goal is to bring basic **Raspberry Pi 5 compatibility** to AstroBox, since there is no official image for the Pi 5 yet.

AstroPrint currently offers no support for this fork.  
However, if you're stuck or need help – feel free to reach out to me!
I'll do my best to help fellow makers.

---

## ✅ Current Status

| Feature             | Status         |
|---------------------|----------------|
| Raspberry Pi 5 Boot | ✅ Working     |
| Basic AstroBox UI   | ✅ Working     |
| Networking (WLAN)   | ⚠️ 90% Working |
| Display Support     | ✅ Working     |

---

## 🛠️ How does it work?

The Raspberry Pi 5 uses a newer bootloader and kernel modules that aren't available in the original AstroBox image.  
To make it work:

- I copied the required **boot files** and **kernel modules (/lib/modules)** from a working **Raspberry Pi OS (Bookworm)** image into the AstroBox image.
- Some minor config changes were made (e.g. `config.txt`, `cmdline.txt`) to ensure Pi 5 compatibility.

This method preserves the core functionality of AstroBox while unlocking Pi 5 support.

---

## ⚠️ Known Issues

- **Hotspot mode is not working**  
  The AstroBox Hotspot (Access Point) fails to start properly on the Pi 5.  
  However, **WiFi, USB, and Ethernet are working fine**, so connecting to your local network is still possible.

---

## 🙌 Want to contribute?

Feel free to open a pull request or suggest improvements via issues.  
Touchscreen support (especially for Waveshare displays) is on the roadmap – help is highly appreciated!

---

## ⚠️ Disclaimer

This is an **unofficial project** maintained by a community member.  
AstroPrint and its team are **not** responsible for any issues, bugs, or magical smoke arising from this image.

Please don’t bother the AstroPrint support with problems related to this fork – instead, [open an issue here](#) or contact me.

---

Thanks for checking out this project – and happy printing!
