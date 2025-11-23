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
**fastboot flash recovery recovery.img
fastboot flash vbmeta vbmeta.img
fastboot --disable-verity --disable-verification flash vbmeta_system vbmeta_system.img 
fastboot reboot fastboot
fastboot flash system system.img
fastboot flash product product.img
fastboot flash system_ext system_ext.img
fastboot flash odm odm.img
fastboot flash vendor vendor.img
fastboot flash mi_ext mi_ext.img
fastboot -w
fastboot reboot**

# Your Device Will Boot Into HyperOS
# Thanks...
