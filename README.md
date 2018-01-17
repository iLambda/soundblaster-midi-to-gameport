# soundblaster-midi-to-gameport

This repository contains a PCB schematic for making a MIDI to Gameport cable for your Soundblaster.

The board's design is based on [Cryogenius's MIDI to Gameport schematic](http://www.cryogenius.com/hardware/sbmidi/). It is a direct implementation of the schematic found on the page.

## schematic

![The board's schematic](/hardware/schematic.gif)

(from [Cryogenius's MIDI to Gameport](http://www.cryogenius.com/hardware/sbmidi/) page)

### 6N137 variant

If you must use a 6N137 (which is more common), you can just use the same PCB and replace *I1* by a **6N137** and *R2* by a 10k resistor.

## pcb

The printable typon can be found at hardware/typon.png. The typon with overlayed components can be found at hardware/pcb.png. They both are real sized images to be printed with a resolution of 600dpi.

![The actual board with overlayed components on top.](/hardware/pcb.png)

The list of parts you need to build the circuit can be found below.

### connectors
* *MIDI IN/OUT* : Female 5-DIN connector
* *GAMEPORT OUT* : Male SUB-D 15pins

### capacitors
* *C1, C2* : .01 µF

### diodes
* *D1* : 1N4148

### ICs & transistors
* *I1* : 6N136
* *I2, I3* : 2N3904

### resistors
* *R1, R4* : 270 Ω
* *R2* : 5,6 kΩ (or 10kΩ if you use a 6N137 for *I1*)
* *R3* : 10 kΩ
* *R5* : 2.2 kΩ
* *R6* : 220 Ω
