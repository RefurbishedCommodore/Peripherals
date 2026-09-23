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
        <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#voltages">Voltages</a>
        </li>
        </ul>
    </li>
    <li>
      <a href="#psu-adapter-cable">PSU adapter cable</a>
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

There are four, interconnécted, PCBs in the Excelerator Plus floppy drive which makes up the drive electronics. The PCBs are numbered from 1-4 (my definition), and have the following functionality (my definitions and assumptions).

<div align="center">
    
| PCB | Name | Description |
|:----------:|:----------:|:----------:|
| PCB #01 | R/W Receive and transmit | Responsible for amplifying signal from read/write head, and transmit digital signals to the read/write head. <BR> Control for rotational speed.  |
| PCB #02 | Servo | Responsible for controlling the servo motor |
| PCB #03 | Clock generator | Responsible for generating the CPU clock |
| PCB #04 | Main logic board | CPU, ROM and glue logic |

</div>

Below is a gallery of the above mentioned PCBs.

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

## Visual inspection 

# PSU adapter cable

The Excelerator Plus floppy drive use a + 5VDC / + 12 VDC power supply (PSU) with a 5-pin DIN connector, but compared to a traditional 1541-II PSU the + 5 / + 12 volt pins are available on a 4-pin DIN connector. Since this very floppy drive did no longer have the PSU that came with it, a solution is made: a PSU adapter cable is made. This cable will be connected to a standard 1541-II PSU (preferably a modern version) so that it can be used with the Excelerator Plus drive.

Below is the schematics for the 1541-II PSU with the 4-pin DIN connector pinout. **NOTE:** the pinout is for the male connector - seen from the outside of the plug connector.



<!-- MARK STOP -->


**Footnotes**
[^1]: JIS pan head (5.4 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm (plus flat washer and spring lock washer)

