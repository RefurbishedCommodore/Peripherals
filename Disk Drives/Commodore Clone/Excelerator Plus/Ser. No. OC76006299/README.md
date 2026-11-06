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
          <a href="#checking-the-voltages">Checking the voltages</a>
        </li>
        <li>
          <a href="#repairing-the-power-switch-connections">Repairing the power switch connections</a>
        </li>
        <li>
          <a href="#replacing-the-electrolytic-capacitors">Replacing the electrolytic capacitors</a>
        </li>
        <li>
          <a href="#troubleshooting">Troubleshooting</a>
        </li>
        <li>
          <a href="#replacing-potentially-faulty-parts">Replacing potentially faulty parts</a>
        </li>
        <li>
          <a href="#using-a-different-power-supply-psu">Using a different Power Supply PSU</a>
        </li>
        </ul>
    </li>
    <li>
      <a href="#drive-mechanism">Drive mechanism</a>
        <ul>
        <li>
          <a href="#cleaning-the-rw-head">Cleaning the R/W head</a>
        </li>
        <li>
          <a href="#cleaning-and-lubricating-the-rw-head-rail-guide">Cleaning and lubricating the R/W head rail guide</a>
        </li>
        <li>
          <a href="#rw-head-measurement">RW Head measurement</a>
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
          <a href="#adding-new-rubber-feet">Adding new rubber feet</a>
        </li>          
        </ul>
    </li>      
    <li>
      <a href="#psu-adapter-cable">PSU adapter cable</a>
    </li>
    <li>
      <a href="#testing">Testing</a>
    </li>           
  </ul>
</details>

<!-- MARK START -->

# Refurbishment activities

The planned refurbishment activities for this Excelerator Plus floppy drive (Order may vary. Several of them in parallel):

- [x] Refurbish the mainboard
- [x] Create power supply adapter cable
- [x] Refurbish the internal mechanics
- [x] Refurbish the casing
- [x] Testing and validation


The plan can be updated during the refurbishment process. Sometimes I discover areas that need special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Starting point

This Commodore clone drive is new to me. I have heard that these drives are renowned for being both robust and less noisy (compared to the original Commodore 1541 floppy drives). From the outside this drive looks well used. There is quite a lot of scratches on the metal casing, and there is a substantial amount of dust and grime on the front bezel. But it seems to be in otherwise good condition. The lever mechanism appears from the outside to be working.

At the bottom one of the rubber feet is missing - hope that it didn't disappear during transportation. 

I do not currently know whether this drive is working, and I do not have the proper power supply, so I need to find a way to power it.

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

Disassembling the Excelerator drive is straightforward. At the bottom of the drive there are four JIS machine screws[^1] (with washers) holding the bottom cover to the rest of the chassis. **NOTE:** Although these are Japanese Industrial Standard (JIS) screws, you can use a standard Phillips screwdriver.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="300">
</p>

With the screws out of the way, the bottom lid can be slid off. Carefully slide it sideways, and then lift it straight up. The interior is now exposed for the first time, probably since the drive was manufactured.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

Before the main drive unit can be pulled out sideways to the right, the power-switch connector on the left-hand side must be disconnected from the PCB. **WARNING:** The connector is NOT keyed, so pay close attention to its orientation before disconnecting it.

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

Initial testing of the Excelerator floppy drive is performed about halfway through the disassembly, after some initial cleaning of the PCB and the R/W head. This helps assess the condition of the drive and provides useful information for the refurbishment process.

The result of the initial testing is **INCONCLUSIVE** for the following reason:

- When the floppy drive is powered on, the motor does not always spin up. It seems like this happens when the floppy drive is "cold" (not started for a while). The combined power/activity LED does seem to work fine every time.

The table below shows the results of the initial testing when the motor spins up. When the motor is not starting, none of the tests pass.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | PASSED | 300.6 |
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| FAILED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | FAILED | Track 0: "UNSATISFACTORY" |

</div>

The initial testing also shows that some tests, such as PERFORMANCE and HEAD STOP, fail. There seems to be an issue with formatting disks, so this needs to be investigated further.

<p align="center">
   <img src="Images/InitTest_01.png" alt="Description" width="400">
   <img src="Images/InitTest_02.png" alt="Description" width="400">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The drive electronics in the Excelerator Plus consist of four interconnected PCBs. I have numbered the PCBs from 1 to 4, and the following descriptions are my own definitions and assumptions.

<div align="center">
    
| PCB | Name | Description |
|:----------:|:----------:|:----------:|
| PCB #01 | R/W Receive and transmit | Responsible for amplifying signal from read/write head, and transmit digital signals to the read/write head. <BR> Control for rotational speed.  |
| PCB #02 | Servo | Responsible for controlling the servo motor |
| PCB #03 | Clock generator | Responsible for generating the CPU clock |
| PCB #04 | Main logic board | CPU, ROM and glue logic |

</div>

Below is a gallery of the PCBs mentioned above.

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

The mainboards appear to be in generally good condition. I cannot see any signs of rework from previous repairs. There is a significant layer of dust and grease on the PCB. Nevertheless, there are some areas which may require further attention:

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

<p align="center" float="left">
    <img src="Images/Main_11.jpeg" alt="Description" width="500">
    <img src="Images/Main_12.jpeg" alt="Description" width="500">
</p>

The table below lists all major custom ICs found on the mainboard. It is difficult to determine exactly when this floppy drive was manufactured, but based on the VIA date codes, I think it is reasonable to assume that it was manufactured in the autumn of 1986.

<div align="center">
    
| Chip | Version | Date code | Position | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | ROCKWELL R6502-20 | W42 Y1984 | UC7 | No |  |
| VIA #1 | UMC UM6522 | W35 Y1986 | UC8 | No |  | 
| VIA #2 | UMC UM6522 | W35 Y1986 | UC9 | No |  |
| DOS ROM | EPROM | Unknown | U3 | Yes | |
| SRAM | SONY CXK5816PN-12L | Unknown | U5 | No | |

</div>

<div align="center">

| Glue logic | Comment |
|:----------:|:----------:|
| Fairchild, Hitachi, Motorola ,Texas Instruments | No MOS glue logic |

</div>

## Checking the voltages

Voltages are measured before and after refurbishment to ensure that they are within acceptable limits. The table will be updated once the refurbishment is complete. 

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 4.768 V | TBD  V | Connector J1 PIN#1 |
| PSU (12V) | 12 V DC | 11.98 V / 0 V (*) | TBD V | Connector J1 PIN#4 |

</div>

(*) This measured voltage is equal to 0 V when disk motor is not starting.

**NOTE:** There is clearly something wrong with the 12 V supply.

## Repairing the power switch connections

After some troubleshooting, it turns out that some of the wires soldered to the power switch are a bit "wonky". This is probably causing the missing +12 V DC supply, although the power switch itself could also be responsible.

The old wires are cut and desoldered from the power switch, and the switch is cleaned properly (exterior). Below is a picture of the cleaned switch.

<p align="center">
    <img src="Images/Main_09.jpeg" alt="Description" width="600">
</p>

After the exterior cleaning, the interior resistance is measured. And the measured resistance is about **0.25 Ω** on both power-supply lines, which is close to the resistance of the meter leads. This indicates that the switch contacts are fine and are not causing the missing +12 V DC supply.

The next step is to replace the old wires, or, more precisely: the part of the wires soldered to the switch. Four new wire stubs are soldered to the connector, and also soldered to the old wires.

<p align="center">
    <img src="Images/Main_10.jpeg" alt="Description" width="600">
</p>

The refurbished power switch, with its new wires, is installed back in the drive. The 12 V DC and 5 V DC supplies are now present as they should be, and the floppy drive starts every time it is powered on. The first problem—the drive not starting every time—therefore seems to be fixed. The measured voltages at J1 are 11.99 V and 4.821 V respectively.

During the repair of the power switch connections the solder joints on the J7 connector are reflowed with fresh leaded solder.

<p align="center">
    <img src="Images/Main_13.jpeg" alt="Description" width="600">
</p>

## Replacing the electrolytic capacitors

As noted during the visual inspection, two capacitors, C5 and C13 on PCB #01, do not look too good. These two capacitors are both 10 μF [16 V], and are replaced with new capacitors with the same capacitance and voltage rating.

Below are some pictures taken during the replacement process.

<p align="center" float="left">
    <img src="Images/Main_17.jpeg" alt="Description" width="500">
    <img src="Images/Main_18.jpeg" alt="Description" width="500">
</p>

<p align="center" float="left">
    <img src="Images/Main_14.jpeg" alt="Description" width="500">
    <img src="Images/Main_15.jpeg" alt="Description" width="500">
</p>

Below is a picture of PCB #01 with the two new capacitors installed.

<p align="center">
    <img src="Images/Main_16.jpeg" alt="Description" width="800">
</p>

I also replace the two electrolytic capacitors, C12 and C14, on PCB #04. These capacitors are 100 μF [16 V], and are replaced with capacitors of the same capacitance, but slightly higher voltage rating (25 V). **NOTE:** To replace the C12 capacitor the whole J7 DIN power connector must be desoldered as well. 

Below are some pictures taken during the replacement process.

<p align="center" float="left">
    <img src="Images/Main_19.jpeg" alt="Description" width="500">
    <img src="Images/Main_20.jpeg" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/Main_22.jpeg" alt="Description" width="600">
</p>

Below is a picture of PCB #04 with the two new capacitors installed.

<p align="center">
    <img src="Images/Main_21.jpeg" alt="Description" width="800">
</p>

**NOTE:** Replacing the capacitors does not improve or fix the formatting problem. The *Performance* test still fails. 

## Troubleshooting

Since the formatting part of the PERFORMANCE test still fails, further troubleshooting is required. Below is a short list of what works and what does not work at this point:

- The voltages are present and within tolerances
- The drive can read directories and load software
- The drive can report the rotational speed
- The drive can fast format a floppy disk
- When copying a disk, the drive manages to read the first part. However, it fails when it tries to write that part to a pre-formatted disk.
- When entering a short, three-line BASIC program, it can be SAVED to disk.
    
There seems to be an issue with the write path. Even if the drive seems to be able to write something (e.g. the fast format and a small BASIC program), I still believe there is a marginal fault somewhere in the write path.

Something I notice during troubleshooting the formatting problem is the following:

The drive can apparently read without any problems. I have tried a few games on floppies, and everything appears to be working as it should. The ALIGNMENT test shows all tracks as "100%" when tested with the original Commodore test floppy. See picture below.

<p align="center">
    <img src="Images/Main_23.jpeg" alt="Description" width="500">
</p>

However, when I run the PERFORMANCE test using a pre-formatted floppy from another drive, something interesting happens. The test fails as before with a *21 - READ ERROR*. However, if I then run the ALIGNMENT test, the first track appears to be corrupted and shows 0%. See picture below.

<p align="center">
    <img src="Images/Main_24.jpeg" alt="Description" width="500">
</p>

*Now, something interesting happens: if I switch the PCB #01 with an identical PCB from a known working Excelerator Plus drive the faulty drive works! If I use this other PCB the faulty drive passes all tests! So, as I understand this, the fault must be with the PCB #01. It would mean that this proves that the R/W head is functioning, and that the fault lies somewhere else (as in PCB #01).*

The schematic below is from an Oceanic OC-118N drive, but it is very similar to the circuitry used in the Excelerator Plus. The WRITE section is on the right-hand side of the schematic, while the READ section is on the left-hand side, towards the middle.

<p align="center">
    <img src="Images/Main_25.png" alt="Description" width="1000">
</p>

To aid the troubleshooting, I take a series of measurements. For each test point, I capture screenshots of the signals from both the faulty and the working drives.

Both PIN #1 and PIN #6 on the R/W head are measured during the format operation in the PERFORMANCE test. The signal varies from 0 V to 12 V with peaks measured at +15 / + 10 V. The signals appear to be OK on the faulty drive.

**TEST POINT #A [FAULTY DRIVE]:**

<p align="center" float="left">
    <img src="Images/Main_26.png" alt="Description" width="135">
    <img src="Images/Main_27.png" alt="Description" width="135">
    <img src="Images/Main_31.png" alt="Description" width="135">
    <img src="Images/Main_29.png" alt="Description" width="135">
    <img src="Images/Main_28.png" alt="Description" width="135">
    <img src="Images/Main_30.png" alt="Description" width="135">
</p>

**TEST POINT #A [WORKING DRIVE]:**

<p align="center" float="left">
    <img src="Images/Main_45.png" alt="Description" width="135">
    <img src="Images/Main_40.png" alt="Description" width="135">
    <img src="Images/Main_42.png" alt="Description" width="135">
    <img src="Images/Main_43.png" alt="Description" width="135">
    <img src="Images/Main_41.png" alt="Description" width="135">
    <img src="Images/Main_44.png" alt="Description" width="135">
</p>

During the initialisation of the format process, a sequence of SYNC, $55, SYNC is sent. The screenshots above suggest that this sequence is correct. Below is a list of the expected values of these (in terms of timing), and that seems to match quite well with the oscilloscope readings. 

<div align="center">
    
| Quantity | Approximate value | 
|:----------:|:----------:|
| Bit-cell duration | 3.25 µs |
| $FF SYNC transition interval | 3.25 µs |
| $55 transition interval | 6.50 µs |

</div>


PIN#3 on the R/W head is measured during the format operation in the PERFORMANCE test. Here I notice something that *could* be important. It seems like the signal on the faulty drive is struggling to stay at +12V for a long enough period. It is difficult to measure this precisely, but I do think there is a difference here.

**TEST POINT #B [FAULTY DRIVE]:** 

<p align="center" float="left">
    <img src="Images/Main_34.png" alt="Description" width="200">
    <img src="Images/Main_32.png" alt="Description" width="200">
    <img src="Images/Main_33.png" alt="Description" width="200">
    <img src="Images/Main_39.png" alt="Description" width="200">    
</p>

**TEST POINT #B [WORKING DRIVE]:**
<p align="center" float="left">
    <img src="Images/Main_36.png" alt="Description" width="200">
    <img src="Images/Main_38.png" alt="Description" width="200">
    <img src="Images/Main_35.png" alt="Description" width="200">
    <img src="Images/Main_37.png" alt="Description" width="200">    
</p>

I am now falling deep into the rabbit hole of magnetic flux! After hours of investigation, I notice something that does seem to be a real difference. When the ERASE coil voltage is raised from 0 V to 12 V, and then back to 0 V again, there are some rapid voltage transients. This is caused by the ERASE coil opposing the change in current. Now, what I notice is the following:

- On the faulty drive, the transients are very noticeable, especially when going from 12 V to 0 V
- On the working drive, the transients are noticeable, but the peak values are way smaller when going from 12 V to 0 V
- On yet another working drive (which actually seems to format disks faster) the transients are barely noticeable when going from 12 V to 0 V

**TEST POINT #B [FAULTY/WORKING/WORKING DRIVE]:**
<p align="center" float="left">
    <img src="Images/Main_46.png" alt="Description" width="300">
    <img src="Images/Main_47.png" alt="Description" width="300">
    <img src="Images/Main_48.png" alt="Description" width="300">
</p>

Close-up screenshots of the transient on the faulty and working drives are shown below. As can be seen, the voltage transient peaks are higher on the faulty drive than on the working drive. The oscillation also lasts slightly longer on the faulty drive.

<p align="center" float="left">
    <img src="Images/Main_50.jpeg" alt="Description" width="400">
    <img src="Images/Main_49.jpeg" alt="Description" width="400">
</p>

**TEST POINT #C [FAULTY/WORKING DRIVE]:**

Another test point is resistor R4, through which the erase-coil current flows to ground. But, as can be seen from the screenshots below there is hardly any difference between the two. The screenshot on the left side is the faulty drive, and the screenshot on the right side is the working drive. On the faulty drive the resistor R4 is measured to 138.2 Ω and on the working drive R4 is measured to 138.4 Ω.

<p align="center" float="left">
    <img src="Images/Main_51.png" alt="Description" width="300">
    <img src="Images/Main_52.png" alt="Description" width="300">
</p>

## Replacing potentially faulty parts

There is no clear indication of what is causing the formatting failure. The only thing that currently stands out is the variation in the voltage/current transients when the Q4 transistor shuts off the 12 VDC to the ERASE coil. The voltage across the ERASE coil is determined by the formula V=L*(dI/dt). This means that the rate at which Q4 interrupts the 12 V DC supply affects the resulting transient.

So, the first part to be swapped with the working PCB is transistor Q4. The transistor is desoldered without any damage to traces or pads.

<p align="center" float="left">
    <img src="Images/Main_53.jpeg" alt="Description" width="500">
</p>

**RESULT:** The drive still cannot format a disk. The voltage transient now looks identical to that of the working drive. This indicates that the voltage transients were not the cause of the problem.

Next the MC3346P transistor package (IC1) is swapped with the working PCB. The chip is desoldered without any damage to traces or pads.

<p align="center" float="left">
    <img src="Images/Main_54.jpeg" alt="Description" width="500">
</p>

**RESULT:** The drive still cannot format a disk. No changes are observed in any of the signals.

Moving over to the read-part of the drive, the MC3470AP chip (IC2) is swapped with the working PCB. The chip is desoldered without any damage to traces or pads.

<p align="center" float="left">
    <img src="Images/Main_55.jpeg" alt="Description" width="500">
</p>

**RESULT:** Some progress! The drive still cannot complete a format, but it now manages to format two or three tracks before failing.

## Using a different Power Supply PSU

During the troubleshooting process, something occurs to me: if the 12 V DC and 5 V DC supplies are not clean enough, they could introduce interference. Writing to magnetic media is susceptible to noise, which can cause errors.

And then something happens: with a new, modern power supply from Ray Carlsen and my new PSU adapter, **the drive works fine!** All this troubleshooting and work - only to see that changing the power supply fixed the issue.

**IMPORTANT NOTE:** Even though the drive now works as it should, I find that it is a bit "picky" about the magnetic media. Old, worn and heavily used floppies sometimes fail to format. Other floppies format without any issues at all. I think this is "as-good-as-it-gets" considering the old age of the drive.

**WHY DOES IT HELP SWITCHING TO A MODERN PSU:** It is good practice to use a modern replacement PSU when powering old retro equipment. Usually, this is due to the danger of overvoltage or insufficient power (too low current output). However, I do not think this is the issue here. But another issue that old power supplies cause is electromagnetic noise. If the filtering capacitors in the PSU are deteriorating, both low- and high-frequency noise can pass into the device. If this is the case, the device may fail during operation.

But, also on the device side there are capacitors that filter out noise. And this noise is both from the power supply - and from the components on the PCBs in the device. Examples include C5 and C13, which filter noise on the 5 V and 12 V rails, respectively (note that there is a typo on the C13 - it is 10µF).

<p align="center">
    <img src="Images/Main_56.png" alt="Description" width="500">
    <img src="Images/Main_57.png" alt="Description" width="250">
</p>

You could argue that replacing all passive components (coils, resistors and capacitors) might eliminate the noise from the PSU. Sure, but I would argue that the cost (and time) to change all these passive components would be very high - and with no guarantees. I think it is much better to use good-quality floppies and a modern PSU with this drive.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# PSU adapter cable

The Excelerator Plus floppy drive uses a +5 V DC / +12 V DC power supply (PSU) with a 5-pin DIN connector. However, on a traditional 1541-II PSU, the +5 V and +12 V pins are available on a 4-pin DIN connector. Since this particular floppy drive no longer had its original PSU, I made an adapter cable. The cable connects to a standard 1541-II PSU (preferably a modern replacement), allowing it to be used with the Excelerator Plus drive.

Below is the schematic for the 1541-II PSU with the 4-pin DIN connector pinout. **NOTE:** the pinout is for the male connector - seen from the outside of the plug connector.

<p align="center">
    <img src="https://github.com/RefurbishedCommodore/Peripherals/blob/main/Disk%20Drives/Commodore%201541/General%20images/1541-II-powersupply.gif" alt="Description" width="800">
</p>

The 5-pin DIN connector used on the Excelerator side has the pinout shown below - seen from the outside of the plug connector.

<p align="center">
    <img src="Images/5_DIN.png" alt="Description" width="400">
</p>

Below is a picture of the final PSU adapter cable.

<p align="center">
    <img src="Images/Main_05.jpeg" alt="Description" width="700">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Drive mechanism

The drive mechanism seems to be in good overall condition. There is not much dust or grease, and I cannot see any signs of mechanical damage.

## Cleaning the RW head

The R/W head does not seem to have been very exposed to residue from floppies. Nevertheless, the R/W head is cleaned properly with some isopropanol.

<p align="center">
    <img src="Images/Mech_01.jpeg" alt="Description" width="800">
</p>

## Cleaning and lubricating the RW head rail guide

To allow the R/W head to move freely across the floppy tracks, the rail guides need to be cleaned and lubricated. The cleaning is done with isopropanol and a cotton swab, and I use a small amount of lithium grease for lubrication.

<p align="center">
    <img src="Images/Mech_02.jpeg" alt="Description" width="800">
</p>

## RW Head measurement

It is good practice to measure the resistance of the Read/Write (R/W) coil and the erase coil. Since the drive fails when formatting a disk, the problem could perhaps be related to a faulty R/W head - still I think this sounds a bit unlikely since the drive seems to work fine otherwise. Since there is very little documentation about the Excelerator Plus drive I don't know the actual target values to look for, and also not which wire is which.

So, to try to find some target values, I am able to borrow a working Oceanic drive. This Oceanic drive is very similar to the Excelerator Plus drive and I therefore think that this Oceanic drive can function as a target reference.

<div align="center">
    
| Check | Description | Target | Measure | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| R/W coil | Thin Black <> White | 15 Ω | 14.9  Ω|  |
| R/W coil | Thin Black <> Blue | 7.5 Ω | 7.9 Ω |  |
| R/W coil | Thin Black <> Red | 8.6 Ω | 9.9 Ω |  |
| R/W coil | Thick Black <> White | 145 Ω | 145 Ω|  |
| R/W coil | ThickBlack <> Blue | 137 Ω | 138 Ω |  |
| R/W coil | ThickBlack <> Red | 139 Ω |  140 Ω |  |

</div>

All the measured values on the Excelerator Plus drive are quite close to the reference values, suggesting that the R/W head is most likely working as it should.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

Both the top and bottom covers are in OK condition mechanically. They are a bit scratched, and covered with a thin layer of grease.

## Cleaning the covers

The front bezel is quite dirty. There is a lot of residue from floppies being inserted into the drive over many years. Nevertheless, the front bezel is quite nice looking after cleaning it with some isopropanol.

<p align="center">
    <img src="Images/Case_02.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Case_01.jpeg" alt="Description" width="800">
</p>

The metal top- and bottom covers are carefully cleaned with some glass cleaning liquid on a cloth. There is a significant amount of scratches on the top cover, but this something that can't be easily fixed.

## Adding new rubber feet

The bottom cover has only three of its four rubber feet. Also, some of the feet are quite dried out. Four new circular rubber feet (17 mm in diameter and 7 mm thick) are installed on the bottom casing.

<p align="center">
    <img src="Images/Case_03.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Testing

The proof is in the pudding — does it work?

The purpose of this stage is to test and verify that the Excelerator floppy disk drive works as it should. The basic functionality tested earlier is tested again and verified. A combination of software tools is used in this process; please see the description of the [tools](https://refurbished-commodore.com/tools).

The table below shows the results of the testing performed using the standard CBM DOS and CBM Kernal.

<div align="center">
    
| Test | Description | Passed/Failed | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Normal power on | Normal power on<br>Disk drives powers on<br>Drive light goes off after short time<br>Motor stops spinning | PASSED |  |
| Loading: DIRECTORY | Loading a directory from BASIC[^5] | PASSED | |
| Loading: FILE | Loading a file from BASIC[^5] | PASSED | |
| Rotation speed | Rotation speed should be 300 RPM[^6] | PASSED | 300.6 RPM|
| Performance | Checking basic functionality such as[^6]:<br>FORMAT, LOAD, WRITE| PASSED | |
| Alignment | Checking R/W track alignment[^7] | PASSED | Track 1-35: "SATISFACTORY" |
| Head stop | Checking the position of track 0[^7] | FAILED | Track 0: "UNSATISFACTORY" |

</div>

**NOTE:** The "HEAD STOP" test fails. However, this is probably perfectly OK and is simply a consequence of this being a 1541 clone that uses a different track 0 sensor and mechanism. 

Below are some screenshots from the testing process.

<p align="center" float="left">
    <img src="Images/Test_01.png" alt="Description" width="180">
    <img src="Images/Test_02.png" alt="Description" width="180">
    <img src="Images/Test_03.png" alt="Description" width="180">
    <img src="Images/Test_04.png" alt="Description" width="180">
</p>

<p align="center" float="left">
    <img src="Images/Test_06.png" alt="Description" width="180">
    <img src="Images/Test_05.png" alt="Description" width="180">
    <img src="Images/Test_07.png" alt="Description" width="180">
    <img src="Images/Test_08.png" alt="Description" width="180">
</p>

<p align="center" float="left">
    <img src="Images/Test_09.png" alt="Description" width="180">
    <img src="Images/Test_11.png" alt="Description" width="180">
    <img src="Images/Test_12.png" alt="Description" width="180">
    <img src="Images/Test_13.png" alt="Description" width="180">
</p>

<p align="center" float="left">
    <img src="Images/Test_14.png" alt="Description" width="180">
    <img src="Images/Test_15.png" alt="Description" width="180">
    <img src="Images/Test_16.png" alt="Description" width="180">
    <img src="Images/Test_17.png" alt="Description" width="180">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Final result

<div align="center">

*"A picture is worth a thousand words."*

Below is a collection of pictures showing the final result of the refurbishment of this Excelerator Plus floppy drive. I hope you like it! Click to enlarge!

</div>

<p align="center">
    <img src="Images/Final_05.jpeg" alt="Description" width="800">
</p>


<p align="center">
    <img src="Images/Final_03.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_04.jpeg" alt="Description" width="800">
</p>


<p align="center">
    <img src="Images/Final_06.jpeg" alt="Description" width="800">
</p>


<p align="center">
    <img src="Images/Final_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Final_02.jpeg" alt="Description" width="800">
</p>


[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK STOP -->


**Footnotes**
[^1]: JIS pan-head machine screw (5.4 mm head diameter), fully threaded, 3.0 mm thread diameter, 6.0 mm fastener length (plus flat washer and spring lock washer).

