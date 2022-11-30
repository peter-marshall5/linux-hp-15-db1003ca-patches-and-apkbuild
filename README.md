# Patches, configuration, and APKBUILD for mainline Linux on HP 15-db1003ca

This repo comes with the patches, APKBUILD, and kernel configuration that I'm using to build mainline Linux for the HP 15-db1003ca.

## Hardware specifications of this device

Hardware | Specification
--- | ---
SOC | AMD Ryzen™ 3 3200U (5 MB cache, 2 cores)
Graphics | AMD Radeon™ Vega 3 Graphics
CPU clock | 2.6 GHz base clock, up to 3.5 GHz max boost clock
Memory | 8 GB DDR4-2400 SDRAM (1 x 8 GB)
Hard Drive | 1 TB 5400 rpm SATA
Optical Drive | Not Included
NVMe SSD | Not Included
Wi-Fi Card | Realtek 802.11b/g/n/ac (2x2) Wi-Fi® and Bluetooth® 4.2 combo
Ethernet | Realtek Integrated 10/100/1000 GbE LAN
Expansion Slots | 1 multi-format SD media card reader
External Ports | 1 HDMI; 1 headphone/microphone combo; 1 RJ-45; 2 USB 3.1 Gen 1 (Data transfer only); 1 AC smart pin; 1 USB 2.0 Type-A (Data Transfer Only)
Minimum dimensions (W x D x H) | 37.6 x 24.6 x 2.25 cm
Weight | 1/9 Kg
Power Supply | 45 W AC power adapter
Battery | 3-cell, 41 Wh Li-ion
Webcam | HP TrueVision HD Camera with integrated digital microphone
Audio | Stereo Speakers

## What's currently working:

Pretty much everything is supported perfectly with this laptop (with no patches).
Feature | Status
--- | ---
Display | ✔️
GPU Acceleration via amdgpu | ✔️
Backlight Control | ✔️
HDMI Output | ✔️
USB 2.0 and 3.0 | ✔️
Keyboard | ✔️
Touchpad via PS/2 bus | ✔️
Touchpad via i2c bus | ✖️
Battery Level Monitoring | ✔️
Battery Power Monitoring | ✔️
Battery Charge Thresholds | ✖️ (1)
Internal Speakers | ✔️
Headphone Output | ✔️
Headphone Jack Detection | ✔️
Headset Microphone | ✔️
Internal Microphone | ✔️
Wifi (Client, AP, Ad-Hoc) | ✔️
Wifi Monitor Mode | ✔️
Wifi Card Temperature | ✖️ (2)
Bluetooth | ✔️
Charger Detection | ✔️
Lid Switch | ✔️
CPU and GPU Temperature | ✔️
Battery Temperature | ✔️
SSD Temperature | ✔️
HDD temperature via SMART | ✔️
Suspend | ✔️
Shutdown | ✔️
Rebooting | ✔️
Real Time Clock | ✔️
NVMe SSD | ✔️
SATA HDD | ✔️
SD Card Reader | ✔️
DVD Drive | ✔️
Windows Dual Boot | ✔️
UEFI Secure Boot | ✔️
KVM | ✔️
BMQ scheduler | ✔️
Clang Thin LTO | ✔️

(1) Likely unsupported by the battery controller
(2) Possibly unsupported by the wifi card

