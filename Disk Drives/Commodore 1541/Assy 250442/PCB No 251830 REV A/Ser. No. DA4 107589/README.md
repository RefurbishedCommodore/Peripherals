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
   </ul>
</details>

# Starting point

Another nice-looking Commodore 1541 Single Drive Floppy Disk in for some TLC! But only that... a Professional DOS speeder will also be installed. It is expected to be fully working from the start, but it will be tested thoroughly during the refurbishment.

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
- [ ]Install the Dolphin DOS 3.0 speeder
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

# Initial testing

Initial testing of the 1541 floppy drive is performed about midway through the disassembly and after some initial cleaning of the PCB and the R/W head. This is done to assess the condition of the floppy drive and use this information as input for the refurbishment process.

Below is a table showing the results of this initial testing.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | FAILED | 297.8 RPM|
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

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


<!-- MARK END -->

**Footnotes**
[^1]: Phillips pan head (6.8 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.6 mm
[^2]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 5.5 mm (and tooth washer)

[^5]: 1541/1571 Drive alignment from Free Spirit software (Probably fake)
[^6]: 1541 Test & Diagnostics cartridge from World of Jani
[^7]: Original Commodore test/demo-diskette for model 1541
