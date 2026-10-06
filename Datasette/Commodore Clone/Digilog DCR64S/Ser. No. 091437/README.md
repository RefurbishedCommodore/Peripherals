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
    </li>
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
      <a href="#interior-drive-mechanism">Interior drive mechanism</a>
    </li>
    <li>
      <a href="#final-result">Final result</a>
    </li>
  </ul>
</details>

# Refurbishment activities

The planned refurbishment activites for this Digilog DCR64S (Order may vary. Several of them in parallel):

- [ ]Refurbish the mainboard
- [ ]Refurbish the internal drive mechanics
- [ ]Refurbish the casing
- [ ]Testing and validation

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


# Interior drive mechanism

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



<!-- MARK STOP -->

**Footnotes**

[^1]: Phillips pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm
[^2]: Phillips pan head (3.9 mm), Machine screw, Fully threaded, Thread diameter: 3.2 mm, Fastener length: 6.0 mm


[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
