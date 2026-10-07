# Netmon

Desktop network monitoring for macOS and Windows: ping and up/down alerts, SNMP and NetFlow traffic, LAN discovery, a Wi-Fi analyzer, Wi-Fi site surveys with heat maps and access point planning, speed tests and PDF reports.

This repository holds the released apps. Netmon checks here for updates and installs them itself.

## Download

| | |
|---|---|
| **macOS** 11 or later (Apple silicon and Intel) | [Netmon-macOS.dmg](https://github.com/mgoodchild2025/netmon-releases/releases/latest/download/Netmon-macOS.dmg) |
| **Windows** 10/11 (x64) | [Netmon-Windows.zip](https://github.com/mgoodchild2025/netmon-releases/releases/latest/download/Netmon-Windows.zip) |

Older versions and release notes: [Releases](https://github.com/mgoodchild2025/netmon-releases/releases).

## Installing

**macOS:** open the DMG and drag Netmon to Applications, then open it from there. Netmon is signed and notarized by Apple, so it opens normally. Allow **Local Network** access when asked (for monitoring and device discovery) and **Location** for the Netmon Wi-Fi Scanner (macOS only shows Wi-Fi network names to apps with Location access).

**Windows:** unzip and put `Netmon.exe` in a permanent folder (for example `Documents\Netmon`), not inside the zip, so it can update itself. If SmartScreen appears, click **More info → Run anyway**.

## Updates

Netmon checks for new versions every few hours. When one is available, a banner offers **What's new** and **Install and restart**. You can also check from Settings → Updates, or turn on automatic installation there. Every release is signed: the app only installs files whose signature and checksums match the publisher's key.
