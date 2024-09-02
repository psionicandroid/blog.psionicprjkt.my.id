---
title: Neural Kernel for RM6785
description: Custom Kernel for Realme 6/6i(Indian)/6s/7/Narzo/Narzo 20 Pro/Narzo 30 4G (RM6785)
date: 2024-09-02
slug: KERNEL/RM6785/Neural
image: main.jpg
tags:
    - KERNEL
---

## About Kernel
```
Neural Kernel for RM6785
Custom Kernel for Realme 6/6i(Indian)/6s/7/Narzo/Narzo 20 Pro/Narzo 30 4G (RM6785)
for Custom ROM based realmeUI-2.0
```

## Latest Changelog
* 2024-09-02
  * Merge 'latest/7ed6e40' of KernelSU
  * Reverted kernel version trimming
  * Restored localversion kernel variants
  * Disable WALT scheduling
  * Switched to WeebX Clang 20.0.0
  * Enabled more -O3 optimizations 
  * treewide: Reduce inline optimization
  * Tuned ged_kpi for perf efficiency
  * Tuned ged_ge for memory efficiency
  * Tuned max boost groups for better perf
  * Tuned kernel/sched for optimized latency
  * Improved sched for Unity-based games (https://paste.crdroid.net/TVOwFq)
  * treewide: Use power-efficient wq
  * Disabled more debugging configs

## Downloads
* [⬇️ Neural-kernel-RM6785-01092024-fcc47a2.zip](https://sourceforge.net/projects/psionicprjkt/files/KERNEL/RM6785/Neural-kernel-RM6785-01092024-fcc47a2.zip/download)
* [⬇️ Neural-kernel-RM6785-01092024-fcc47a2-ksu.zip](https://sourceforge.net/projects/psionicprjkt/files/KERNEL/RM6785/Neural-kernel-RM6785-01092024-fcc47a2-ksu.zip/download)
* [⬇️ Neural-kernel-RM6785-01092024-08d3fb1-ksu-oc.zip](https://sourceforge.net/projects/psionicprjkt/files/KERNEL/RM6785/Neural-kernel-RM6785-01092024-08d3fb1-ksu-oc.zip/download)

```
FILE: Neural-kernel-RM6785-01092024-fcc47a2.zip (Normal/Non-KSU)
FILE: Neural-kernel-RM6785-01092024-fcc47a2-ksu.zip (Inc. KernelSU)
FILE: Neural-kernel-RM6785-01092024-08d3fb1-ksu-oc.zip (Inc. KernelSU + Overclock)
FILESIZE: 27 MB
```

## Info & Sources
* Device Info
  * Kernel: 4.14.x
  * Chipset: Mediatek MT6785 Helio G90T - ARMv8.2-A (64-bit)

* Sources
  * [psionicprjkt](https://github.com/psionicprjkt)
  * [officialputuid](https://github.com/officialputuid)
  * [realme-mt6785-devs](https://github.com/realme-mt6785-devs)

### Support Group
[psionicprjktchat](https://t.me/psionicprjktchat) | [psionicprjkt channel](https://t.me/psionicprjkt) | [psionicprjktlogs](https://t.me/psionicprjktlogs) managed by [officialputuid](https://t.me/officialputuid)

## Old Changelog
* 2024-08-27
  * Merge '4.14.352' of openela/kernel-lts

* 2024-08-24
  * Merge '4.14.351' of openela/kernel-lts
  * Merge 'latest/b2dbaa9' of tiann/KernelSU

* 2024-08-09
  * Merge '4.14.350' of openela/kernel-lts
  * Merge 'latest/a94c51c' of tiann/KernelSU
  * Switch to stock RUI2 kernel timer 
  * Simply localversion kernel

* 2024-07-26
  * Merge 'v1.0.1' of tiann/KernelSU
  * Switch kernel timer to 300 Hz
  * Refactor & trim kernel version logic
  * Prevent detection in localversion kernel [Read Notes]
  * The -ksu suffix has been removed from Neural Kernel versions, details are now in the additional info section: Normal [#1kv], KernelSU [#2kv], KernelSU + OC [#3kv], also added a custom uname override (lv from rui2) to avoid detection

* 2024-07-18
  * Merge '4.14.349' of openela/kernel-lts
  * Merge 'latest/e5b6320' of PhoenixKernel/linux
  * Merge 'latest/c01b462' of tiann/KernelSU
  * Drop BBRv2 (BBRv1 better)
  * treewide: Use power efficient wq

* 2024-07-07
  * Increase aggressive i-opt flags
  * net/sch: Switch to fq_codel (result (https://docs.google.com/spreadsheets/d/1YzZJkxgij-KARvgwpKd98UVEdgbAynWLq-Y3lxRLkBg/edit))
  * Added KProfiles v6.0.0 (mode (https://github.com/dakkshesh07/Kprofiles?tab=readme-ov-file#about))
  * KernelSU: Update state v1.0.0
  * Reduce thermal trip point
  * Enable more USB HID game controller support

* 2024-06-16
  * Increase thermal trip points for perf
  * Reduce rating of teo governor for battery
  * Fixed issue with charging animation getting stuck in stock ROM (thanks to @onlyskyie for reporting it)

* 2024-06-14
  * Implement xHide KSU|Zygisk (Momo happy?)
  * xHide for KSU|Zygisk|mounted systemless hosts
  * xHide for init.rc is modified|Device is running a custom ROM
  * Switch to TEO as the default CPU idle governor
  * Force enable KALLSYMS_ALL (APacth? not tested)
  * Allow users to change max swappiness to 200
  * More optimize subsystems with -O3
  * Added blu_schedutil CPU governor
  * Suppressed various log spams
  * Revert changes power efficient wq
  * Disable additional config debugging
  * Reduce latency for better responsiveness

* 2024-06-05
  * Upstreamed Kernel to v4.14.348

* 2024-06-04
  * Upstreamed Kernel to v4.14.347

* 2024-06-03
  * Upstreamed Kernel to v4.14.346

* 2024-06-02
  * Updated KernelSU v0.9.5

* 2024-05-31
  * Upstreamed Kernel to v4.14.345

* 2024-05-27
  * Drop Neural version, use codename
  * Enable nintendo switch controller driver
  * treewide: Use power efficient wq
  * Overclock BIG Cluster 2200 Mhz (OC)
  * Overclock GPU 900 Mhz (OC)
  * Updated KernelSU (main 11868)

* 2024-05-09
  * Upstreamed Kernel to v4.14.344
  * Improve perf with Clang Polly
  * Improve perf with inline optimization
  * Optimize subsystems with -O3
  * Updated KernelSU v0.9.4

* 2024-05-05
  * Bump version to R2
  * Added TCP BBRv2 (default still BBRv1)
  * Enable all available CPU_FREQ_GOV*
  * Switch to stable AOSP clang 18.0.1
  * Switch kernel timer to 50 Hz
  * Updated KernelSU v0.9.3 

* 2024-04-19
  * Introducing Neural Kernel R1
  * Upstreamed Kernel to v4.14.343
  * BBR as default TCP Congestion
  * Enable all available TCP Congestion
  * Compiled with ZyC clang 19.0.0
  * Support for U-QPR2 Custom ROMs
  * WireGuard v1.0.20220627 integration
  * gpufreq max to 821MHz for R6 Series
  * Added KernelSU v0.9.2 (11682) 
  * fs: Backport path_umount KSU <GKI>
  * Kernel timer set to 300 Hz
  * Fix random reboot, process systemui isn't responding/hotspot bug in QRP1/QPR2 ROMs
