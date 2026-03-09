# ansible-workstation-ubuntu

This repo exists to rebuild my Ubuntu workstation quickly, which is a critical need for playing 24/7 non-stop loops of Berman-era Star Trek.

## Preparation
Download latest Ubuntu ISO

Create bootable usb drive
```dd if=ubuntu-24.04.4-desktop-amd64.iso of=/dev/rdiskN bs=1m```

## Installation

Hold Option key upon boot to load boot menu, select usb drive, select install Ubuntu

Choose language, accessibility, keyboard layout, connection to internet, install Ubuntu, interactive installation, extended selection

Enable Install third-party software for graphics and Wi-Fi hardware

Erase disk and install Ubuntu

Set up your user **with a password**; this document presumes user `jarvis` with computer name `tower`.

Select timezone

Install