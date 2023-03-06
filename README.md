# SCHIFFRE

The Schiffre project is a mechanical keyboard featuring a host board and shield design, using a Flexible Flat Cable (FFC) as interconnect.

All PCBs designed with Kicad 7.0. Case designed in Fusion.

## COMPONENTS
In this repository you will find everything to build a Schiffre 86 board.

- The host board: `schiffre_nrf`
- The shield PCB: `schiffre_86`
- The switch plate: `schiffre_86_plate`, with files for production from FR4.
- The case: `schiffre_86_case`, designed both for with 3D printing and CNC machining in mind.

In addition there is a breakout board for the 30 pin FFC connector, with a RPi Pico header in `schiffre_pico`.

## BOM
See the production subfolders in the respective folders.
In addition you will need
 - An E73-2G4M08S1C bluetooth module [AliExpress](https://aliexpress.com/item/32944356249.html)
 - One 100mm reversible FFC calbe with 30 pins and .5mm pitch [AliExpress](https://aliexpress.com/item/1005002259855390.html).
 - M3x5.7x4.6 and M2x4x3.6 Heat-set inserts (if 3D printing the case or machining from plastics) [AliExpress](https://www.aliexpress.com/item/4001258499799.html).
 - DIN912 socket head screws: 6x M3x10mm, 4x M2x6mm [AliExpress](https://www.aliexpress.com/item/32810872544.html)
 - A Lipo rechargable battery. There is room for a long, but narrow and thin one. Thickness <= 4mm, and width <= 25mm.
   - 4x20x60mm 600mAh [AliExpress](https://aliexpress.com/item/1005005086965061.html)
   - 4x25x100mm 1200mAh [AliExpress](https://aliexpress.com/item/1005005067026996.html)


## FIRMWARE
ZMK compatible firmware under development.

## PROJECT NAME
*Schiffre* is a combination of the german word *Chiffre* (translation of Cypher, the board this project was based on originally), and the word *Schiff*, which means ship or big boat, reflecting the shape of the keyboard.