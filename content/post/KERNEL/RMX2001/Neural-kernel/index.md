---
title: Neural Kernel for RMX2001
description: Custom Kernel for Realme 6, 6s, 6i and Narzo (RMX2001/02/03)
date: 2024-06-16
slug: KERNEL/RMX2001/Neural
image: main.jpg
tags:
    - KERNEL
---

## About Kernel
```
Neural Kernel for RMX2001
Custom Kernel for Realme 6, 6s, 6i and Narzo (RMX2001/02/03)
for Custom ROM based realmeUI-1.0 (android 11)
```

## Latest Changelog
* 2024-06-16
  * Drop Neural version, use codename
  * Implement xHide KSU|Zygisk (Hide: init.rc is modified, Device is running a custom ROM. and some suspicious mounts)
  * Optimize subsystems with -O3
  * Increase thermal trip points for perf
  * Updated KernelSU v0.9.5 (11872)
  * Fix failed to execute pm in terminal (ksu)
  * Improve perf with inline optimization & Clang Polly
  * Reduce latency for better responsiveness

## Downloads
* [⬇️ Neural-kernel-RMX2001-16062024-a5a3d4b.zip](https://sourceforge.net/projects/psionicprjkt/files/KERNEL/RMX2001/Neural-kernel-RMX2001-16062024-a5a3d4b.zip/download)
* [⬇️ Neural-kernel-RMX2001-16062024-a5a3d4b-ksu.zip](https://sourceforge.net/projects/psionicprjkt/files/KERNEL/RMX2001/Neural-kernel-RMX2001-16062024-a5a3d4b-ksu.zip/download)

```
FILE: Neural-kernel-RMX2001-16062024-a5a3d4b.zip (Normal/Non-KSU)
FILE: Neural-kernel-RMX2001-16062024-a5a3d4b-ksu.zip (Inc. KernelSU)
FILESIZE: 16.4 MB
```

## Info & Sources
* Device Info
  * Kernel: 4.14.x
  * Chipset: Mediatek MT6785 Helio G90T - ARMv8.2-A (64-bit)

* Sources
  * [psionicprjkt](https://github.com/psionicprjkt)
  * [officialputuid](https://github.com/officialputuid)

### Support Group
[psionicprjktchat](https://t.me/psionicprjktchat) | [psionicprjkt channel](https://t.me/psionicprjkt) | [psionicprjktlogs](https://t.me/psionicprjktlogs) managed by [officialputuid](https://t.me/officialputuid)

## Old Changelog
* 2024-04-19
  * Introducing Neural Kernel R1
  * BBR as default TCP Congestion
  * Enable all available TCP Congestion
  * Compiled with Proton clang 13.0.0
  * WireGuard v1.0.20220627 integration
  * Added KernelSU to v0.9.2 (11682)
  * fs: Backport path_umount KSU <GKI>
  * Fix sulist KernelSU gone after restart
  * gpufreq: Adjust max Freq to 821MHz
