# VenomEZ
> GP2040-CE powered EZ Mod for Venom PS3/PS4 Arcade Stick

**UNTESTED** - do not order yet! All I've done is printed the edge cuts on paper and confirmed it *should* fit. It's the same dimensions as the original PCB.

"EZ" mod for the [Venom PS3/PS4 Arcade Stick](https://imgur.com/rmCg5gm), using the RP2040 microcontroller and [GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE) firmware. It's a drop-in replacement for the existing PCB, apart from the change to a USB-C connector.

![VenomEZ](https://github.com/SavageCore/VenomEZ/assets/171312/d36bae48-fc1e-4f05-b7f6-0b4c7f334deb)
![VenomEZ-back](https://github.com/SavageCore/VenomEZ/assets/171312/1b91df46-6774-4d86-97a6-d9af2606d588)


## Pins

| GPIO | Function |
| --- | -------- |
17 | Up
16 | Down
14 | Left
15 | Right
5 | B1 / A / B / Cross / 2 / K1
6 | B2 / B / A / Circle / 3 / K2
13 | R2 / RT / ZR / R2 / 8 / K3
11 | L2 / LT / ZL / L2 / 7 / K4
7 | B3 / X / Y / Square / 1 / P1
8 | B4 / Y / X / Triangle / 4 / P2
12 | R1 / RB / R / R1 / 6 / P3
10 | L1 / LB / L / L1 / 5 / P4
19 | S1 / Back / Minus / Select / 9 / Coin
18 | S2 / Start / Plus / Start / 10 / Start
9 | A1 / Guide / Home / PS / 13 / ~
20 | A2 / ~ / Capture / ~ / 14 / ~
21 | Turbo
25 | Turbo LED
41 | Player LED 1
40 | Player LED 2
39 | Player LED 3
38 | Player LED 4
22* | LS/RS Toggle Switch
23* | Turbo 1/2 Toggle Switch
24* | PS3/PS4 Toggle Switch

\* These pins are not mapped to anything in the firmware but are available for use with add-ons.

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
