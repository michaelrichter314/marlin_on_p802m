# Marlin on Tronxy p802m
Marlin 2.0 compatible configuration for Tronxy p802m

Work in progress, but prints (at least through Octoprint). Needs calibration.

Tested with Marlin 2.0.5.3: https://github.com/MarlinFirmware/Marlin/archive/2.0.x.zip

# Build instructions
The installation process is similar to https://www.youtube.com/watch?v=7J7NYnxL5vA

Install bootloader: prepare Arduino as ISR flasher, install board "Sanguino," then connect Melzi board, move power jumper to power through USB, and flash bootloader

Flash firmware: Connect Melzi board through USB, then upload firmware from Arduino IDE
