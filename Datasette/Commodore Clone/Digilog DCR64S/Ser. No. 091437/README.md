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

The planned refurbishment activities for this Digilog DCR64S are as follows (the order may vary, and several activities may be carried out in parallel):

- [x] Refurbish the mainboard
- [x] Refurbish the internal drive mechanism
- [x] Refurbish the casing
- [x] Testing and validation

The plan may be updated during the refurbishment process. Sometimes I discover areas that require special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK START -->

# Starting point

This is one of many clones of the original Commodore 1530 (C2N) datasette. This particular clone, the Digilog DCR64S, is new to me, but I would expect it to be quite similar to the others. The datasette appears to be in fine condition. There are a few marks, including one (and only one!) cable burn mark—but I would not expect anything else.

I think the colour is original, in the sense that it has not yellowed. The dark colour is so even across the entire casing that I find it hard to believe this is due to yellowing. All the keys feel responsive, but the top lid is slightly difficult to press down after ejecting. I think this is normal, though. There is some oxidation on the pins of the datasette port connector.

All in all, this looks like a fine datasette from the outside. I do not know whether it works or not, but that will be investigated during the refurbishment.

DCR64S? What could it mean? My guess is that "DCR" is short for Data Cassette Recorder, and "64", yes, of course, refers to the Commodore 64.

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

Disassembly of the Digilog DCR64S starts by removing the four screws[^1] from the bottom cover.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

With the screws out of the way, the bottom cover is carefully lifted off. The interior, with its PCB, belts, and drive mechanism, is now exposed. One thing I immediately notice is that the PCB is marked **1531**. This is quite special, since the **1531** PCB is usually found in the original Commodore 1530 (C2N) datasette. So, this is either an original **1531** PCB or a 1:1 clone of it. A picture of the original Commodore **1531** PCB can be seen in the [HOWTO - Datasette head alignment](https://refurbished-commodore.com/datasette-head-alignment) article.

Below is a picture of the interior with the bottom cover removed (Digilog DCR64S).

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

The whole drive mechanism can simply be lifted out of the top cover. **NOTE:** I am not completely sure, but I had to press the EJECT button before I was able to release it.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

The top cover can be disassembled further: the top lid can be pushed out of the base. **WARNING:** This is old and brittle plastic! Be *very* careful when pushing the two arms (see arrows in the picture above) inwards. A small drop of machine sewing oil on the arms can help reduce friction when the lid is pushed out.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="500">
</p>

The next step is not complicated, but it is very easy to lose some small parts. On the back of the drive mechanism, there are three small springs attached to the six keys. These springs need to be released from the keys and then removed. A pair of small tweezers is highly recommended.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="500">
</p>

Before the metal shaft holding all the keys in place can be pulled out, the small E-clip on the right-hand side needs to be removed. This can be a bit tricky, but it can be done with a small flat-head screwdriver.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="400">
</p>

Below is a picture of all the small parts—THIS IS WHAT YOU ARE LOOKING FOR ON THE FLOOR!

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="800">
</p>

# Mainboard

As mentioned in the disassembly chapter, this PCB is marked **1531**, which is the version designation used on the original Commodore 1530 (C2N) datasette. The back of this Digilog PCB also looks identical to that of the original **1531** PCB. So, this is either a 1:1 clone of the original PCB—or it is actually an original Commodore PCB.

## Visual inspection

There is a substantial amount of old flux residue on the PCB. The flux itself is neither conductive nor corrosive, but it can become sticky as it ages. Dust and moisture can then accumulate in the residue, which can eventually lead to corrosion. So, during the refurbishment process, the PCB will be cleaned thoroughly with isopropanol to remove all the flux.

Below is a picture of the back of the **1531** mainboard before refurbishment.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="400">
</p>

To remove the mainboard from the rest of the datasette mechanism, the two screws[^2] (marked with thick arrows in the picture above) are removed. The black wire from the leaf switch underneath is desoldered from the PCB (marked with a thin arrow in the picture above). Also, to make removal easier, the transparent plastic band holding all the wires together is untied. See the picture below.

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="600">
</p>

Before the mainboard can be completely lifted from the datasette mechanism, the PCB is tilted slightly to expose the leaf switch, where the blue and black wires are connected. The small screw holding the leaf switch in place is removed.

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="600">
</p>

With the leaf switch out of the way, the whole mainboard can be lifted out of the datasette mechanism.

<p align="center">
    <img src="Images/Main_04.jpeg" alt="Description" width="800">
</p>

## Replacing the electrolytic capacitors

The front side of the mainboard also appears to be in fine condition. I can see some flux residue here as well, but other than that, I cannot see any damage or corrosion. There are three electrolytic capacitors (C7, C8, and C9) on the mainboard, all rated at 47 μF [16 V]. I cannot see any obvious signs of leakage or bulging, but I choose to replace them anyway.

<p align="center" float="left">
    <img src="Images/Main_05.jpeg" alt="Description" width="500">
    <img src="Images/Main_06.jpeg" alt="Description" width="500">
</p>

## Cleaning the leaf switch

The leaf switch is heavily oxidised. This oxidation is removed with a fibreglass pen and some fine-grit sandpaper.

<p align="center" float="left">
    <img src="Images/Main_07.jpeg" alt="Description" width="500">
    <img src="Images/Main_08.jpeg" alt="Description" width="500">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Drive mechanism

The drive mechanism is marked "WEICHIEN PW-33Z" and "87". See the pictures below. My immediate guess is that "87" refers to the year it was manufactured. This is supported by the fact that this datasette came with the [Commodore 128](https://github.com/RefurbishedCommodore/Commodore128/blob/main/Artwork%20310381%20(Rev%209)/Ser.%20No.%20DA%204%20354432/README.md), which is also expected to have been manufactured in 1987.

An AI search for "WEICHIEN PW-33Z" reveals the following:

> The Wei Chien PW-33Z is an internal cassette tape drive mechanism manufactured in Taiwan.
>
> During the 1980s, this specific component was widely sourced by electronics brands to build dedicated data recorders (datasettes) and cassette players for 8-bit home computers.
>
> A prominent example of its use is in the Noris Data Datenrekorder DR 1535, a popular third-party Commodore 64 cassette recorder distributed in Germany. Units produced around 1986 featured a sticker on the internal mechanism confirming it as the Wei Chien PW-33Z.

<p align="center">
    <img src="Images/Int_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Int_02.jpeg" alt="Description" width="800">
</p>

## Visual inspection

The first thing I notice is that there is surprisingly little dust and grease covering the drive mechanism. Usually, an old datasette is full of dust, but this is definitely not the case with this Digilog datasette. I cannot see any mechanical damage to the gears, flywheel, pinch roller, or capstan.

On the other hand, the large drive belt seems to have lost some of its elasticity. It is not in terrible condition, but it would probably benefit from being replaced.

## Replacing the rubber belts

There are two rubber belts in the datasette:

- The drive belt, which transfers power from the motor to the flywheel
- The counter belt, which connects the PLAY/FF gears to the three-digit counter

It is good practice to replace both of these, although replacing the counter belt is not strictly necessary.

Replacing the drive belt is not very complicated—provided you avoid disassembling more than is strictly necessary! First, the counter mechanism is removed from the flywheel assembly. There are two small screws[^3] holding the counter mechanism in place.

<p align="center">
    <img src="Images/Int_03.jpeg" alt="Description" width="500">
</p>

When the counter mechanism is moved out of the way, the small screw[^4] holding the flywheel bracket is revealed. At the same time, the counter belt can easily be removed.

<p align="center">
    <img src="Images/Int_04.jpeg" alt="Description" width="500">
</p>

Now the small screw in the corner of the flywheel bracket is **PARTIALLY** loosened. You do not want to remove this screw completely! Just unscrew it a few turns.

<p align="center">
    <img src="Images/Int_05.jpeg" alt="Description" width="500">
</p>

With the screws out of the way, the metal flywheel bracket is lifted slightly—just enough to allow the drive belt to be manoeuvred through the small gap. The belt can now be pulled free from the flywheel and the gears. See the picture below.

<p align="center">
    <img src="Images/Int_06.jpeg" alt="Description" width="500">
</p>

The belts are actually not in too bad a condition. I have seen much worse. But they do lack some elasticity, and they are also a bit deformed. See the picture below.

<p align="center">
    <img src="Images/Int_07.jpeg" alt="Description" width="600">
</p>

New replacement belts are ordered from [dataserve-retro.co.uk](https://dataserve-retro.co.uk). Notice that the belt size is listed as the "Taiwan version". These belts fit 1530 C2N datasettes made in Taiwan, as well as this Digilog datasette.

<p align="center">
    <img src="Images/Int_08.jpeg" alt="Description" width="400">
</p>

## Cleaning the read head, capstan, pinch roller and moving parts

After the new belts are installed and the function keys are reassembled, the read head, capstan, and pinch roller are cleaned. The reason for doing this while the datasette is partly reassembled is that it can then be connected to and powered by a Commodore 64. Functions such as PLAY/FF/REW can be activated, which makes the moving parts... move! And while they are moving, the parts can be cleaned.

<p align="center">
    <img src="Images/Int_09.jpeg" alt="Description" width="400">
</p>

The videos below show how this is done. Note that these videos are not from this particular datasette, but the principles are the same.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Tape head azimuth alignment

To check the tape head azimuth, two software packages are used. [See the Tools page for details.](https://refurbished-commodore.com/tools)

- Cassette-azimuth H. Diebek
- Azimuth Head Alignment Kit

But now I discover something I have not observed before: there is no easy way to adjust the head azimuth! On other datasette players, there is a small hole whose purpose is to allow a small screwdriver to adjust the azimuth of the R/W head. But on the Digilog datasette, there is no such hole. It is very important to adjust the R/W head while the datasette is completely assembled.

Nevertheless, both Cassette-azimuth and the Azimuth Head Alignment Kit show that the R/W head is properly aligned. There may be a slight misalignment visible in the Cassette-azimuth software, but I do not think it is significant. And the Azimuth Head Alignment Kit counts to 8000 without any issues, every single time (bang on every attempt).

<p align="center" float="left">
    <img src="Images/Head_01.png" alt="Description" width="400">
    <img src="Images/Head_02.png" alt="Description" width="400">
</p>

# Tape speed

The idea is smart, but simple:

A professional Speed Calibration Audio cassette containing 440 Hz and 3150 Hz sine-wave recordings is loaded into the datasette. During playback, software (developed by J. Deorgee) reads the measured frequency on a Commodore 64. The idea is to adjust the speed until the recorded frequency of 3150 Hz is measured.

Note that this great idea is not mine. It is based on a magnificent article by [Jan Derogee and his Tape Frequency Counter software](https://janderogee.com/projects/1530_tapespeed/1530_tapespeed.htm).

My experience so far is that the datasette (or Datenrekorder) works best when the playback speed is in the range of 3150–3250 Hz. You could argue that the speed should be as close to 3150 Hz as possible, since this is the expected speed/frequency reading. But, for reasons I have not yet understood, I find that the tape deck works better at a slightly higher speed. I will continue taking these readings when refurbishing datasettes and Datenrekorder to see if I can learn something!

As can be seen from the picture below, the speed is about 3175 Hz/443 Hz, which is very close to the reference. I would say this is "bang on".

<p align="center" float="left">
    <img src="Images/Head_03.png" alt="Description" width="400">
    <img src="Images/Head_04.png" alt="Description" width="400">
</p>

# Casing

The casing consists of a top and a bottom cover. The top cover also includes a semi-transparent lid that can be removed. All in all, the covers do not appear to be very dirty. And I think the colour is more or less original. If the casing were yellowed, I would expect the yellowing to be more uneven. The colour seems to be the same all over the covers.

There are some marks on the rear side of the top cover, as well as a "burn mark" from the cable that may be difficult to remove. But the casing will be cleaned thoroughly, so hopefully it will look much better.

Before the covers are cleaned, the top lid is removed. This is not very complicated, but be careful not to break the brittle plastic. The two plastic arms (one on each side) are pushed inwards while, at the same time, the lid is pushed outwards. A small drop of machine sewing oil is applied to the plastic arms to reduce friction when removing the lid.

<p align="center">
    <img src="Images/Case_01.jpeg" alt="Description" width="700">
</p>

The covers are cleaned with mild soapy water and some glass-cleaning spray.

<p align="center">
    <img src="Images/Case_02.jpeg" alt="Description" width="700">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Testing

*Playback*

Four original C64 games are used for testing. Even though these games are old and worn, they load without any problems at all. But I also try a few other games, and they do not load as they should (they only load partially before crashing). Nevertheless, I think this is "as good as it gets" for this datasette.

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

The recording functionality is also checked and verified. A small BASIC program is created and saved using the SAVE command. The program is then loaded again to verify the recording. The LED also lights up while recording is in progress.

**CONCLUSION**

Even though this datasette loads both alignment software and some games without any problems, I think it is unfortunately somewhat marginal. Why? My guess is that this is not an electronic issue, but rather a mechanical issue related to old (but not worn-out) parts that prevent some tapes from loading. To elaborate:

- Probably the hardest game to load (the most worn tape) is "Ghostbusters". But this loads perfectly, without any issues at all. This suggests that the R/W head, amplifying circuits, and A/D conversion are working as they should.
- The tape speed is "bang on" with the new belts. This suggests that the analogue data is being processed at a good, steady pace. The majority of the mechanical drive mechanism appears to be working correctly.
- Tapes that fail to load, and tapes that load successfully, behave the same way whether the top cover is on or off. There is no difference. This suggests that the top cover does not affect the R/W head alignment to any significant degree.

Is it impossible to improve it further? Well, nothing is impossible, but replacing every old mechanical component in this datasette is more or less hopeless. Low-cost datasettes are not designed to be serviced to this level. You will end up damaging the drive mechanism more than you fix it.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Final result

<div align="center">

*"A picture is worth a thousand words"*

Below is a collection of pictures showing the final result of the refurbishment of this Digilog datasette. Hope you like it! Click to enlarge!

</div>

<p align="center">
    <img src="Images/Final_01.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Final_02.jpeg" alt="Description" width="600">
</p>

<p align="center" float="left">
    <img src="Images/Final_05.jpeg" alt="Description" width="600">
</p>

<p align="center" float="left">
    <img src="Images/Final_03.jpeg" alt="Description" width="600">
</p>

<p align="center" float="left">
    <img src="Images/Final_04.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Final_06.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


<!-- MARK STOP -->




**Footnotes**

[^1]: Phillips pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm
[^2]: Phillips pan head (3.9 mm), Machine screw, Fully threaded, Thread diameter: 3.2 mm, Fastener length: 6.0 mm
[^3]: Phillips pan head (4.2 mm), Machine screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 4.0 mm
[^4]: Phillips pan head (4.2 mm - without spacer), Machine screw, Partially threaded, Thread diameter: 3.5 mm, Fastener length: 5.0 mm

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
