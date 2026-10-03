# Pyae's Macropad

My macropad is a 13 key macropad with a rotary encoder.
It uses QMK firmware

It serves as a macropad that I can use every day.

## Features:
- EC11 Rotary encoder for volume
- 13 Keys, 12 for macros and 1 for swapping layers
- [VIA](https://www.caniusevia.com/) support

## PCB
My PCB was made using KiCad.

Schematic

<img width="652" height="741" alt="image" src="https://github.com/user-attachments/assets/757308ef-cf28-4c04-881d-3ca06773f527" />


PCB

<img width="448" height="675" alt="Screenshot 2026-09-27 125154" src="https://github.com/user-attachments/assets/e24e6084-20a6-43c6-a953-92a11e9fc1f3" />


I used [Joe Scotto's](https://www.youtube.com/@joe_scotto) footprints for all of them.

## CAD Model
Everything fits together using 4 M3 Bolts and heatset inserts.

It has 4 different pieces, Top Case, Bottom Case, Plate, and a Rotary Encoder Knob

<img width="1022" height="836" alt="Screenshot 2026-10-03 101123" src="https://github.com/user-attachments/assets/dc530c12-921b-49e6-b8b0-c1ee5b0dd392" />


This model was made in Fusion 360 by Autodesk.

## Firmware
This macropad uses [QMK](https://qmk.fm/) firmware for its code.
- 13 keys; 12 for macros, 1 for layers
- Rotary encoder used to change volume

## BOM:
Here is everything that is needed to make this macropad

- 13x MX Style Switches
- 13x DSA Keycaps
- 14x 1N4148 DO-35 Diodes.
- 1x  Rotary encoder
- 4x  M3 Bolts
- 4x  Heatset Inserts
- 1x  Case (Top Case, Bottom Case, Plate, Knob)
