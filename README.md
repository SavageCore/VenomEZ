# VenomEZ
> GP2040-CE powered EZ Mod for Venom PS3/PS4 Arcade Stick

**UNTESTED** - do not order yet! All I've done is printed the edge cuts on paper and confirmed it *should* fit. It's the same dimensions as the original PCB.

"EZ" mod for the [Venom PS3/PS4 Arcade Stick](https://imgur.com/rmCg5gm), using the RP2040 microcontroller and [GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE) firmware. It's a drop-in replacement for the existing PCB, apart from the change to a USB-C connector.

![VenomEZ](https://github.com/SavageCore/VenomEZ/assets/171312/d6262efd-f4ef-4d3f-9a7a-6b57e9fd4318)
![VenomEZ-back](https://github.com/SavageCore/VenomEZ/assets/171312/23bb95b7-9ebc-49e4-9492-49424b47dde7)


## Ordering your own boards

1. Go to [JLCPCB](https://jlcpcb.com/)

2. Click on `Instant Quote`

3. Click on `Add Gerber file` and choose the file named `GERBER-VenomEZ.zip`
 from [Releases](https://github.com/SavageCore/VenomEZ/releases/latest)

4. Choose the following options for the board:

* Base Material = FR-4
* Layers = 2
* Dimensions = (should auto-populate) 71.97 mm x 41.99 mm
* PCB Qty = 5 (or more)
* Product Type = Industrial/Consumer electronics
* Different Design = 1
* Delivery Format = Single PCB
* PCB Thickness = 1.6
* PCB Color = Whatever you want
* Silkscreen = N/A
* Surface Finish = HASL(with lead)
* Outer Copper Weight = 1oz
* Via Covering = Tented
* Board Outline Tolerance = +/- 0.2mm (Regular)
* Confirm Production file = Yes
* **Remove Order Number = Specify a location**
* Flying Probe Test = Fully Test
* Gold Fingers = No
* Castellated Holes = No

Advanced options: (I left these as default)

* 4-Wire Kelvin Test = No
* Paper between PCBs = No
* Appearance Quality = IPC Class 2 Standard
* Silkscreen Technology = Ink-jet/Screen Printing Silkscreen
* Package Box = With JLCPCB logo

PCB Assembly:

* PCBA Type = Economic
* Assembly Side = Top Side
* PCBA Qty = (the same as PCB Qty)
* Tooling holes = Added by JLCPCB
* Confirm Parts Placement = Yes


## This is what we're replacing:

![PXL_20230706_222544935](https://github.com/SavageCore/VenomEZ/assets/171312/070c1cbe-40d9-4150-9416-02d24ce2f595)

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
