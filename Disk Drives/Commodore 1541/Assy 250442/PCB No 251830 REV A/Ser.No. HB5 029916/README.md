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
          <a href="#track-1-position">Track 1 position</a>
        </li>
        <li>
          <a href="#removing-corrosion">Removing corrosion</a>
        </li>
        </ul>
    </li>
    <li>
      <a href="#installing-dolphin-dos-3">Installing Dolphin DOS 3</a>
        <ul>
        <li>
          <a href="#desoldering-the-cpu">Desoldering the CPU</a>
        </li>
        <li>
          <a href="#testing-the-dd3-installation">Testing the DD3 installation</a>
        </li>
        <li>
          <a href="#retrofitting-the-dd3-pcb">Retrofitting the DD3 PCB</a>
        </li>
        <li>
          <a href="#installing-the-drive-rom-switch">Installing the drive ROM switch</a>
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
        <li>
          <a href="#retrofitting-the-parallel-cable">Retrofitting the parallel cable</a>
        </li>
        </ul>
    </li>      
    <li>
      <a href="#testing">Testing</a>
    </li>
    <li>
      <a href="#final-result">Final result</a>
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

- [x]Refurbish the mainboard
- [x]Refurbish the internal mechanics
- [x]Install the Dolphin DOS 3.0 speeder
- [x]Refurbish the casing
- [x]Testing and validation

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

When the tray is flipped upside down, something becomes immediately apparent: the drive has been exposed to some kind of liquid at the bottom. There are several large areas of corrosion on the tray. Also, I can see through the tray that the stepper motor has some corrosion as well.

<p align="center">
    <img src="Images/Dis08.jpeg" alt="Description" width="1000">
</p>

Now the inner tray is lifted from the bottom cover. This is done by removing the six Phillips screws[^3] located on each side of the tray (see arrows in the picture above). Below is a picture of the remaining bottom cover.

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="1000">
</p>

To remove the drive itself from the tray, the four Phillips screws[^4] (two on each side of the drive) are removed, as shown below.

<p align="center">
    <img src="Images/Dis06.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Dis07.jpeg" alt="Description" width="500">
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
| Rotation speed | Rotation speed should be 300 RPM[^6] | FAILED | 297.8 RPM|
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| PASSED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | PASSED | Track 0: "EXCELLENT" |

</div>

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
| VIA #2 | MOS 6522 | W12 Y1987 | UC2 | No |  |
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

## Cleaning the PCB

As mentioned earlier, the PCB is quite dirty, and there is some unknown residue as well as dried-out glue.

First, the unknown residue (along with some flux residue) is removed. The residue is quite stubborn and can only be removed by carefully scraping it away with a pick tool. The residue had started to degrade the solder mask, so the damaged solder mask is scraped away. Some transparent nail polish is applied to the affected area after cleaning. Also, the four solder points are re-soldered.

<p align="center">
    <img src="Images/Main07.jpeg" alt="Description" width="800">
</p>

Next, the old dried glue is removed and the PCB is properly cleaned with mild soapy water. This removes most of the old grease and dirt from the PCB. The more stubborn grease is removed with isopropanol.

After the PCB has dried completely, the two capacitors (C16 and C17) are glued back onto the mainboard.

<p align="center">
    <img src="Images/Main08.jpeg" alt="Description" width="700">
</p>

Below are some pictures of the mainboard after cleaning. Note that the QA sticker was removed during cleaning; it will be reinstalled later.

<p align="center">
    <img src="Images/Main09.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Main10.jpeg" alt="Description" width="1000">
</p>

## Voltages

The 1541 disk drive is supplied by two voltages: 12 VDC and 5 VDC. These are transformed, rectified, and regulated inside the drive. The table below lists the measured voltages.

<div align="center">
    
| Area | Target voltage | Measured voltage<br>(Before refurbish) | Measured voltage<br>(After refurbish) | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Regulated 5V | 5 VDC | 5.004 V | 5.002 V| Measured at C5 |
| Regulated 12V | 12 VDC | 12.27 V | 12.28 V| Measured at C2 |

</div>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Drive mechanics

This floppy drive is equipped with the ALPS drive mechanism, which is reputed to be more reliable than the Newtronics drive mechanism. Not necessarily because of the mechanism itself, but because the R/W head is less likely to fail.

<p align="center">
    <img src="Images/Drive01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Drive02.jpeg" alt="Description" width="1000">
</p>

## Visual inspection

Besides the corrosion on the stepper motor, the drive seems to be in good condition. Hopefully, the corrosion is only on the surface of the metal cover on the stepper motor. Also, there is a significant amount of sticky grease in several places on the aluminium frame. The belt seems to be in quite good condition.

The table below shows the versions of this ALPS drive mechanism, as well as the stepper and spindle motors.

<div align="center">
    
| Device | Manufacturer | Model | Serial | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Drive mechanism | Alps Electric Co. | FDM2111-B2 | 01445420 |  |
| Step motor | Alps Electric Co. | AP-68 | 44MOB 468061 |  |
| Spindle motor | COPAL | LC-177B | 8452-2 |  |

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
| R/W coil | End-to-end (Blue-Red) | 32.4 Ω | 33.45 Ω|  |
| R/W coil | End-to-centertap #1 (Blue-White) | 16.3 Ω | 17.43 Ω |  |
| R/W coil | End-to-centertap #2 (Red-White) | 16.3 Ω | 17.24 Ω |  |
| Erase coil | End-to-end (Yellow-White) | 10.5 Ω | 11.53 Ω |  |

</div>

From the same service manual, we can find the nominal values for the stepper motor:

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/StepperMotor.png" alt="Description" width="700">
</p>

The measured resistance values of the stepper motor coil at connector P7 are listed in the table below.

<div align="center">
    
| Check | Description | Target | Measure | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| Stepper motor coil (A) | End-to-end (Yellow-Orange) | 64.0 Ω | 67.44 Ω|  |
| Stepper motor coil (A) | End-to-centertap #1 (Yellow-Red) | 32.0 Ω | ~34 Ω |  |
| Stepper motor coil (A) | End-to-centertap #2 (Orange-Red) | 32.0 Ω | ~36 Ω |  |
| Stepper motor coil (B) | End-to-end (Brown-Black) | 64.0 Ω | 66.20 Ω|  |
| Stepper motor coil (B) | End-to-centertap #1 (Brown-Red) | 32.0 Ω | ~34 Ω |  |
| Stepper motor coil (B) | End-to-centertap #2 (Black-Red) | 32.0 Ω | ~34 Ω |  |

</div>

As can be seen from the tables above, all measured resistances are within acceptable tolerances.

## Track 1 position

Another good practice is to check and measure the track 1 position. The nominal value for the track 1 position is a gap of 0.35 mm (from the full stop at track 0), as shown in the schematic below.

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/Track1.png" alt="Description" width="700">
</p>

It is not trivial to measure the gap exactly, but with a feeler gauge, the gap is measured to be approximately 0.35 mm. See the picture below.

<p align="center">
    <img src="Images/Drive03.jpeg" alt="Description" width="1000">
</p>

## Removing corrosion

As mentioned previously, there is corrosion on the stepper motor casing and on the aluminium frame. To remove the corrosion, the area is first cleaned with isopropanol. Then vinegar is applied to the same area, which will stop the corrosion. Finally, the area is cleaned with a steel brush. This process is repeated several times. Below are some pictures after the corrosion has been removed (or at least most of it).


<p align="center">
    <img src="Images/Drive04.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Drive05.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Drive06.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Installing Dolphin DOS 3

It’s a bird... It’s a plane... It’s Dolphin DOS 3!

Traditionally, the 1541 floppy drive is very slow. This is due to the non-optimised serial communication between the floppy drive and the Commodore 64. Luckily, there are solutions often referred to as speeders that utilise the user port and parallel communication between the Commodore 64 and the 1541 floppy drive. These speeders can achieve loading times that are substantially faster than those obtained with other fast-load systems such as JiffyDOS or Action Replay.

The Dolphin DOS 3 (DD3) PCB, which will be installed inside the 1541 floppy drive, is shown in the pictures below.

<p align="center" float="left">
    <img src="Images/DD3_01.jpeg" alt="Description" width="500">
    <img src="Images/DD3_02.jpeg" alt="Description" width="500">
</p>

There are four things to note about the DD3 PCB:

- A large connector that connects to the 40-pin CPU socket on the 1541 mainboard.
- A smaller connector that connects to the user port on the Commodore 64.
- A jumper that enables DD3 when open and enables the standard ROM when closed.
- The MOS 6502 CPU IC is transferred from the 1541 mainboard to the DD3 PCB.

<p align="center">
    <img src="Images/DD3_03.jpeg" alt="Description" width="800">
</p>

## Desoldering the CPU

As noted in the *Visual Inspection* section, the CPU in position UC4 is not socketed. Therefore, the first step in installing Dolphin DOS 3 is to desolder the MOS 6502 CPU.

No traces or pads were damaged during the desoldering process.

<p align="center" float="left">
    <img src="Images/DD3_05.JPG" alt="Description" width="500">
    <img src="Images/DD3_04.JPG" alt="Description" width="500">
</p>

A new 40-pin socket is installed in position UC4.

<p align="center">
    <img src="Images/DD3_06.JPG" alt="Description" width="800">
</p>

## Testing the DD3 installation

Before the DD3 is installed permanently, it is temporarily installed for testing purposes, as shown in the picture below. The jumper, JP1, is left open, and the wide ribbon cable is connected to the UC4 socket on the 1541 mainboard.

<p align="center">
    <img src="Images/DD3_07.jpeg" alt="Description" width="800">
</p>

The narrow ribbon cable is connected to the user port, and the Dolphin DOS 3.0 Kernal is installed in the Commodore 64.

<p align="center">
    <img src="Images/DD3_08.jpeg" alt="Description" width="800">
</p>

## Retrofitting the DD3 PCB

As easy as it might sound, retrofitting the DD3 PCB is not trivial. There are several things to consider when finding a suitable location for the PCB:

- CPU cable interference: The wide ribbon cable connecting the DD3 PCB to the CPU socket on the mainboard is susceptible to electromagnetic interference.

- Parallel cable length: The ribbon cable connecting the 1541 drive to the Commodore 64 is intentionally kept short to minimise the risk of data corruption. If the PCB is placed closer to the front of the drive, the cable can be made shorter. Furthermore, if the PCB is rotated so that the ribbon cable connector faces the side of the drive, the cable length can be reduced even further.

To reduce the electromagnetic interference affecting the CPU ribbon cable, a custom RF-shielding contraption is fabricated. The shield is made from an old Commodore 64 RF shield and wrapped in insulating tape.

<p align="center">
    <img src="Images/DD3_09.jpeg" alt="Description" width="800">
</p>

With the RF shield in place, the Dolphin DOS 3 PCB is positioned on top of the 1541 mainboard with the parallel cable pointing towards the rear of the drive. The CPU ribbon cable is routed over the RF-shielding contraption and folded down through the gap between the outer 1541 bottom cover and the inner drive chassis.

<p align="center">
    <img src="Images/DD3_10.jpeg" alt="Description" width="800">
</p>

## Installing the drive ROM switch

A nice, and important, feature of Dolphin DOS 3 (DD3) is that it can run both the DD3 ROM Kernal and the standard Commodore 1541 ROM Kernal. Switching between these two ROMs is normally done using a selector jumper on the PCB. When the jumper is open, the DD3 ROM is selected; when it is closed, the standard Commodore 1541 ROM is selected.

To avoid having to open the drive each time a different ROM is required, a small microswitch is installed. The microswitch requires a 6 mm hole to be drilled in the front of the drive (on the right-hand side). Two Dupont wires are connected to the jumper and soldered to the switch.

<p align="center" float="left">
    <img src="Images/DD3_11.jpeg" alt="Description" width="500">
    <img src="Images/DD3_12.jpeg" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/DD3_13.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

Both the top and bottom covers are in good condition from a mechanical perspective. They are a bit dirty, or more precisely, covered with a thin layer of grease. Parts of the covers are also slightly yellowed.

## Cleaning the covers

The covers are cleaned with mild soapy water. The cleaning process consists of soaking the covers in the soapy water for a couple of days, which dissolves most of the grease.

Note that the metal badge on the front of the drive is removed before cleaning begins. To remove the badge, hot air from a hair dryer is applied while it is carefully pried off the cover using a selection of spudgers.

Below are some pictures of the covers after cleaning, along with the removed badge.

<p align="center">
    <img src="Images/Case01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Case02.jpeg" alt="Description" width="800">
</p>

And the removed metal badge.

<p align="center">
    <img src="Images/Case06.jpeg" alt="Description" width="800">
</p>

## Retrobrighting

The covers are not severely yellowed, but there are areas where some yellowing is present. Therefore, both the top and bottom covers are retrobrighted using 12% hydrogen peroxide cream and exposed to UV light for about 12 hours.

**Note:** Before retrobrighting, the rubber feet are removed. If they are left in place during the process, they can become soft and "mushy".

<p align="center">
    <img src="Images/Case04.jpeg" alt="Description" width="800">
</p>

The result of the retrobrighting is quite good. It is not perfect, but I think the covers look much better than they did before.

<p align="center" float="left">
    <img src="Images/Case03.jpeg" alt="Description" width="500">
    <img src="Images/Case05.jpeg" alt="Description" width="500">
</p>

## Retrofitting the parallel cable

To allow the flat parallel cable to exit the casing, the area above the AC power inlet on the top cover is carefully filed down.

<p align="center" float="left">
    <img src="Images/Case08.jpeg" alt="Description" width="500">
    <img src="Images/Case07.jpeg" alt="Description" width="500">
</p>

As a strain-relief mechanism, the flat ribbon cable is routed beneath the mainboard PCB and above the AC power inlet. In addition, some hot glue is applied to provide extra strain relief.

<p align="center">
    <img src="Images/Case09.jpeg" alt="Description" width="800">
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
| Rotation speed | Rotation speed should be 300 RPM[^6] | FAILED(*) | 297.8 RPM|
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| PASSED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | PASSED | Track 0: "EXCELLENT" |

</div>

(*) The rotational speed should be 300 RPM, but it was measured at 297.8 RPM. The test is therefore marked as "FAILED". Nevertheless, the 1541 drive appears to be working just fine. I cannot find anything that would indicate that the slightly low rotational speed is causing any issues. Therefore, I will leave the rotational speed as it is. If it turns out later that this becomes a problem, the speed can be adjusted.

The table below shows the results of testing performed using selected speeder ROMs on both the computer and drive sides. The software used for this testing is the 64'er Floppy Speed Tester.

<div align="center">
    
| Action | Time | Factor | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Picture show(*) | 00:34 | N/A |  |
| Format | 00:19.3 | 3.86 |  |
| Program LOAD | 00:09.6 | 14.27 |  |
| Program SAVE | 00:04.8 | 26.46 |  |
| SEQ WRITE | 00:13.9 | 6.19 |  |
| SEQ READ | 00:08.3 | 9.16 |  |
| REL CREATE | 00:43.5 | 2.71 |  |
| Validate | 00:09.6 | 6.88 |  |
| Scratch files | 00:12.5 | 5.52 |  |
| Data transfer | 00:06.9 | 10.43 |  |
| 64´er-factor |   | 11.4 |  |

</div>

(*) A video showing the picture show can be found [here](https://youtu.be/jHJzYiJmzKw).

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Final result

<div align="center">

*"A picture is worth a thousand words"*

Below is a collection of pictures of the final result of the refurbishment of this 1541. Hope you like it! Click to enlarge!

<p align="center">
    <img src="Images/Final_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_02.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_03.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_04.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_05.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_06.jpeg" alt="Description" width="800">
</p>

<!-- MARK -->
<!-- MARK END-->

**Footnotes**
[^1]: Phillips pan head (6.8 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.6 mm
[^2]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 5.5 mm (and tooth washer)
[^3]: Phillips pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.6 mm
[^4]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 7.5 mm
[^5]: 1541/1571 Drive alignment from Free Spirit software (Probably fake)
[^6]: 1541 Test & Diagnostics cartridge from World of Jani
[^7]: Original Commodore test/demo-diskette for model 1541



