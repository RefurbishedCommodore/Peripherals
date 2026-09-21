<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Excelerator Plus Disk Drive

![Name](https://img.shields.io/badge/Serial_No.-OC76006299-white?style=plastic)
<br>

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
    </li>
  </ul>
</details>

<!-- MARK START -->

# Refurbishment activities

The planned refurbishment activites for this Excelerator Plus floppy drive (Order may vary. Several of them in parallel):

- [ ]Refurbish the mainboard
- [ ]Create power supply adapter cable
- [ ]Refurbish the internal mechanics
- [ ]Refurbish the casing
- [ ]Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Starting point

This Commodore clone drive is new to me. I have heard that these drives are renowned for being both robust and less noisy (compared to the original Commodore 1541 floppy drives). From the outside this drive looks well used. There is quite of lot of scratches on the metal casing, and there is a substantial amount of dust and grime on the front bezel. But it seems to be in otherwise good condition. The lever mechanisms appears from the outside to be working.

At the bottom one of the rubber feet is missing - hope that it didn´t disappear during transportation. 

I do not currently know if this drive is working or not, and I do not have the proper power supply - so I need to find a way to power it.

Below are some pictures of the floppy drive before refurbishment.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="800">
    <img src="Images/Start_02.jpeg" alt="Description" width="800">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
    <img src="Images/Start_06.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

Disassembling the Excelerator drive is straightforward. At the bottom of the drive there are four JIS machine screws[^1] (with washers) holding the bottom cover to the rest of the chassis. **NOTE:** Even if these are Japanese Industrial Standard (JIS) screws you can use a normal Phillips screwdriver.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="300">
</p>

With the screws out of the way, the bottom lid can be slid off. Carefully slide it sideways, and then lift it straight up. Now the interior is exposed for the first time - probably since it was manufactured.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

Before the main floppy drive unit can be pulled out, sideways to the right, the left-hand side power switch connector must be disconnected from the PCB. **WARNING:** The connector is NOT keyed, so pay close attention to the direction which it is connected.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="500">
</p>

With the connector out of the way, the whole drive unit is removed from the bottom cover.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="800">
</p>

Removing the power switch is a bit fiddly, but with some gentle pressing of the thin metal plates covering the switch it can be pushed out.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="400">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

There are four, interconnécted, PCBs in the Excelerator Plus floppy drive which makes up the drive electronics. The PCBs are numbered from 1-4 (my definition), see pictures below.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="400">
</p>

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_04.jpeg" alt="Description" width="800">
</p>


<div align="center">
    
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU#1 | MOS | 8502R0 | W17 Y1987 | No |  |
| CPU#2 | ZILOG | Z0840006PSC | W05 Y1987 | No |  |
| SID | MOS | 6581R4AR | W11 Y1987 | Yes | The highly acclaimed version |
| VIC-IIe | MOS | 8566R3 | W19 Y1987 | Yes |  |
| VDC | MOS | 8563R9B | W11 Y1987 | Yes |  |
| MMU | MOS | 8722R2 | W19 Y1987 | Yes |  |
| PLA | MOS | 8721R3 | W14 Y1987 | No |  |
| CIA#1	 | MOS | 6526A | W12 Y1987 | Yes |  |
| CIA#2	 | MOS | 6526A | W12 Y1987 | Yes |  |
| ROM - C64 Kernal | Unknown | 325179-01 | Unknown | Yes | EPROM marked: "C128 64 Nor." |
| ROM - C128 Kernal | Unknown | 325177-03 | Unknown | Yes | EPROM marked: "Nor.Kern.C128" |
| ROM - BASIC LO | MOS | MOS 318018-02 | W09 Y1987 | Yes |  |
| ROM - BASIC HI | MOS | MOS 318019-02 | W10 Y1987 | Yes |  |
| ROM - Character | Unknown | 325178-01 | Unknown | Yes | EPROM marked: "C128 Char.Nor." |
| RAM | SAMSUNG | KM4164B-15 | Unknown | No | |
| Glue logic | MATSUSHITA, FAIRCHILD, TEXAS INSTRUMENTS, NEC, NATIONAL SEMICONDUCTOR |  |  |  | No MOS glue logic |

</div>


<!-- MARK STOP -->


**Footnotes**
[^1]: JIS pan head (5.4 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm (plus flat washer and spring lock washer)

