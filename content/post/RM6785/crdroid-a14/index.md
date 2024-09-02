---
title: crDroid (Android-14) for RM6785
description: Custom ROM for Realme 6/6i(Indian)/6s/7/Narzo/Narzo 20 Pro/Narzo 30 4G (RM6785)
date: 2024-08-27
slug: ROM/RM6785/crDroid/A14
image: main.jpg
categories:
    - UNOFFICIAL
tags:
    - ROM
---

## About ROM
crDroid is a custom ROM based on LineageOS that provides a clean, stock Android experience along with useful customizations for added functionality and personalization. With its lightweight design, performance optimizations, security enhancements, and regular updates, crDroid has become a popular custom ROM in the Android community. At its core, crDroid aims to deliver a bloat-free, responsive Android UI that closely resembles stock Android. On top of this foundation, it adds thoughtful tweaks and options to enhance the user experience without compromising system stability and reliability.

## Whats Working
F-I | F-II | S-I | S-II
---------|---------|---------|---------
SELinux | Video/Screen/Audio REC | ✓ | ✓
RIL (Data,SMS,Calls) | Audio | ✓ | ✓
Userdata encryption[FDE] | GPS | ✓ | ✓
Fingerprint sensor | NFC | ✓ | ✓ (EU)
WiFi (2.4Ghz/5Ghz) | Sensors | ✓ | ✓
Bluetooth | Video Playback | ✓ | ✓
Camera | VoLTE | ✓ | ✓

### Known Issues
* Native video calling (ViLTE) and Voice over WiFi (VoWiFi)

## Latest Changelog
* 2024-08-27
  * August 2024 ASB
  * Add Moto Dolby Atmos
  * Add BCR v1.69 & BCR GUI v1.7.6
  * Signed build with private key
  * PI STRONG Passed by default (27/08)
  * Switch to RM6785-common tree
  * Fix & use Pixel offline charging
  * Updated KernelSU to v1.0.1
  * Upstreamed Kernel to v4.14.352+ksu
  * Compiled with clang 17.0.4 + Full LTO

## Downloads
[⬇️ crDroidAndroid-14.0-20240827-RMX2001L1-v10.7.zip](https://sourceforge.net/projects/psionicprjkt/files/RM6785/AwakenOS-A14/awaken-4.5-ursa-RM6785-unofficial-1149-20240617.zip/download) | [⬇️ GApps](https://sourceforge.net/projects/nikgapps/files/Releases/Android-14/13-Aug-2024/NikGapps-core-arm64-14-20240813-signed.zip/download) | [🌆 Screenshot](https://photos.app.goo.gl/QbUjREhE9QG5mdnu9)

```
FILE: crDroidAndroid-14.0-20240827-RMX2001L1-v10.7.zip
MD5SUM: e6d9094fed04224c6d8f6dca2cd9722f
FILESIZE: 1.6 GB (Vanilla)
```

## Instructions
* If you are coming form any ROM based realmeUI-1.0 (cleanflash)
  * Boot into custom recovery
  * Format Data
  * Flash ROM &  Flash Gapps (Optional)
  * Flash custom recovery based realmeUI-2.0
  * Reboot your device once the installation is done

* If you are on any ROM based realmeUI-2.0 (cleanflash)
  * Boot into custom recovery
  * Flash ROM &  Flash Gapps (Optional)
  * Format Data
  * Reboot your device once the installation is done

* If you use the same ROM (dirtyflash)
  * Boot into custom recovery
  * Flash ROM &  Flash Gapps (Optional)
  * Reboot your device once the installation is done

## Info & Sources
* Device Info
  * Kernel: 4.14.x
  * Chipset: Mediatek MT6785V/CD - MT6785V/CC - ARMv8.2-A (64-bit)

* Sources
  * [psionicprjkt](https://github.com/psionicprjkt)
  * [officialputuid](https://github.com/officialputuid)
  * [realme-mt6785-devs](https://github.com/realme-mt6785-devs)

### Support Group
[psionicprjktchat](https://t.me/psionicprjktchat) | [psionicprjkt channel](https://t.me/psionicprjkt) | [psionicprjktlogs](https://t.me/psionicprjktlogs) managed by [officialputuid](https://t.me/officialputuid)

## Old Changelog
