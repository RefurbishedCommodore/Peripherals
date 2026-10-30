<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Digilog DCR64S

![Name](https://img.shields.io/badge/Serial_No.-091437-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/PCB-1531-white?style=plastic)
![Name](https://img.shields.io/badge/Belt_size-Taiwan-white?style=plastic)

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
          <a href="#replacing-the-electrolytic-capacitors">Replacing the electrolytic capacitors</a>
        </li>
        <li>
          <a href="#cleaning-the-leaf-switch">Cleaning the leaf switch</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#drive-mechanism">Drive mechanism</a>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#replacing-the-rubber-belts">Replacing the rubber belts</a>
        </li>
      </ul>
    </li>    
    <li>
      <a href="#tape-head-azimuth-alignment">Tape head azimuth alignment</a>
    </li>
    <li>
      <a href="#tape-speed">Tape speed</a>
    </li>
    <li>
      <a href="#casing">Casing</a>
    </li>
    <li>
      <a href="#testing">Testing</a>
    </li>
    <li>
      <a href="#final-result">Final result</a>
    </li>
  </ul>
</details>

# Refurbishment activities

The planned refurbishment activites for this Digilog DCR64S (Order may vary. Several of them in parallel):

- [x] Refurbish the mainboard
- [x] Refurbish the internal drive mechanics
- [x] Refurbish the casing
- [x] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK START -->

# Starting point

This is one of many clones of the original Commodore 1530 (C2N) datasette. This particular clone, the Digilog DCR64S, is new to me, but I would expect it to be quite similar as the others. The datasette looks to be in fine condition. There are some spots, and one (and only one) cable burn mark - but I would not expect anything else.

I think that the colour is original, in the sense that it is not yellowed. The dark colour is so even around the whole casing that I can´t think that this is due to any yellowing. All the keys feels responsive, but the top lid is slightly hard to press down after eject. But I think this is normal. There are some oxidation on the pins on the datasette port connector.

All in all, this looks like a fine datasette from the outside. I do not know if it works or not, but that will be investigated during the refurbishment.

DCR64S? What could it mean? My guess is that "DCR" is short for Data Cassette Recorder, and "64", yes, of course refers to the Commodore 64.

Below are some pictures of the datasette before refurbishment.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="600">
    <img src="Images/Start_02.jpeg" alt="Description" width="600">
    <img src="Images/Start_03.jpeg" alt="Description" width="600">
    <img src="Images/Start_04.jpeg" alt="Description" width="600">
    <img src="Images/Start_05.jpeg" alt="Description" width="600">
    <img src="Images/Start_06.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

Disassembly of the Digilog DCR64S starts with removing the four screws[^1] at the bottom cover.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

With the screws out of the way, the bottom cover is carefully lifted off. The interior, with its PCB, belts and drive mechanism is exposed. One thing I immediate notice is that the PCB is marked **1531**. This is quite special, since the **1531** PCB is usually found in the original Commodore 1530 (C2N) datasette. So, this is either an original **1531** PCB or a 1:1 clone of it. A picture of the original Commodore **1531** PCB can be seen in the [HOWTO - Datasette head alignment](https://refurbished-commodore.com/datasette-head-alignment) article.

Below is a picture of the interior with the bottom cover removed (Digilog DCR64S).

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

The whole drive mechanism can simply be pulled off from the top cover. **NOTE:** I am not completely sure, but I had to press the EJECT button before I was able to release it. 

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

The top cover can be disassembled further: the top lid can be pushed out from the base. **WARNING:** This is old and brittle plastic! Be *very* carful when pushing the two arms (see arrows in picture above) inwards. A small drop of machine sewing oil on the arms can help reduce the friction when the lid is pushed out.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="500">
</p>

Next step is not complicated, but it is very easy to loose some small parts. On the backside of the drive mechanism there are three small springs attached to the six keys. These springs needs to be released from the keys, and the springs removed. A pair of small tweezers is highly recommended.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="500">
</p>

Before the metal shaft holding all the keys in placed can be pulled out the little E-clip on the right hand side needs to be removed. This can be a bit tricky, but with a small flat screwdriver it can be removed.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="400">
</p>

Below is a picture of all the small parts - THIS IS WHAT YOU ARE LOOKING FOR ON THE FLOOR!

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="800">
</p>

# Mainboard

As mentioned in the disassembly chapter, this PCB is marked **1531** which is the version label that the original Commodore 1530 (C2N) datasette use. And from the backside of this Digilog PCB looks identical to the original **1531** PCB. So, this is either a 1:1 clone of the original PCB - or it is actually an original Commodore PCB.

## Visual inspection

There is a substantial amount of old flux residue on the PCB. The flux itself is not conductive, or corrosive, but when the flux gets old it also gets sticky. This will then lead to moist and dust being accrued together with the flux which eventually can lead to corrosion. So, during the refurbishment process the PCB will be cleaned properly with isopropanol to remove all the flux.

Below is a picture of backside of the **1531** mainboard before refurbishment.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="400">
</p>

To remove the mainboard from the rest of the datasette mechanism the two screws[^2] (marked with thick arrows in the picture above) are removed. The black wire, from the leaf switch underneath, is desoldered from the PCB (marked with thin arrow in the picture above). Also, to make the removal easier, the transparent plastic band holding all the wires is untied. See picture below.

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="600">
</p>

Before the PCB mainboard can be completely lifted from the datasette mechanism, the PCB is tilted slightly so that the leaf switch is revealed where the blue and black wires are connected. The small screw holding the leaf switch is removed.

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="600">
</p>

With the leaf switch out of the way, the whole mainboard is lifted from the datasette mechanism.

<p align="center">
    <img src="Images/Main_04.jpeg" alt="Description" width="800">
</p>

## Replacing the electrolytic capacitors

The front side of the mainboard also looks to be in fine condition. I can see some flux residue here as well, but other than that it I can not see any damage or corrosion. There are three electrolytic capacitors (C7, C8 and C9) on the mainboard, all 47 μF [16 V]. I can not see any obvious leakage, or bulging, but I choose to replace them anyway.

<p align="center" float="left">
    <img src="Images/Main_05.jpeg" alt="Description" width="500">
    <img src="Images/Main_06.jpeg" alt="Description" width="500">
</p>

## Cleaning the leaf switch

The leaf switch is heavily oxidised. This oxidation is removed with a glassfiber pen and some fine grain sanding paper.

<p align="center" float="left">
    <img src="Images/Main_07.jpeg" alt="Description" width="500">
    <img src="Images/Main_08.jpeg" alt="Description" width="500">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Drive mechanism

The drive mechanism is marked with "WEICHIEN PW-33Z" and "87". See pictures below. My immediate guess is that "87" refers to the year it was manufactured - strengthened by the fact that this datasette was following the [Commodore 128](https://github.com/RefurbishedCommodore/Commodore128/blob/main/Artwork%20310381%20(Rev%209)/Ser.%20No.%20DA%204%20354432/README.md) which is also expected to be manufactured in 1987. 

An AI search for the "WEICHIEN PW-33Z" reveals the following:

>The Wei Chien PW-33Z is an internal cassette tape drive mechanism manufactured in Taiwan.
>During the 1980s, this specific component was widely sourced by electronics brands to build dedicated data recorders (datasettes) and cassette players for 8-bit home computers.
>
>A prominent example of its use is in the Noris Data Datenrekorder DR 1535, a popular third-party Commodore 64 cassette recorder distributed in Germany. Units produced around 1986 featured a sticker on the internal mechanism confirming it as the Wei Chien PW-33Z

<p align="center">
    <img src="Images/Int_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Int_02.jpeg" alt="Description" width="800">
</p>

## Visual inspection

The first thing I notice is that there is surprisingly little dust and grease covering the the drive mechanism. Usually, an old datasette is full of dust, but this is definitely not the case with this Digilog datasette. I can not see any mechanical damage on gears, flywheel, pinch roller or capstan.

On the other hand, the large drive belt seems to be lacking its elasticity. It is not terrible, but it would probably benefit from a new drive belt.

## Replacing the rubber belts

There are two rubber belts in the datasette:

- The drive belt which transfers the energy from the motor to the flywheel
- The counter belt which connects the PLAY/FF gears to the three digit counter

It is good practice to replace both of these, but it is not strictly required for the counter belt.

Replacing the drive belt is not very complicated - if you avoid disassembling more than strictly required! First, the counter mechanism is removed from the flywheel assembly. There are two small screws[^3] holding the counter mechanism in place.

<p align="center">
    <img src="Images/Int_03.jpeg" alt="Description" width="500">
</p>

When the counter mechanism is moved away, the small screw[^4] holding the flywheel bracket is revealed. At the same time the counter belt can easily removed.

<p align="center">
    <img src="Images/Int_04.jpeg" alt="Description" width="500">
</p>

Now the small screw in the corner of the flywheel bracket is **PARTIALLY** loosened. You do not want to completely remove this screw! Just unscrew it a few turns.

<p align="center">
    <img src="Images/Int_05.jpeg" alt="Description" width="500">
</p>

With the screws out of the way, the flywheel metal bracket is slightly lifted - just so that the drive belt can be navigated through the small gap. Now the belt is free to be pulled out from the drive flywheel and the gears. See picture below.

<p align="center">
    <img src="Images/Int_06.jpeg" alt="Description" width="500">
</p>

The belts are actually not in too bad condition. I have seen much worse. But they do lack some elasticity. Also, they are a bit deformed. See picture below.

<p align="center">
    <img src="Images/Int_07.jpeg" alt="Description" width="600">
</p>

New replacement belts are ordered from [dataserve-retro.co.uk](dataserve-retro.co.uk). Notice that the belt size is named the "Taiwan version". These belts fit 1530 C2N datasettes which are made in Taiwan - and this Digilog datasette.

<p align="center">
    <img src="Images/Int_08.jpeg" alt="Description" width="400">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Tape head azimuth alignment

To check the tape head azimuth two software packages are used. [See Tools page for details.](https://refurbished-commodore.com/tools):

- Cassette-azimuth H. Diebek
- Azimuth Head Alignment Kit

But now I discover something which I have not observed before: there is no easy way to adjust the head azimuth! On other datasette players there is a small hole which purpose is to allow for a small screwdriver to adjust the azimuth on the R/W head. But on the Digilog datasette there are no such hole. It is very important to adjust the R/W while the datasette is completely assembled.

Nevertheless, both the Cassette-azimuth and the Azimuth Head Aligment kit shows that the R/W heads are properly aligned. There is maybe a slight misalignment seen from the Cassette-azimuth software, but I do not think this is substantial. And the Azimuth Head Alignment Kit is counting to 8000 without any issues each time (bang on every attempt). 

<p align="center" float="left">
    <img src="Images/Head_01.png" alt="Description" width="400">
    <img src="Images/Head_02.png" alt="Description" width="400">
</p>

# Tape speed

The idea is smart, but simple:

A professional Speed Calibration Audio cassette which contains a 440 Hz and 3150 Hz sinewave recording is loaded in the datasette. During playback of this tape a software (developed by J. Deorgee) reads the registered frequency on a Commodore 64. The idea is to adjust the speed until the recorded frequency, 3150 Hz, is measured.

Note that this great idea is not mine. The idea is based on a magnificent article by [Jan Derogee and his Tape Frequency Counter software.](https://janderogee.com/projects/1530_tapespeed/1530_tapespeed.htm)

My experience so far is that the datasette (or datenrekorder) works best when the playback speed is in the range between 3150 - 3250 Hz. You could argue that the speed should be as close to 3150 Hz as possible, since this is the expected speed/frequency reading, but for reasons I have not understood yet I see that the tape deck works better with a slightly higher speed. I will continue to do these readings when refurbishing datasettes/datenrekorder to see if I can learn something!

As can be seen from the picture below the speed is bout 3175 Hz/443 Hz which is very close to the reference. I would say this is "bang-on".

<p align="center" float="left">
    <img src="Images/Head_03.png" alt="Description" width="400">
    <img src="Images/Head_04.png" alt="Description" width="400">
</p>

# Casing

The casing consists of a top and bottom cover. The top cover also includes a semi-transparent lid which can be removed. All in all, the covers does not appear to be very dirty. And I think that the colour is more or less the original. If this were yellowed I would expect the yellowing to be more random. The colour seem to be the same all over the covers.

There are some marks at the rear side of the top cover, and a "burn mark" from the cable which can be hard to remove, but the casing will be cleaned properly so hopefully it will look much better.

Before the covers are cleaned the top lid is removed. This is not very complicated, but be careful not to break the brittle plastic. The two plastic arms (one on each side) is pushed inwards, while at the same time the lid is pushed outwards. A small drop of machine sewing oil is used on the plastic arms to reduce the friction when removing it.

<p align="center">
    <img src="Images/Case_01.jpeg" alt="Description" width="700">
</p>

The covers are cleaned with mild soapy water and some glass cleaning spray.

<p align="center">
    <img src="Images/Case_02.jpeg" alt="Description" width="700">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Testing

*Playback*

Four original C64 games to be used for testing. Even if these games are old and worn the load without any problems at all. But, I also try with a few other games and they do not load as they should (they only load partially before crashing). Nevertheless, I think this is "as-good-as-it-gets" for this datasette.

<p align="center">
    <img src="Images/Test_20.jpeg" alt="Description" width="500">
</p>


<p align="center" float="left">
    <img src="Images/Test_02.png" alt="Description" width="225">
    <img src="Images/Test_03.png" alt="Description" width="225">
    <img src="Images/Test_04.png" alt="Description" width="225">
    <img src="Images/Test_05.png" alt="Description" width="225">
</p>

<p align="center" float="left">
    <img src="Images/Test_06.png" alt="Description" width="225">
    <img src="Images/Test_07.png" alt="Description" width="225">
    <img src="Images/Test_08.png" alt="Description" width="225">
    <img src="Images/Test_09.png" alt="Description" width="225">
</p>

<p align="center" float="left">
    <img src="Images/Test_01.png" alt="Description" width="225">
    <img src="Images/Test_10.png" alt="Description" width="225">
    <img src="Images/Test_11.png" alt="Description" width="225">
    <img src="Images/Test_12.png" alt="Description" width="225">
</p>

*Recording*

The saving functionality is also checked and verified. A small BASIC program is made and the SAVE command is used (and then the program is re-loaded). The LED is also on while recording is in progress.

**CONCLUSION** 

Even if this datasette loads both alignment software and some games without any problem at all I think that this datasette is marginal unfortunately. Why? My guess is that this is not an electronic issue, but a mechanical issue related to old (but not worn) parts which prevents some tape from loading. To elaborate:

- Probably the hardest game to load (the most worn tape) is "Ghostbusters". But this loads perfect without any issues at all. This points to the fact that the R/W head, amplifying circuits and A/D conversion works as it should.
- The tape speed is "bang on" with the new belts. This points in the direction that the analog data is being processed with a good steady pace. The majority of the mechanical drive work is operational.
- Tapes that fails to load / loads successfully is the same both when tested with top cover on and off. No difference. This points to the direction that the top cover does not affect the R/W alignment in any significant way.

Is it impossible to improve it further? Well, nothing is impossible, but to replace every old mechanical gear on this datasette is more or less hopeless. Low cost datasette are not designed to be serviced at this level. You will end up damaging the drive work more than you fix it.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Final result

<div align="center">

*"A picture is worth a thousand words"*

Below is a collection of pictures of the final result of the refurbishment of this Digilog datasette. Hope you like it! Click to enlarge!

</div>

<p align="center">
    <img src="Images/Final_01.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Final_02.jpeg" alt="Description" width="400">
    <img src="Images/Final_03.jpeg" alt="Description" width="400">
</p>

<p align="center" float="left">
    <img src="Images/Final_04.jpeg" alt="Description" width="400">
    <img src="Images/Final_05.jpeg" alt="Description" width="400">
</p>

<p align="center">
    <img src="Images/Final_06.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


<!-- MARK STOP -->




**Footnotes**

[^1]: Phillips pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm
[^2]: Phillips pan head (3.9 mm), Machine screw, Fully threaded, Thread diameter: 3.2 mm, Fastener length: 6.0 mm
[^3]: Phillips pan head (4.2 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 4.0 mm
[^4]: Phillips pan head (4.2 mm - without spacer), Machine screw, Partially threaded, Thread diameter: 3.5 mm, Fastener length: 5.0 mm

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
