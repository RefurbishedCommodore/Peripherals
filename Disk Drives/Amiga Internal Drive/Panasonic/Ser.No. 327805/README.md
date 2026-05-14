<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Amiga Internal Drive

![Name](https://img.shields.io/badge/Serial_No.-327805-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Brand-Panasonic/Matsushita-white?style=plastic)
![Name](https://img.shields.io/badge/Model-JU_253_033P-white?style=plastic)

# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#refurbish-activities">Refurbish activities</a>
    </li>
    <li>
      <a href="#mechanics">Mechanics</a>
    </li>
    <ul>
        <li>
          <a href="#cleaning-and-lubricating-the-worm-gear">Cleaning and lubricating the worm gear</a>
        </li>
    </ul>
    <li>
      <a href="#mainboard">Mainboard</a>
    </li>
    <ul>
        <li>
          <a href="#visual-inspection-of-first-mainboard">Visual inspection of first mainboard</a>
        </li>
        <li>
          <a href="#replacing-the-smd-electrolytic-capacitor">Replacing the SMD electrolytic capacitor</a>
        </li>
        <li>
          <a href="#setting-the-position-of-the-three-switches">Setting the position of the three switches</a>
        </li>
     </ul>
    <li> 
    <a href="#testing">Testing</a>
    </li>
  </ul>
</details>

# Starting point

This internal floppy drive from Panasonic (Model JU-253-033P) was installed in the [Amiga 500 with "special" serial number 1.](https://github.com/RefurbishedCommodore/Amiga500/tree/main/Assy%20312510/Artwork%20312513%20REV%206A/Ser.No.%201#readme) It does not look too bad, but I can see quite a bit of dust inside it, and the SMD capacitor at the front has leaked its dielectric material, leaving the PCB area in a bit of a mess.

Mechanically, the drive appears to be in decent condition. I cannot see any immediate signs of damage, either externally or internally (from what I can observe of the interior).

At this stage, I do not know whether the drive works or not, but with that "melted" capacitor, I have my doubts...

Below are some pictures of the internal disk drive before refurbishment.

<p align="center">
    <img src="Images/Start06.jpeg" alt="Description" width="600">
    <img src="Images/Start05.jpeg" alt="Description" width="600">
    <img src="Images/Start03.jpeg" alt="Description" width="600">
    <img src="Images/Start04.jpeg" alt="Description" width="600">
    <img src="Images/Start02.jpeg" alt="Description" width="600">
    <img src="Images/Start01.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Refurbish activities

The planned refurbishment activities for this Amiga 500 (order may vary; several activities may be performed in parallel):

- [x] Clean the interior
- [x] Clean special parts such as R/W head and stepper motor shaft
- [x] Refurbish mainboard
- [x] Testing and validation

The plan may be updated during the refurbishment process. Sometimes I discover areas that need special attention.
<br>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Disassembly

Disassembly starts by removing the two small Phillips screws[^1] at the far end of the top lid. See the picture below.

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="400">
</p>

Before the lid can be lifted, it needs to be freed from the two small metal tabs located on each side of the drive. See the picture below.

<p align="center">
    <img src="Images/Dis02.jpeg" alt="Description" width="400">
</p>

The lid is lifted off the drive, exposing the interior. There is less dust than I anticipated, but I can see that both the PCB and the worm gear require significant cleaning.

<p align="center">
    <img src="Images/Dis03.jpeg" alt="Description" width="800">
</p>

The next step is to remove the eject button, which is straightforward, but care must be taken not to break the brittle plastic. Using a thin flat screwdriver, the plastic eject button is carefully released from the small tab holding it in place.

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="800">
</p>

To remove the inner floppy tray, the eject button metal tab (now without the plastic button attached) needs to be pressed inward.

<p align="center">
    <img src="Images/Dis05.jpeg" alt="Description" width="800">
</p>

With some care, the front of the floppy tray can be lifted from the base. Be VERY careful not to lose any of the small metal wheels (and spacers). These are tiny!

<p align="center">
    <img src="Images/Dis06.jpeg" alt="Description" width="800">
</p>

Something to note: there are four metal wheels, but only two spacers. They are arranged as shown in the picture below.

<p align="center" float="left">
    <img src="Images/Dis07.jpeg" alt="Description" width="400">
    <img src="Images/Dis08.jpeg" alt="Description" width="449">
</p>

With the tray out of the way, we are getting closer to the final disassembly. However, there is still one last metal shield that needs to be removed. There are two things to note when removing this shield. First, there is a plastic "lever" that needs to be carefully removed (see top left arrow). Second, there are two small springs that also need to be removed.

<p align="center">
    <img src="Images/Dis09.jpeg" alt="Description" width="800">
</p>

First, the plastic "lever" is removed. This is done by first removing the split plastic ring, then the specially formed spring, and finally the plastic "lever" itself. See the pictures below.

<p align="center" float="left">
    <img src="Images/Dis10.jpeg" alt="Description" width="466">
    <img src="Images/Dis11.jpeg" alt="Description" width="400">
</p>

<p align="center" float="left">
    <img src="Images/Dis12.jpeg" alt="Description" width="400">
    <img src="Images/Dis13.jpeg" alt="Description" width="557">
</p>

<p align="center">
    <img src="Images/Dis14.jpeg" alt="Description" width="800">
</p>

Next, the two small springs are removed. The tension in them should now be zero, since the metal plate is pushed towards the front of the drive.

<p align="center" float="left">
    <img src="Images/Dis15.jpeg" alt="Description" width="500">
    <img src="Images/Dis16.jpeg" alt="Description" width="411">
</p>

The metal plate can now be removed from the base. Below is a picture of the metal plate.

<p align="center">
    <img src="Images/Dis17.jpeg" alt="Description" width="500">
</p>

With the metal plate removed, the rest of the interior is exposed. This is the final part of the disassembly.

<p align="center">
    <img src="Images/Dis18.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Mechanics

After 30+ years, the internal mechanics need some care. This primarily consists of cleaning and lubrication, but a visual inspection can sometimes reveal that additional work is required.

## Cleaning and lubricating the worm gear

The worm gear is quite full of old grease. There is some odd grease residue in the middle of the worm gear that almost looks like a plastic ring. However, ignoring the old grease, the worm gear appears to be in acceptable mechanical condition. Below is a picture of the worm gear before cleaning (click to enlarge).

<p align="center" float="left">
    <img src="Images/Mech01.jpeg" alt="Description" width="500">
    <img src="Images/Mech02.jpeg" alt="Description" width="500">    
</p>

The worm gear is cleaned using isopropanol.

<p align="center">
    <img src="Images/Mech03.jpeg" alt="Description" width="700">   
</p>

After cleaning, the worm gear is lubricated with lithium grease. This should allow the R/W head to travel along the worm gear frictionlessly.

<p align="center">
    <img src="Images/Mech04.jpeg" alt="Description" width="700">   
</p>

Something I recommend is letting the floppy drive itself smear the grease along the worm gear. This is something that can be done during initial testing (assuming that the drive is at least partially working). By using the Amiga Test Kit software, you can get the R/W head to travel all the way from track 0 to 79 quite quickly several times. This will distribute the lithium grease evenly along the worm gear. [A video demonstrating this can be found here:](https://youtu.be/zGUp7R_3y7c)

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Mainboard

There are actually two interconnected mainboards in the floppy drive:

- One mainboard surrounding the large flywheel (referred to as "Mainboard #1" here)
- One mainboard at the rear, beneath the R/W head and the stepper motor (referred to as "Mainboard #2" here)

## Visual inspection of first mainboard

There are two things revealed by the visual inspection of the mainboard:

- There is some blue paint/marker residue on the left-hand side of the mainboard. I am not entirely sure what this is, but I assume it may be related to assembly quality control.
- The 10 µF [35V] electrolytic SMD capacitor has leaked across the right-hand side of the mainboard.

Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main02.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="800">
</p>

## Replacing the SMD electrolytic capacitor

The leaked SMD electrolytic capacitor needs to be removed. First, the area is properly cleaned with isopropanol. Then, the old SMD capacitor is cut off using diagonal cutters. The area is cleaned with vinegar and isopropanol before the old solder is removed from the pads using flux and fresh solder (this smells terrible!). No pads or traces were damaged during the process.

<p align="center">
    <img src="Images/Main03.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main04.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main05.jpeg" alt="Description" width="800">
</p>

A new 10 µF [35V] electrolytic capacitor is installed. Note that the new capacitor is not the SMD version, but a standard through-hole (THT) capacitor. This does not affect functionality in any way.

<p align="center">
    <img src="Images/Main06.jpeg" alt="Description" width="1000">
</p>

Also, the left-hand side of the mainboard is properly cleaned with isopropanol. The blue paint (?) is removed without any issues. In addition, the two small push switches (which detect whether a floppy disk is inserted and/or write-protected) are treated with contact cleaner.

<p align="center">
    <img src="Images/Main09.jpeg" alt="Description" width="1000">
</p>

## Cleaning the read/write (R/W) heads

Yes, it is “heads” in the plural. There are two R/W heads: one reads the top side of the disk and one reads the bottom side (for “DS” floppies). The heads are cleaned thoroughly with isopropanol on a cotton swab (Q-tip).

<p align="center">
    <img src="Images/Main07.jpeg" alt="Description" width="1000">
</p>

## Setting the position of the three switches

Disclaimer: I was not aware of the three switches at the rear of the floppy drive before performing the initial testing. During the initial testing, I had problems getting the drive to work at all. The drive was:

- Not ticking (in the sense that the R/W head was moving slightly back and forth)
- Not able to sense or read any floppy disks

After some research on the web, I found a brilliant YouTube video from [The Floppy Doc:](https://www.youtube.com/watch?v=VQsnVUCTDEw&t=6290s)
. The video “Diagnosing the Amiga 600 Panasonic Drive” explains that, in order for the floppy drive to work in an Amiga, the three switches must be set as follows:

`Amiga mode: SW3: "0", SW2: "M0", SW1: "RY"`

It turns out that SW3 was set to "3", which caused the floppy drive to not work at all in the Amiga.

Below is a picture of the switches set to the correct position for "Amiga mode".

<p align="center">
    <img src="Images/Main08.jpeg" alt="Description" width="1000">
</p>

Also, in the same video, it shows which positions the switches must be set to in order for the drive to work in a PC:

`PC mode: SW3: "1", SW2: "MS", SW1: "DC"`

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Testing

To test the internal floppy drive, it is installed in the [Amiga it came from
.](https://github.com/RefurbishedCommodore/Amiga500/blob/main/Assy%20312510/Artwork%20312513%20REV%206A/Ser.No.%201/README.md) With the floppy drive installed, the Amiga is first powered on to verify that the machine is able to boot, but also to listen for the famous "ticking" sound.

The floppy drive is then tested using the floppy test functions found in Amiga Test Kit v1.20. Below are the results from the testing.

<div align="center">

| Test | Description | PASSED/FAILED | Comment |
|:----------:|:----------:|:----------:|:----------:|
| Power on "ticking" | The drive is making the normal ticking sound on power-on | PASSED | |
| Boot ATK | The drive is able to boot Amiga Test Disk | PASSED | |
| Read test | Reading all 80 tracks (both sides) | PASSED | Using an original WB 1.3 floppy |
| Write test | Writing data to track 158 and 159 | PASSED | |
| Head calibration test| Testing reading cylinder 0, 40 and 79 | PASSED | Using an original WB 1.3 floppy<br><br>CYLINDER 0: 11/11 [OK] <br>CYLDINDER 40: 11/11 [OK]<br>CYLINDER 79: 11/11 [OK]|

</div>

Below are some pictures from the floppy drive testing.

<p align="center" float="left">
    <img src="Images/Test04.jpeg" alt="Description" width="200">
    <img src="Images/Test05.jpeg" alt="Description" width="200">
    <img src="Images/Test06.jpeg" alt="Description" width="200">
</p>

<p align="center" float="left">
    <img src="Images/Test01.jpeg" alt="Description" width="200">
    <img src="Images/Test02.jpeg" alt="Description" width="200">
    <img src="Images/Test03.jpeg" alt="Description" width="200">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

**Footnotes**
[^1]: Phillips pan head (3.0 mm), Machine screw, Fully threaded, Thread diameter: 2.0 mm, Fastener length: 4.0 mm
