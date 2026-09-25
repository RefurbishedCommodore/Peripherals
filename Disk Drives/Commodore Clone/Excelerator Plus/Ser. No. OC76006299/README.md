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
      <a href="#initial-testing">Initial testing</a>
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

# Initial testing

Initial testing of the Excelerator floppy drive is performed about midway through the disassembly and after some initial cleaning of the PCB and the R/W head. This is done to assess the condition of the floppy drive and use this information as input for the refurbishment process.

Below is a table showing the results of this initial testing.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | TBA | |
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| FAILED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "TBA" |
| Head stop | Checking the position of track 0[^7] | FAILED | Track 0: "TBA" |

</div>

The "Passed/Failed" status is set to "INCONCLUSIVE" for the following reason:

- When the floppy drive is powered on, the motor does not always spin up. It seems like this happens when the floppy drive is "cold" (not started for a while). The combined power/activity LED does seem to work fine every time.

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

The mainboards appears to be in general good condition. I cannot see any signs of rework from previous repairs. There is a significant layer of dust and grease on the PCB. Nevertheless, there are some areas which may require further attention:

- Two of the electrolytic capacitors, C5 and C13, on PCB #01 have partly lost their outer insulation
- Four of the ICs on PCB #03 and one IC on PCB #01 are not soldered flush to the PCB
- Soldering points on the J7 input power connector look dried out

Below is a gallery of some of the findings from the visual inspection.

<p align="center">
    <img src="Images/Main_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_07.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_08.jpeg" alt="Description" width="800">
</p>

## Checking the voltages

Voltages are measured before—and after—refurbishment. This is to ensure that all voltages are within acceptable levels. The table is updated after the refurbishment is completed. 

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 4.768 V | TBD  V | Connector J1 PIN#1 |
| PSU (12V) | 12 V DC | 11.98 V / 0 V (*) | TBD V | Connector J1 PIN#4 |

</div>

(*) This measured voltage is equal to 0 V when disk motor is not starting.

**NOTE:** There is obviously something wrong with the 12 V voltage supply.

# PSU adapter cable

The Excelerator Plus floppy drive use a + 5VDC / + 12 VDC power supply (PSU) with a 5-pin DIN connector, but compared to a traditional 1541-II PSU the + 5 / + 12 volt pins are available on a 4-pin DIN connector. Since this very floppy drive did no longer have the PSU that came with it, a solution is made: a PSU adapter cable is made. This cable will be connected to a standard 1541-II PSU (preferably a modern version) so that it can be used with the Excelerator Plus drive.

Below is the schematics for the 1541-II PSU with the 4-pin DIN connector pinout. **NOTE:** the pinout is for the male connector - seen from the outside of the plug connector.

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/1541-II-powersupply.gif" alt="Description" width="800">
</p>

The 5-pin DIN connector which is to be used on the Excelerator side have the pinout as shown below - seen from the outside of the plug connector.

<p align="center">
    <img src="Images/5_DIN.png" alt="Description" width="400">
</p>

Below is a picture of the final PSU adapter cable.

<p align="center">
    <img src="Images/Main_05.jpeg" alt="Description" width="600">
</p>

<!-- MARK STOP -->


**Footnotes**
[^1]: JIS pan head (5.4 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm (plus flat washer and spring lock washer)

