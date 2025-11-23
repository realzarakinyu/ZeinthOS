# ZeinthOS for Poco C75 5G & Redmi A4 5G
**Maintainer:** ZaraKinYu  
**Based on:** Global HyperOS OS1.0.10.0.UGVINXM  

---

## Introduction
ZeinthOS is a Modded HyperOS built specifically for **Poco C75 5G** and **Redmi A4 5G**, derived from the official Global HyperOS OS1.0.10.0.UGVINXM. It aims to provide:

- A **stable and smooth** Android experience.
- **Enhanced performance** for mid-range devices.
- **Minimal bloatware** while retaining essential features.
- **Optimized RAM and battery management**.

---

## Supported Devices
| Device Model       | Codename |
|------------------|----------|
| Poco C75 5G       | warm_in_global|
| Redmi A4 5G       | warm_global|

> **Warning:** Flashing on unsupported devices may **brick your phone**.  

---

## Features
- Based on **Global HyperOS OS1.0.10.0.UGVINXM**.
- Fully **deodexed and debloated**.
- **EXT4** formatted for partitions  
- **AVB/Verity disabled** for custom modifications.  
- **Optimized for mid-range RAM management**.

---

## Requirements
- Unlocked bootloader.
- A computer with **ADB & Fastboot** installed.
- Latest **USB drivers** for your device.
- Backup all important data (ZeinthOS installation will **wipe data**).

---

## Installation Instructions
> **Note:** Make sure your device has enough battery (>50%).  
1. **Boot into Fastboot mode**: 
2. fastboot flash recovery recovery.img
3. fastboot flash vbmeta vbmeta.img
4. fastboot --disable-verity --disable-verification flash vbmeta_system vbmeta_system.img 
5. fastboot reboot fastboot
6. fastboot flash system system.img
7. fastboot flash product product.img
8. fastboot flash system_ext system_ext.img
9. fastboot flash odm odm.img
10. fastboot flash vendor vendor.img
11. fastboot flash mi_ext mi_ext.img
12. fastboot -w
13. fastboot reboot

# Your Device Will Boot Into HyperOS
# Thanks...
