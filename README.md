# Pyae's Macro Pad

My macro pad is a 12 key macro pad with a rotary encoder, an OLED Display.
It uses QMK firmware

It serves as a macro pad that I can use every day.

## Features:
- 128x32 OLED Display
- EC11 Rotary encoder for volume
- 12 Keys for what ever
- [VIA](https://www.caniusevia.com/) support

## CAD Model
Everything fits together using 8 M3 Bolts and heatset inserts.

It has 2 different pieces, the Case and the Plate.

<img width="1165" height="791" alt="image" src="https://github.com/user-attachments/assets/a3df0b8d-e8fe-4fe1-b7da-4a1f0a3d425c" />

The model was made in Shapr 3D.

##PCB
My PCB was made using KiCad.

Schematic

<img width="1250" height="631" alt="image" src="https://github.com/user-attachments/assets/030f6dd6-54e0-4566-b0a3-37391eaa0fc4" />


PCB

<img width="728" height="992" alt="image" src="https://github.com/user-attachments/assets/8e311ab8-0277-4e9c-a988-f5cafe62dbfd" />


I used [Joe Scotto's](https://www.youtube.com/@joe_scotto) footprints for all of them.

## Firmware
This hackpad uses [QMK](https://qmk.fm/) firmware for everything.
- 12 keys used for macros (can be changed with VIA).
- Rotary encoder used to change volume.
- OLED display to show what layer is currently open.

## BOM:
Here is everything you will need to make this hackpad

12x Cherry MX Switches
12x DSA Keycaps
8x M3x5x4 Heatset inserts
8x M3x16mm SHCS Bolts
12x 1N4148 DO-35 Diodes.
1x 0.91" 128x32 OLED Display
1x EC11 Rotary Encoder
1x XIAO RP2040
1x Case (2 printed parts)
