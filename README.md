# CherryZXKeyboard

![Keyboard](/Images/Keyboard06.jpg)

The goal of the project was to create a keyboard consisting of Cherry MX keys with two-layer keycaps, into which printed labels will be inserted. At the same time, I wanted the keyboard to have a better layout of the keys (for example, cursor keys), to be easy to manufacture and install (ideally without SMD), from available components, cheap and at the same time to write well on it.

I wasn't limited to a standard format as the goal was to build a ZX MAX 128 clone and put it in my own cabinet.

Since the ZX Spectrum+ membrane is double-layered, the 48p-KDLX solution was suitable, i.e. electronically secured switching of two contacts at the same time, since the MX buttons have only one contact.

![3D](/Images/CherryZXKeyboard3D.png )

## What is needed to make

### PCB
In the [Gerber](/Gerber) directory there are materials for production. For example, on [https://jlcpcb.com](https://jlcpcb.com), just pack this directory in ZIP format, insert it into the order, and after payment, you have printed circuit boards within 2 weeks, even with the cheapest selected transport.

### Electronic Parts
These are common cheap parts from a local dealer - for example TME.
30 pcs Diode BAT42
1 pc Electrolytic capacitor 10u
5 pcs Resistor network (6x-1-104LF) 
5 pcs 74HC4066
5 pcs DIP14 socket

### Mechanical MX Switches (62 pcs) ![AliExpress](https://www.aliexpress.com/item/1005004285423123.html )
You can use the original, but rather expensive Cherry MX, or, like me, a copy of the MX switches from AliExpress.
![MX](/Images/MX.png )

### Keycaps
Three types of keycaps are used:

#### - Standard buttons (53 pcs) ![AliExpress](https://www.aliexpress.com/item/1005004623750938.html )
![KeyCap](/Images/Keyboard05.jpg )


#### - Wide buttons (4 pcs) ![AliExpress](https://www.aliexpress.com/item/1005003201365793.html )
![WideKeyCaps](/Images/WideKeyCaps.jpg )


#### - Space bar 6.25u (1 pc) ![AliExpress](https://www.aliexpress.com/item/1005003211865080.html )
![SpaceBar](/Images/SpaceBar.jpg )

### Mechanical stabilizer for spacebar 6.25u (1 pc) ![AliExpress](https://www.aliexpress.com/item/1005002552011081.html )
![Stabilisers](/Images/Stabilisers.jpg )

### 3D printed inserts
I divided the printing of the mat into 2 parts so that it would not be a problem to print it on a standard size 3D printer. The documents in STL format are in the [Stl](./Stl) directory.

![Printed01](/Images/Keyboard01.jpg )
![Printed02](/Images/Keyboard02.jpg )
![Printed03](/Images/Keyboard03.jpg )
![Printed04](/Images/Keyboard04.jpg )

### Labels
The labels were drawn in Inkscape and can be printed on any color printer on plain office paper. File in SVG format is in [Labels](./Labels) directory.
![Stitky](/Images/Stitky.png )




