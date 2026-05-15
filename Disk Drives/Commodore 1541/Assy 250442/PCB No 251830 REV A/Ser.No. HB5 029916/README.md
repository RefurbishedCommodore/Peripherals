<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Commodore 1541

![Name](https://img.shields.io/badge/Serial_No.-HB5_029916-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Brand-ALPS-white?style=plastic)
![Name](https://img.shields.io/badge/Model-1541-white?style=plastic)

# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#refurbishment-activities">Refurbishment activities</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
        <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        </ul>
    </li>
  </ul>
</details>

# Starting point

This nice-looking Commodore 1541 Single Drive Floppy Disk is in for some TLC, but also to have a Dolphin DOS 3 speeder installed. It is expected to be fully working from the start, but it will be tested thoroughly during the refurbishment.

It appears to be in good condition. I cannot see any signs of damage. There are some occasional marks, but nothing serious. There are signs of some dust on the inside, but very little.

Also, this is, in my opinion, the "right" version of the Commodore 1541 floppy drive. The characteristic front with the closing lid indicates that this 1541 drive is built with the ALPS drive mechanism. The ALPS drive mechanism is more likely to have a working R/W head.

Below are some pictures of the drive before refurbishment.

<p align="center">
    <img src="Images/Start01.jpeg" alt="Description" width="600">
    <img src="Images/Start02.jpeg" alt="Description" width="600">
    <img src="Images/Start03.jpeg" alt="Description" width="600">
    <img src="Images/Start04.jpeg" alt="Description" width="600">
    <img src="Images/Start05.jpeg" alt="Description" width="600">
    <img src="Images/Start06.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Refurbishment activities

The planned refurbishment activities for this Commodore 1541 Single Drive Floppy Disk (order may vary; several activities may be performed in parallel):

- [ ]Refurbish the mainboard
- [ ]Refurbish the casing
- [ ]Refurbish the internal mechanics
- [ ]Install the Dolphin DOS 3.0 speeder
- [ ]Testing and validation

The plan may be updated during the refurbishment process. Sometimes I discover areas that need special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

The first step in disassembling the Commodore 1541 floppy drive is to remove the four Phillips machine screws[^1] on the bottom.

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="1000">
</p>

The drive is flipped back over, and the top cover is removed. This reveals the mainboard and parts of the internal mechanics.

<p align="center">
    <img src="Images/Dis02.jpeg" alt="Description" width="1000">
</p>

The next step is to remove the mainboard from the drive. There are seven Phillips machine screws[^2] holding the mainboard to the bottom chassis (see arrows in the picture above). Note that two of these screws are located on the large heat sink for the voltage regulators. Also, there is a tooth washer for each of the seven screws.

Before the mainboard can be lifted, the connectors at P4, P5, P6, and P7 must be disconnected.

Something to note: one of the seven screws is heavily oxidized. Could this be a sign that the drive has been exposed to moisture? The remaining six screws still have their fine brass appearance.

<p align="center">
    <img src="Images/Dis05.jpeg" alt="Description" width="600">
</p>

With the mainboard out of the way, the entire internal mechanism is exposed.

<p align="center">
    <img src="Images/Dis03.jpeg" alt="Description" width="1000">
</p>

Now the inner tray is lifted from the bottom cover. This is done by removing the six Phillips screws[^3] located on each side of the tray (see arrows in the picture above). Below is a picture of the remaining bottom cover.

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is Assy 250422 / PCB No. 251830 Rev A, also marked "MDK 511HB". Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Main02.jpeg" alt="Description" width="1000">
</p>

## Visual inspection

The mainboard appears to be in generally good condition. During the visual inspection, this is what I notice:

- There is a layer of dust and grease across the entire mainboard.
- The glue holding the large electrolytic capacitors (C16 and C17) has dried out.
- No observable leakage from any of the capacitors.
- Some residue on the backside of the PCB that does not appear to be normal flux residue.
- The P4 pin connector is different from the others. This may be normal, but the effect is that the cable connector does not sit properly when attached.

Below are pictures with close-ups of some of these findings.

<p align="center">
    <img src="Images/Main03.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Main04.jpeg" alt="Description" width="600">
</p>

<p align="center" float="left">
    <img src="Images/Main05.jpeg" alt="Description" width="335">
    <img src="Images/Main06.jpeg" alt="Description" width="300">
</p>

<div align="center">
    
| Chip | Version | Date code | Position | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS 6502AD | W52 Y1986 | UC4 | No |  |
| VIA #1 | MOS 6522 | W12 Y1987 | UC3 | No |  | 
| VIA #1 | MOS 6522 | W12 Y1987 | UC2 | No |  |
| Drive logic IC | MOS 325572-01 | W04 Y1987 | UC1 | No | |
| DOS ROM#1 | MOS 901229-05 | Unknown | UB4 | No | |
| DOS ROM#2 | MOS 325302-01 | Unknown | UB3 | No | |
| SRAM | SANYO LC3517A-15 | Unknown | UB2 | No | |

</div>

<div align="center">

| Glue logic | Comment |
|:----------:|:----------:|
| Mitsubishi, Hitachi, Texas Instruments, Signetics, National Semiconductor | No MOS glue logic |

</div>

<!-- MARK -->
<!-- MARK END-->

**Footnotes**
[^1]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 7.5 mm
[^2]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 5.5 mm (and tooth washer)
[^3]: Phillips pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.6 mm




