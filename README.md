<p align="center">
  <img src="assets/banner.png" alt="Clover Project Banner" width="800"/>
</p>

<p align="center">
  <a href="https://github.com/gachanxd/Clover-fleur/releases">
    <img src="https://img.shields.io/github/v/release/gachanxd/Clover-fleur?style=for-the-badge&logo=android" alt="Latest Release"/>
  </a>
  <img src="https://img.shields.io/badge/Android-15-blue?style=for-the-badge&logo=android"/>
  <img src="https://img.shields.io/badge/Device-Fleur-green?style=for-the-badge&logo=xiaomi"/>
  <img src="https://img.shields.io/badge/Status-UNOFFICIAL-orange?style=for-the-badge"/>
</p>
# Clover Project for Xiaomi Fleur (MT6781)

![Android](https://img.shields.io/badge/Android-15-blue.svg)
![Device](https://img.shields.io/badge/Device-Fleur-green.svg)
![Status](https://img.shields.io/badge/Build-UNOFFICIAL-orange.svg)

## 📱 About
Clover Project is an Android 15 QPR2-based custom ROM for **Xiaomi Fleur (MT6781)**.  
This build is maintained unofficially and provides a clean, smooth, and feature-rich Android experience.

## ✨ Features
- Based on **Clover Project v2.7**
- Android **15 QPR2**
- **KernelSU support** (via optional boot image patch)
- Up-to-date **security patches**
- Smooth performance & stability
- Debloated & optimized for daily use

## ⚡ Installation
1. Boot into custom recovery (e.g. OrangeFox, TWRP).
2. **Wipe system/data/cache** if coming from another ROM.
3. Flash the latest CloverProject ROM zip from [Releases](https://github.com/gachanxd/Clover-fleur/releases).
4. (Optional) Flash `ksu-patch.img` via **fastboot** for KernelSU support:
   ```bash
   fastboot flash boot ksu-patch.img
