# Sweep
![](./front.png)
![](./back.png)

This is the main Choc v1 board we all know and love.

## Ordering The PCB

To order the PCB the following settings are recommended<sup>1,2</sup>: 

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

## Components list

To build and use a Sweep you will need:

* 1x PCB Kit
* 2x promicro compatible boards or 2 nice!nanos.
* 34 switches of a compatible type (refer to the compatibility table)
* 34 keycaps
* 2x reset switches (optional; [B3U-1000P(M)](https://github.com/davidphilipbarr/Sweep/issues/20))
* Some little rubber feet/bumpers
* 2x power switches (optional if supported; MSK 12C02)
* 1x TRRS (not TRS!) cable (wired build only)
* 2x TRRS Jack [PJ-320A] (wired build only)
* 1 USB Cable (depends on your micro-controller choice)

## How do I make this thing?

<a href="https://www.youtube.com/watch?v=fBPu7AyDtkM" target="_blank">
  <img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

## Firmware

The firmware can be found [with the Ferris  firmware as part of QMK](https://github.com/qmk/qmk_firmware/tree/master/keyboards/ferris/sweep).

Firmware for zmk and bluemicro_ble is called ["Cradio"](https://zmk.dev/docs/hardware/).

## Who made this?

This repo is a direct fork of the wonderful work done by davidphilipbarr here: https://github.com/davidphilipbarr/Sweep