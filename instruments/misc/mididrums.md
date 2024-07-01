---
title: MIDI Drums
author: Carl Mylo
date: 
category: Instruments
layout: post
---

## NOTES:

* Requires an electronic MIDI Drum Kit connected via USB or a MIDI to USB interface.
	* **Your MIDI Drum Kit needs to be set to MIDI Channel 10 and standard GM mapping.**  These should be default settings but consult the manual for your MIDI Drum Kit to make sure.
* D-Pad: Left and D-Pad: Right cannot be used. This makes slowing down practice mode and cycling through trainers impossible.

## Instructions:

**Right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/iod.png "I/O")
* ![A tan square with a solid outline](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") : 
	* 🥁 **Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it**.

## Mapping
By default:
* START: Hihat Pedal, Hihat Pedal, Hihat Pedal, Snare
* SELECT: Hihat Pedal, Hihat Pedal, Hihat Pedal, Snare Rim
* Song select shortcuts: Hihat Pedal, Hihat Pedal, Hihat Pedal, Kick

### Additional Setup:

You can adjust a variety of options in the `rb3drums.yml` file, located within the `config` folder inside your RPCS3 installation folder.
Below are the defaults and what each option does.

`Pulse width ms: 30` = How long each drum pad hit is "held" for. **You should leave this alone.**
`Minimum velocity: 10` = The minimum velocity (how hard a pad is hit) needed for a signal to be sent. Anything below this number will not send a signal.
`Combo window in milliseconds: 2000`  = Determines how long you have to press the Combos for Start, Select, and Kick Hold.
`Stagger cymbal hits: true` = If you hit two cymbals at the same time, one will be delayed by the "Pulse width ms" above. **You should leave this alone.**
`Midi id to note override: ""` = Allows you to remap what each MIDI note does. Read [[Remapping]](#remapping) for more information.
`Combo Start: HihatPedal,HihatPedal,HihatPedal,Snare` = Defines what combo will trigger the Start button.
`Combo Select: HihatPedal,HihatPedal,HihatPedal,SnareRim` = Defines what combo will trigger the Select button.
`Combo Toggle Hold Kick: HihatPedal,HihatPedal,HihatPedal,Kick` = Defines what combo will trigger the Hold Kick action, for library navigation.
`Midi CC status: 176` = Defines the status byte. Can be notated as `0xB0` as well. **You should leave this alone.**
`Midi CC control number: 4` = Defines the number of the Continuous Controller (CC), which acts as the hi-hat pedal. **You should leave this alone.**
`Midi CC threshold: 64` = Defines the middle point the hi-pedal pedal goes from closed to open.
`Midi CC invert threshold: false` = Inverts the range for the hi-hat pedal, mentioned above.

#### Remapping
If your MIDI Drum Kit has incompatible mapping, you can remap using `Midi id to note override: ""` with the corrected notes.
* To do this:
	* Go to [MIDI Monitor](https://www.midimonitor.com/)
	* Play the pad you want to replace to find its MIDI Note number ("Note #[number]").

The file uses the following note names:

`Kick`  
`HihatPedal`  
`Snare`  
`SnareRim`  
`HiTom`  
`LowTom`  
`FloorTom`  
`HihatWithPedalUp`  
`Hihat`  
`Ride`  
`Crash`

Examples of common replacements:
* Blue cymbal is mapped to `Note #51` and Green cymbals is mapped to `Note #49` and your kit has these reversed.
	* `Midi id to note override: "49=Ride,51=Crash"` will reverse them to be closer to the game's layout
* You want to map Open Hi-Hat to Blue cymbal.
	* `Midi id to note override: "46=Ride"`

In `rb3drums.yml`, you will find `Combo Start`, `Combo Select`, `Combo Toggle Hold Kick`, which allow you to customize the combos to activate their respective buttons.

### Default Mapping

| **MIDI Note#** | **Trigger Type** | **In-Game Action** |
|:--------:|:-------------------:|:-----------------:|
| **38**, 31, 34, 37, 39, 40 | Snare | ![Red Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/rp.png "Red Pad") |
| **48**, 50 | Hi-tom | ![Yellow Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/yp.png "Yellow Pad") |
| **45**, 50 | Low-tom | ![Blue Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/bp.png "Blue Pad") |
| **41**, 43 | Floor-tom | ![Green Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/gp.png "Green Pad") |
| **22**, 26, 42, 46, 54 | Hi-Hat Cymbal | ![Yellow Cymbal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/yc.png "Yellow Cymbal") |
| **51**, 53, 56, 59 | Ride Cymbal | ![Blue Cymbal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/bc.png "Blue Cymbal") |
| **49**, 52, 55, 57 | Crash Cymbal | ![Green Cymbal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/gc.png "Green Cymbal") |
| **33**, 35, 36 | Kick Pedal | ![Foot Pedal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/kp.png "Foot Pedal") |
| **44** | Hi-Hat Pedal | Hi-Hat Pedal |
| **CC#4 (Foot controller)** | Hi-Hat Pedal Position | Allows Hi-Hat pedal to be held closed |

![Platform](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/plat/midi.png "Platform") 

![Controller](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/cont/mididrumscontroller.png "Controller") 

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)


Research by [[Linos]](https://www.youtube.com/@LinosMelendi)
Implemented by [[nswarm]](https://github.com/nswarm)