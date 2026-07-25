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
        </ul>
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

- [ ]Refurbish the mainboard
- [ ]Refurbish the internal mechanics
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

TBD

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
<!-- MARK END -->

**Footnotes**
[^1]: Phillips pan head (6.8 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.6 mm
[^2]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 5.5 mm (and tooth washer)
[^3]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.2 mm
[^4]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.6 mm
[^5]: 1541/1571 Drive alignment from Free Spirit software (Probably fake)
[^6]: 1541 Test & Diagnostics cartridge from World of Jani
[^7]: Original Commodore test/demo-diskette for model 1541
