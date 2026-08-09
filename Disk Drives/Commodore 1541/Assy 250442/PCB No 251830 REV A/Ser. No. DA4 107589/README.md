<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Commodore 1541

![Name](https://img.shields.io/badge/Serial_No.-DA4_107589-white?style=plastic)
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
      <a href="#initial-testing">Initial testing</a>
    </li> 
    <li>
      <a href="#mainboard">Mainboard</a>
        <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#cleaning-the-pcb">Cleaning the PCB</a>
        </li>
        <li>
          <a href="#voltages">Voltages</a>
        </li>
        </ul>
    </li> 
    <li>
      <a href="#drive-mechanics">Drive mechanics</a>
        <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#rw-head-and-stepper-motor">RW Head and Stepper Motor</a>
        </li>
        <li>
          <a href="#cleaning">Cleaning</a>
        </li>
        <li>
          <a href="#track-1-position">Track 1 position</a>
        </li>
        </ul>
    </li>
    <li>
      <a href="#installing-professional-dos">Installing Professional DOS</a>
        <ul>
        <li>
          <a href="#moving-some-capacitors">Moving some capacitors</a>
        </li>
        <li>
          <a href="#installing-the-pcbs">Installing the PCBs</a>
        </li>
        </ul>
    </li>
    <li>
      <a href="#casing">Casing</a>
        <ul>
        <li>
          <a href="#cleaning-the-covers">Cleaning the covers</a>
        </li>
        <li>
          <a href="#retrobrighting">Retrobrighting</a>
        </li>
        </ul>
    </li>     
    <li>
      <a href="#testing">Testing</a>
    </li>     
  </ul>
</details>

# Starting point

Another nice-looking Commodore 1541 Single Drive Floppy Disk in for some TLC! But not only that... a Professional DOS speeder will also be installed. It is expected to be fully working from the start, but it will be tested thoroughly during the refurbishment.

It appears to be in good condition. I cannot see any signs of damage. There are some occasional marks, but nothing serious. There are signs of some dust and greast both on the inside and outside , but nothing severe. The covers are slightly yellowed.

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

- [x]Refurbish the mainboard
- [x]Refurbish the internal mechanics
- [ ]Install the Professional DOS speeder
- [ ]Refurbish the casing
- [ ]Testing and validation

The plan may be updated during the refurbishment process. Sometimes I discover areas that need special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK START -->

# Disassembly

The first step in disassembling the Commodore 1541 floppy drive is to remove the four Phillips machine screws[^1] on the bottom.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="1000">
</p>

The drive is flipped back over, and the top cover is removed. This reveals the mainboard and parts of the internal mechanics.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="1000">
</p>

It is very nice to see that several of the custom ICs are in socket. This will make installation of Professional DOS, or any repair, easier.

The next step is to remove the mainboard from the drive. There are seven Phillips machine screws[^2] holding the mainboard to the bottom chassis (see arrows in the picture above). Note that two of these screws are located on the large heat sink for the voltage regulators. Also, there is a tooth washer for each of the seven screws.

Before the mainboard can be lifted, the connectors at P4, P5, P6, and P7 must be disconnected.

With the mainboard out of the way, the entire internal mechanism is exposed.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="1000">
</p>

Now the inner tray is lifted from the bottom cover. This is done by removing the six Phillips screws[^3] located on each side of the tray (see arrows in the picture above). Below is a picture of the remaining bottom cover.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="1000">
</p>

To remove the drive itself from the tray, the four Phillips screws[^4] (two on each side of the drive) are removed, as shown below.

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="500">
</p>

Finally, the LED is removed from the bottom cover. This is quite straightforward, but a good tip is to firmly press the LED from the outside towards the inside until it "pops out". See pictures below.

<p align="center" float="left">
    <img src="Images/Dis_07.jpeg" alt="Description" width="325">
    <img src="Images/Dis_08.jpeg" alt="Description" width="325">
    <img src="Images/Dis_09.jpeg" alt="Description" width="325">
</p>

<p align="center">
    <img src="Images/Dis_10.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Initial testing

Initial testing of the 1541 floppy drive is performed about midway through the disassembly and after some initial cleaning of the PCB and the R/W head. This is done to assess the condition of the floppy drive and use this information as input for the refurbishment process.

Below is a table showing the results of this initial testing.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | PASSED | 300.3 RPM|
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| PASSED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | PASSED | Track 0: "EXCELLENT" |

</div>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is Assy 250422 / PCB No. 251830 Rev A, also marked "R-7HB". Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="1000">
</p>

## Visual inspection

The mainboard appears to be in generally good condition. During the visual inspection, this is what I notice:

- There is a layer of dust and grease across the entire mainboard
- Pin #20 on MOS 6522 VIA IC in position UC3 is bent and not properly socketed
- The above mentioned VIA IC has a very different date code than the rest

I think that it is a fair assumption that this 1541 floppy drive has been repaired previoulsy, and that one of the VIA ICs were replaced.

Below is a picture with a close-up of the VIA chip from these findings.

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="600">
</p>

The table below lists all major custom ICs found on the mainboard. As shown, the MOS chips were produced between week 22 of 1983 and week 30 of 1984. But since the assumption is that the VIA #1 chip was replaced at some time, I think that it is a fair guess that this Commodore 1541 floppy drive drive was manufactured during the autumn of 1984.

<div align="center">
    
| Chip | Version | Date code | Position | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS 6502B | W29 Y1984 | UC4 | Yes |  |
| VIA #1 | MOS 6522 | W22 Y1983 | UC3 | Yes |  | 
| VIA #2 | MOS 6522A | W30 Y1984 | UC2 | Yes |  |
| Drive logic IC | MOS 325572-01 | Unknown | UC1 | No | |
| DOS ROM#1 | GI 9464B-0841 <BR>901229-05 | W24 Y1984 | UB4 | Yes | |
| DOS ROM#2 | MOS 325302-01 | W23 Y1984 | UB3 | Yes | |
| SRAM | FUJITSU MB8128-15 | W28 Y1984 | UB2 | No | |

</div>

<div align="center">

| Glue logic | Comment |
|:----------:|:----------:|
| SGS Thomson, EL, Hitachi, Mitsubishi, Fairchild, Texas Instruments, Signetics, National Semiconductor | No MOS glue logic |

</div>

## Cleaning the PCB

The PCB is cleaned properly with mild soapy water. This removes most of the dust and grease on the PCB.

<p align="center">
    <img src="Images/Main_04.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Main_05.jpeg" alt="Description" width="1000">
</p>

There are some old flux residue near the serial interface connectors and the voltage regulators. Even if this is (probably) some sort of "no-clean" flux used when the drive was manufactured it is still good practice to remove this old flux residue.

<p align="center" float="left">
    <img src="Images/Main_06.jpeg" alt="Description" width="500">
    <img src="Images/Main_07.jpeg" alt="Description" width="500">
</p>

<p align="center" float="left">
    <img src="Images/Main_08.jpeg" alt="Description" width="500">
    <img src="Images/Main_09.jpeg" alt="Description" width="500">
</p>

## Voltages

The 1541 disk drive is supplied by two voltages: 12 VDC and 5 VDC. These are transformed, rectified, and regulated inside the drive. The table below lists the measured voltages.

<div align="center">
    
| Area | Target voltage | Measured voltage<br>(Before refurbish) | Measured voltage<br>(After refurbish) | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Regulated 5V | 5 VDC | 5.047 V | 5.047 V| Measured at C5 |
| Regulated 12V | 12 VDC | 12.08 V | 12.09 V| Measured at C2 |

</div>


[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Drive mechanics

This floppy drive is equipped with the ALPS drive mechanism, which is reputed to be more reliable than the Newtronics drive mechanism. Not necessarily because of the mechanism itself, but because the R/W head is less likely to fail.

<p align="center">
    <img src="Images/Drive_01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Drive_02.jpeg" alt="Description" width="1000">
</p>

## Visual inspection

The table below shows the versions of this ALPS drive mechanism, as well as the stepper and spindle motors.

<div align="center">
    
| Device | Manufacturer | Model | Serial | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Drive mechanism | Alps Electric Co. | FDM2111-B2 | 01772971 |  |
| Step motor | Alps Electric Co. | AP-68 | 933786  |  |
| Spindle motor | COPAL | LC-177B | 8474-2 |  |

</div>

## RW Head and Stepper Motor

It is good practice to measure the resistance of the Read/Write (R/W) coil, the erase coil, and the stepper motor. Even if initial testing shows that these appear to be working as they should, it is useful to confirm that the measured resistances are also within acceptable tolerances.

From the [*Service Manual Model 1540/1541 Disk Drive*](https://refurbished-commodore.com/reference-documents), we can find the nominal values for the R/W coil and the erase coil:

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/RW%20Head.png" alt="Description" width="800">
</p>

The measured resistance values of the R/W coil and erase coil at connector P8 are listed in the table below.

<div align="center">
    
| Check | Description | Target | Measure | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| R/W coil | End-to-end (Blue-Red) | 32.4 Ω | 32.55 Ω|  |
| R/W coil | End-to-centertap #1 (Blue-White) | 16.3 Ω | 17.27 Ω |  |
| R/W coil | End-to-centertap #2 (Red-White) | 16.3 Ω | 16.61 Ω |  |
| Erase coil | End-to-end (Yellow-White) | 10.5 Ω | 10.87 Ω |  |

</div>

From the same service manual, we can find the nominal values for the stepper motor:

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/StepperMotor.png" alt="Description" width="700">
</p>

The measured resistance values of the stepper motor coil at connector P7 are listed in the table below.

<div align="center">
    
| Check | Description | Target | Measure | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Stepper motor coil (A) | End-to-end (Yellow-Orange) | 64.0 Ω | 65.64 Ω|  |
| Stepper motor coil (A) | End-to-centertap #1 (Yellow-Red) | 32.0 Ω | 33.24 Ω |  |
| Stepper motor coil (A) | End-to-centertap #2 (Orange-Red) | 32.0 Ω | 32.95 Ω |  |
| Stepper motor coil (B) | End-to-end (Brown-Black) | 64.0 Ω | 65.43 Ω|  |
| Stepper motor coil (B) | End-to-centertap #1 (Brown-Red) | 32.0 Ω | 32.87 Ω |  |
| Stepper motor coil (B) | End-to-centertap #2 (Black-Red) | 32.0 Ω | 33.14 Ω |  |

</div>

As can be seen from the tables above, all measured resistances are within acceptable tolerances.

## Cleaning

The drive is properly cleaned with isopropanol and a Q-tip. There is not much dust and grease, but it is cleaned nonetheless. Both the R/W head and the two rails it slides on are cleaned with isopropanol also.

<p align="center">
    <img src="Images/Drive_03.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Drive_04.jpeg" alt="Description" width="600">
</p>

## Track 1 position

Another good practice is to check and measure the track 1 position. The nominal value for the track 1 position is a gap of 0.35 mm (from the full stop at track 0), as shown in the schematic below.

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/Track1.png" alt="Description" width="700">
</p>

It is not trivial to measure the gap exactly, but with a feeler gauge, the gap is measured to be approximately 0.30 mm. That is a bit less than optimal target. Whether or not this has any impact on the drive we will find out during testing. See the picture below.

<p align="center">
    <img src="Images/Drive_05.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Installing Professional DOS

Traditionally, the 1541 floppy drive is very slow. This is due to the non-optimised serial communication between the floppy drive and the Commodore 64. Luckily, there are solutions often referred to as speeders (such as Professional DOS) that utilise the user port and parallel communication between the Commodore 64 and the 1541 floppy drive. These speeders can achieve loading times that are substantially faster than those obtained with other fast-load systems such as JiffyDOS or Action Replay.

The Professional DOS PCBs, which will be installed inside the 1541 floppy drive, are shown in the pictures below. Note that there are two PCBs to be installed:

- The main speeder board which will be installed in the CPU socket (UC4)
- A breakout board which will be installed in the VIA socket (UC3)

<p align="center">
    <img src="Images/ProfDOS_01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/ProfDOS_02.jpeg" alt="Description" width="1000">
</p>

**NOTE:** For the Professional DOS to function, the old DOS-ROM IC must be removed (901229-05 in UB4).

## Moving some capacitors

To be able to install the mainboard and breakout PCBs, some ceramic capacitors needs to be moved from the top side of the 1541 mainboard to the bottom side: **C24**, **C27** and **C28**. This is to make room for the PCBs to fit properly. See pictures below.

<p align="center">
    <img src="Images/ProfDOS_03.jpeg" alt="Description" width="1000">
</p>

<p align="center" float="left">
    <img src="Images/ProfDOS_04.jpeg" alt="Description" width="325">
    <img src="Images/ProfDOS_05.jpeg" alt="Description" width="325">
    <img src="Images/ProfDOS_06.jpeg" alt="Description" width="325">
</p>

Below is a picture of all the three ceramic capacitors, C24/C27/C28, installed at the backside of the mainboard.

<p align="center">
    <img src="Images/ProfDOS_07.jpeg" alt="Description" width="1000">
</p>

## Installing the PCBs

The installation is done in the following order:

- Breakout board installed in the VIA socket (UC3)
- DOSROM (901229-05 in UB4) and CPU (UC4) removed
- Main speeder PCB installed in the UC4 socket.

**NOTE:** A small insulated cardboard shield (from an old Commodore 64 shield) is fitted between the speeder PCB and the 1541 mainboard.

Below are some pictures from the installation.

<p align="center">
    <img src="Images/ProfDOS_08.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/ProfDOS_09.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/ProfDOS_10.jpeg" alt="Description" width="600">
</p>

## Installing the drive ROM switch

A nice, and important, feature of Professional DOS is that it can run both the Professional DOS ROM Kernal and the standard Commodore 1541 ROM Kernal. Switching between these two ROMs is normally done using a selector jumper on the PCB. When the jumper is closed, the Professional DOS is selected; when it is open, the standard Commodore 1541 ROM is selected.

To avoid having to open the drive each time a different ROM is required, a small microswitch is installed. The microswitch requires a 6 mm hole to be drilled in the front of the drive (on the right-hand side). Two Dupont wires are connected to the jumper and soldered to the switch.

<p align="center">
    <img src="Images/ProfDOS_11.jpeg" alt="Description" width="600">
</p>


[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

Both the top and bottom covers are in good condition from a mechanical perspective. They are a bit dirty, or more precisely, covered with a thin layer of grease. Parts of the covers are also slightly yellowed.

## Cleaning the covers

The covers are cleaned with mild soapy water. The cleaning process consists of soaking the covers in the soapy water for a couple of days, which dissolves most of the grease.

Note that the metal badge on the front of the drive is removed before cleaning begins. To remove the badge, hot air from a hair dryer is applied while it is carefully pried off the cover using a selection of spudgers.

Below are some pictures of the covers after cleaning, along with the removed badge.

<p align="center">
    <img src="Images/Case_01.jpeg" alt="Description" width="800">
</p>

And the removed metal badge.

<p align="center">
    <img src="Images/Case_03.jpeg" alt="Description" width="800">
</p>

## Retrobrighting

The covers are not severely yellowed, but there are areas where some yellowing is present. Therefore, both the top and bottom covers are retrobrighted using 12% hydrogen peroxide cream and exposed to UV light for about 12 hours.

**Note:** Before retrobrighting, the rubber feet are removed. If they are left in place during the process, they can become soft and "mushy".

<p align="center">
    <img src="Images/Case_04.jpeg" alt="Description" width="800">
</p>

The result from retrobrighting is quite good as most of the yellowing is gone.

<p align="center">
    <img src="Images/Case_05.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Testing

The proof is in the pudding — does it work?

The purpose of this stage is to test and verify that the 1541 floppy disk drive works as it should. The basic functionality tested earlier is re-tested and verified. A combination of software tools is used in this process; please see the description of the [tools](https://refurbished-commodore.com/tools).

The table below shows the results of the testing performed using the standard CBM DOS and CBM Kernal.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | PASSED | 297.8 RPM|
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| PASSED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | PASSED | Track 0: "EXCELLENT" |

</div>

The table below shows the results of testing performed using selected speeder ROMs on both the computer and drive sides. The software used for this testing is the 64'er Floppy Speed Tester.

<div align="center">
    
| Action | Time | Factor | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Picture show(*) | 00:34 | N/A |  |
| Format | 00:18.8 | 3.96 |  |
| Program LOAD | 00:09.2 | 14.89 |  |
| Program SAVE | 00:04.4 | 28.86 |  |
| SEQ WRITE | 00:16.0 | 5.38 |  |
| SEQ READ | 00:14.7 | 5.17 |  |
| REL CREATE | 00:28.3 | 4.17 |  |
| Validate | 00:09.8 | 6.73 |  |
| Scratch files | 00:19.6 | 3.52 |  |
| Data transfer | 00:17.0 | 4.24 |  |
| 64´er-factor |   | 11.2 |  |

</div>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


<!-- MARK END -->

**Footnotes**
[^1]: Phillips pan head (6.8 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.6 mm
[^2]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 5.5 mm (and tooth washer)
[^3]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.2 mm
[^4]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.6 mm
[^5]: 1541/1571 Drive alignment from Free Spirit software (Probably fake)
[^6]: 1541 Test & Diagnostics cartridge from World of Jani
[^7]: Original Commodore test/demo-diskette for model 1541
