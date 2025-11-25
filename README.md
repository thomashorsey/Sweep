# Sweep
![](./front.png)
![](./back.png)

## Ordering The PCB

To order the PCB the following settings are recommended: 

|Detail|Value|
|---|---|
|Gerber file|`sweepv2.X_gerber.zip`|
|Base material|FR-4|
|Layers|2|
|Dimension|216.9mm x 86.9mm|
|Different design|2|
|Delivery format|Panel by customer|
|PCB thickness|1.6mm|
|PCB color|(Personal preference)|
|Silkscreen|(Personal preference)|
|Surface finish|(Personal preference)|
|Outer copper weight|1oz|
|Gold Fingers|No|
|Confirm production file|No|
|Castellated holes|No|
|Remove order number|Yes|

1: Settings are for [JLCPCB](https://jlcpcb.com/), but could work for other manufacturers.

2: Settings are taken from [Kyek's video guide](https://www.youtube.com/watch?v=fBPu7AyDtkM&t=17s).

## Components List

To build and use a Sweep you will need:

* 1x PCB Kit
* 2x nice!nanos
* 2x IC header strip (M)
* 2x IC header strip (F)
* 1x TRRS Cable
* 2x TRRS Jack [PJ-320A]
* 1 USB C Cable
* 34 choc v1 switches
* 34 keycaps (including 2 homing keycaps)
* Some little rubber feet/bumpers

## Build Guide

https://www.youtube.com/watch?v=fBPu7AyDtkM

## Firmware

The firmware can be found [with the Ferris firmware as part of QMK](https://github.com/qmk/qmk_firmware/tree/master/keyboards/ferris/sweep).

Firmware for zmk and bluemicro_ble is called ["Cradio"](https://zmk.dev/docs/hardware/).

## Who made this?

This repo is a direct fork of the wonderful work done by davidphilipbarr here: https://github.com/davidphilipbarr/Sweep