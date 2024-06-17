---
title: Instrument Repo
author: Carl Mylo
date: 
category: Instruments
layout: post
---

# What is this?

A repository of premade controller profiles for RPCS3 to help newcomers to Rock Band 3. These files should be simple drag and drop configurations for controllers.

## How to install:
Before you install, **if you have any bindings in `config\input_configs\BLUS30463`, you should back them up because they will be overwritten.**

1. Download the .7z file in the folder for the instrument(s) you want to use.
2. Extract the .7z file.
3. Drag `config` folder into the folder you have RPCS3 in.

![A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder.](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/xtra/instrepoinstall.gif "Installing a configuration from the Instrument Repo")

Most of the time, these controller profiles should work out of the box but if they don't, try changing the controller listed in "`Devices`", next to the "`Refresh`" button until it receives an input. You can edit this while the game is running.

The profiles are formatted for single players. If you need to use a combination of various controllers for local multiplayer or want to quickly swap between multiple instruments, you can try the guide below for manually [[#mapping]](#mapping) additional controllers.

Alternatively, you can combine multiple files if you know your way around text editors like Notepad++ or Sublime Text.
Select everything from line 2 to the end of line 86 in the `Default.yml` file of the instrument you want to add, then copy it. 
Paste it into:
* Line 88 to 172 for Player 2
* Line 174 to 258 for Player 3
* Line 260 to 344 for Player 4
* Line 346 to 430 for Player 5
* Line 432 to 516 for Player 6
* Line 518 to 602 for Player 7

## Instrument List:

#### Drums:
* [[MIDI Drums]](https://rb3pc.milohax.org/instruments/misc/mididrums) - Does not include a profile but does have instructions. Requires a drum kit with at least one kick drum, one snare drum, one hi-hat, two cymbals, and three toms. Can have either MIDI to USB or USB outputs.
	* Requires [[additional configuration]](https://github.com/hmxmilohax/rb3-pc/tree/TheGreatSplit/instruments/misc/mididrums)
* [[Roll Limitless]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Roll%20Limitless%20Drums.7z) - Requires a drum kit with at least one kick drum, one snare drum, one hi-hat, two cymbals, and three toms. Must have a MIDI output.
	* Requires [[additional configuration]](https://rb3pc.milohax.org/instruments/misc/rolllimitless)
* [[Xbox 360 Rock Band Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20Rock%20Band%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/rbdrms)
* [[Xbox 360 Rock Band MIDI Pro Adapter Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20MIDI%20Pro%20Adapter%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/mpa)
* [[Xbox 360 Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/ghdrms)
* [[PS3 Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/PS3%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/ps3/ghdrms)
* [[Wii Rock Band Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Wii%20Rock%20Band%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/wii/rbdrms)
* [[Wii Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Wii%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/wii/ghdrms)

#### Guitars:
* [[Xbox 360 Rock Band Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20Rock%20Band%20Guitar.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/rbgtrs)
* [[Wii Rock Band Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Wii%20Rock%20Band%20Guitars.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/wii/rbgtrs)
* [[Xbox 360/PC Guitar Hero Xplorer Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20Guitar%20Hero%20Xplorer.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/xplorer)
	* Requires [[additional configuration]](https://rb3pc.milohax.org/instruments/xbox/xplorer)
* [[Xbox 360 Guitar Hero Les Paul Guitars]](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/instrument-repo/Xbox%20360%20Guitar%20Hero%20Les%20Paul.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/ghlp)
* [[Wii Guitar Hero Les Paul (Raphnet) Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BRaphnet%5D.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/wii/raphlp)
* [[Wii Guitar Hero Les Paul (PI Pico) Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BPi%20Pico%5D.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/misc/picolp)
* [[PS3 Guitar Hero Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/PS3%20Guitar%20Hero%20Genericaster.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/ps3/ghwttar)
* [[Xbox 360 Guitar Hero Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/Xbox%20360%20Guitar%20Hero%20Genericaster%20Guitar.7z) - [[Notes]](https://rb3pc.milohax.org/instruments/xbox/ghwttar)
* [[PS2 Guitar Hero SG Guitar]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/PS2%20Guitar%20Hero%20SG%20Guitar.7z) - **Requires a specific adapter**. [[Notes]](https://rb3pc.milohax.org/instruments/misc/ps2sg)
* [[PS3 Guitar Hero Les Paul]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/PS3%20Guitar%20Hero%20Les%20Paul%20Guitar.7z) - **Not a recommended controller**. [[Notes]](https://rb3pc.milohax.org/instruments/ps3/ghlp)
* [[PC-Mac Guitar Hero World Tour Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/TheGreatSplit/instrument-repo/PC-Mac%20Guitar%20Hero%20World%20Tour%20Genericaster.7z) - **Not a recommended controller**. [[Notes]](https://rb3pc.milohax.org/instruments/misc/pcghwt)
* [[PS3 Dualshock 3 Controller (Padtar)]](https://rb3pc.milohax.org/instruments/ps3/ds3) - Does not include a profile but does have instructions.
* [[Xbox Controller (Padtar)]](https://rb3pc.milohax.org/instruments/xbox/xb1pad) - Does not include a profile but does have instructions.
* [[PC Keyboard (Padtar)]](https://rb3pc.milohax.org/instruments/misc/pckeyboard) - Does not include a profile but does have instructions.


## Missing Instruments:

#### TODO:
* [TODO] Xbox One/Xbox Series S/X Riffmaster Guitar
* [TODO] Xbox One/Xbox Series S/X Rock Band 4 Guitar
* [TODO] Xbox One/Xbox Series S/X Rock Band 4 Drums
* [TODO] Wii Rock Band MIDI Pro Adapter Drums
* [TODO] Wii Rock Band Drums
* [TODO] Wii Guitar Hero Genericaster Guitar
* [TODO] PS2 Guitar Hero Kramer Striker
* [TODO] Arduino Drums

If you own any of these instruments and wish to help, please contact Carl Mylo on the [[Milohax Discord server]](https://rb3dx.neocities.org/downloads.html) for information.

#### REJECTED:

* Rock Band 3 Fender Mustang Pro Guitar
	* PS3 version works via passthrough (Zadig), and PS3, X360, and Wii versions work via a MIDI to USB interface with the Emulated Midi Device in RPCS3 in the I/O tab.
* Rock Band 3 Squier Stratocaster Pro Guitar
	* PS3 version works via passthrough (Zadig), and PS3, X360, and Wii versions work via a MIDI to USB interface with the Emulated Midi Device in RPCS3 in the I/O tab.
* Rock Band Guitars (PS3 Versions)
	* They work via passthrough natively.
* Rock Band Drums (PS3 Versions)
	* They work via passthrough natively.
* Rock Band 4 Drum Kit (PS4 Version)
	* Bluetooth latency is unacceptable.
	* Pro Cymbals refuse to work due to the format they're in.
* Rock Band 4 Guitar Controllers (PS4 Version)
	* Bluetooth latency is unacceptable.
	* Whammy, tilt, and effects switch can't be mapped.

## Mapping:

![A screenshot of RPCS3's right click menu, showing "Create Custom Gamepad Configuration" highlighted](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

* If you are planning on plugging in multiple instruments, _you must set them on different ports_ (Player 1, Player 2, etc).
* PS3 guitar, drum controllers, and MIDI Pro Adapters for the Rock Band series are plug and play.
* If you're using PS3 (Guitar Hero), or Wii guitars, set the “Handlers” option to “MMJoyStick.” 
* If you're using Xbox 360/One/Series guitar controllers, set the “Handlers” option to “XInput.”
* If you're using PS3 (Guitar Hero), Wii, or Xbox 360 drum controllers, set the “Handlers” option to “MMJoyStick.”
* If you're using a Xbox One or Xbox Rock Band Drums, or Xbox 360 MIDI Pro Adapter for drums, set the "Handlers" option to "XInput."

Below are the buttons you should map in RPCS3's Gamepad Settings.

**If your controller isn't being detected, click “Refresh”. If that doesn't solve it, restart RPCS3.**

Once you've finished configuring, **remember to click “Save”.**

  
**Guitar**:  
Make sure you **set “Device Class” to “Guitar”.**

**Switch the drop-down menu next to it to "Rock Band" if you're using a Rock Band guitar or leave it on “Guitar Hero” if you're using a Guitar Hero guitar**. 
 
**Some guitar controllers** (most notably Guitar Hero controllers) misbehave and **refuse to map sometimes. If you try mapping a button and get “U+”, click “Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

| **RPCS3**          | **PS/Wii Rock Band Guitars** | **Xbox Rock Band Guitars** | **Guitar Hero Guitars** |
|:------------------:|:---------------------:|:---------------------:|:-----------------------:|
| Cross | ![Green Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/gf.png "Green Fret") | ![Green Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/gf.png "Green Fret") | ![Green Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/rf.png "Red Fret") | ![Red Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/rf.png "Red Fret") | ![Red Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/bf.png "Blue Fret") | ![Yellow Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/yf.png "Yellow Fret") | ![Yellow Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Yellow Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/yf.png "Yellow Fret") | ![Blue Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/bf.png "Blue Fret") | ![Blue Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/of.png "Orange Fret") | ![Orange Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/of.png "Orange Fret") | ![Orange Fret](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbu.png "Strumbar Up") | ![Strumbar Up](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbu.png "Strumbar Up") | ![Strumbar Up](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbd.png "Strumbar Down") | ![Strumbar Down](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbd.png "Strumbar Down") | ![Strumbar Down](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/sbd.png "Strumbar Down") |
| D-Pad: Left | ![D-Pad: Left](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpl.png "D-Pad: Left") | ![D-Pad: Left](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpl.png "D-Pad: Left") | ![D-Pad: Left](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpl.png "D-Pad: Left") |
| D-Pad: Right | ![D-Pad: Right](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpr.png "D-Pad: Right") | ![D-Pad: Right](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpr.png "D-Pad: Right") | ![D-Pad: Right](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/dpr.png "D-Pad: Right") |
| Right Stick: <br/> Left/Right <br/> (ignore Left on Rock Band Wii guitars) | ![Whammy Bar](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/wb.png "Whammy Bar") | ![Whammy Bar](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/wb.png "Whammy Bar") | ![Whammy Bar](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/wb.png "Whammy Bar") |
| Right Stick: Up/Down | ![Effects Switch](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/fx.png "Effects Switch") | | |
| L2 | | ![Effects Switch](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/fx.png "Effects Switch") | |
| L2 | ![Solo Buttons](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/solo.png "Solo Buttons") | | |
| L3 | | ![Solo Buttons](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/solo.png "Solo Buttons") | |
| R1 | ![Tilt](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/ts.png "Tilt") | ![Tilt](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/gtrs/ts.png "Tilt") | Does not work |


**Drums**:

Make sure you **set “Device Class” to “Drum”.**

**Switch the drop-down menu next to it to "Rock Band Pro" if you're using Rock Band drums or Rock Band Drums with Pro expansions. Do **NOT** use the regular "Rock Band" type. Leave it on “Guitar Hero” if you're using Guitar Hero drums.**

If you're using a 360 MPA with a drum kit, please ask [**[the Milohax discord]**](https://rb3dx.neocities.org/discord) for the mapping as they know more about this.

| **RPCS3**    | **Rock Band Drums** | **Guitar Hero Drums** |
|:--------:|:-------------------:|:-----------------:|
| Cross | ![Green Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/gp.png "Green Pad") |
| Circle | ![Red Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/rp.png "Red Pad") |
| Square | ![Blue Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Cymbal](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/yc.png "Yellow Cymbal") |
| L1 | ![Foot Pedal](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/kp.png "Foot Pedal") |
| D-Pad | ![D-Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 | ![Second Foot Pedal](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/rb/kp.png "Second Foot Pedal") | ![Orange Cymbal](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/drms/gh/oc.png "Orange Cymbal") |
| R3 | Cymbal Modifier | |
| L3 | Pad Modifier | |


**Vocals**:  
*For vocals*, you can *use regular controllers*. If you're using a PS4 controller, switch to DS4. If you're using an Xbox One controller, switch to XInput. There's no need to remap anything. Alternatively, you can use a typing keyboard and refer to this guide to customize the mapping according to your preferences.

| **PlayStation (DS4)** | **Xbox One (XInput)** | **Use**                         | **Alt Use**         |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
| ![Left Stick](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/ls.png "Left Stick") | ![Left Stick](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/ls.png "Left Stick") | Navigation |
| ![D-Pad](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/dp.png "D-Pad") | ![Left Stick](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/dp.png "D-Pad") | Navigation |
| ![Cross Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/x.png "Cross Button") | ![A Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/a.png "A Button") | Select                          |
| ![Circle Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/o.png "Circle Button") | ![B Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/b.png "B Button") | Back                            | Mic 3 Volume (Song) |
| ![Square Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/s.png "Square Button") | ![X Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/x.png "X Button") | Mic 1 Volume (Song) |
| ![Triangle Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/t.png "Triangle Button") | ![Y Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/y.png "Y Button") | View More Info (Library)        | Mic 2 Volume (Song) |
| ![Options Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/opt.png "Options Button") | ![Options Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/opt.png "Options Button") | Options                         | Pause (Song)        |
| ![Share Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/shr.png "Share Button") | ![View Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/viw.png "View Button") | Filters (Library)               | Overdrive (Song)    |
| ![L1 Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/l1.png "L1 Button") | ![Left Bumper](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/lb.png "Left Bumper") | Guide Part Selection (Practice) |
| ![L2 Trigger](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/l2.png "L2 Trigger") | ![Left Trigger](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/lt.png "Left Trigger") | Vocal Part Selection (Practice) |
| ![R1 Button](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/r1.png "R1 Button") | ![Right Bumper](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/rb.png "Right Bumper") | Vocal Track Volume (Song)       |
| ![R2 Trigger](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/ps4/r2.png "R2 Trigger") | ![Right Trigger](https://github.com/hmxmilohax/rb3-pc/blob/TheGreatSplit/images/btns/ctrls/xbox/rt.png "Right Trigger") | Pitch Correction (Song)         |


## CREDITS:

* [[TheNathannator's]](https://github.com/TheNathannator) [[PlasticBand GitHub]](https://github.com/TheNathannator/PlasticBand) for outstanding documentation on controllers.
* [[Jnack]](https://www.youtube.com/@jnackmclain) - Xbox 360 Xplorer, Xbox 360 MIDI Pro Adapter profiles
* [[Linos]](https://www.youtube.com/@LinosMelendi) - MIDI Drums profile 
* [[KrazzyKlown]](https://www.youtube.com/@KrazzyKlown) - Xbox 360 Xplorer profile
* [[gonakil1ya]](https://linktr.ee/Gonakil1ya) - Xbox 360 Rock Band Kit, Xbox 360 Rock Band Guitar, Xbox 360 Guitar Hero Les Paul, and Xbox 360 Guitar Hero Genericaster profiles
* [[GamerPerson22]](https://www.youtube.com/channel/UCC5SlXPlnlGwBG7w6mvfx8g) - Wii Les Paul Raphnet, Xbox 360 Guitar Hero Drums, PS3 Guitar Hero Genericaster, and Wii Guitar Hero Drums profiles
* [Derd] - PS3 Guitar Hero World Tour, PC-Mac Guitar Hero World Tour Genericaster profiles
* [Uzny] - Roll Limitless profile
* [16bitblastprocessing] - PS3 Guitar Hero Les Paul
* [heartworthbreaking] - Wii Guitar Hero Ardwiino PI Pico Guitar profile
* [[cas]](https://www.youtube.com/channel/UCw2JKh7_Zt65kjENqjnvm_g) - PS2 Guitar Hero SG Guitar profile
* [[scott0852]](https://twitter.com/scott0852) - Wii Rock Band Drums
* [SlothDemon](https://www.youtube.com/@SlothDemon1991) - DS3 Padtar instructions
* [[Clone Hero Wiki]](https://wiki.clonehero.net/) - Instrument pictures.
