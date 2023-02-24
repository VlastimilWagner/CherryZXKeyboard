# CherryZXKeyboard
The goal of the project was to create a keyboard consisting of Cherry MX keys with two-layer keycaps, into which printed labels will be inserted. At the same time, I wanted the keyboard to have a better layout of the keys (for example, cursor keys), to be easy to manufacture and install (ideally without SMD), from available components, cheap and at the same time to write well on it.

I wasn't limited to a standard diaphragm format as the goal was to build a ZX MAX 128 clone and put it in my own cabinet.

Since the ZX Spectrum+ membrane is double-layered, the 48p-KDLX solution was suitable, i.e. electronically secured switching of two contacts at the same time, since the MX buttons have only one contact.

![3D](/Images/CherryZXKeyboard3D.png )

I designed the first version of the keyboard in such a way that 2 MX buttons were used simultaneously for the longer keys and even 3 for the spacebar. It worked well outside of the spacebar, but in the latest version that is stored here I already modified it to use 1 button for the center and auxiliary buttons synchronization mechanisms. Fortunately, even the original version with one sync mechanism for the spacebar is normally usable (it's in the photos) and I didn't have to make a new PCB.

## What is needed to make

### PCB
In the [Gerber](/Gerber) directory there are materials for production. For example, on [https://jlcpcb.com](https://jlcpcb.com), just pack this directory in ZIP format, insert it into the order, and after payment, you have printed circuit boards within 2 weeks, even with the cheapest selected transport.

### Electronic Parts
These are common cheap parts from a local dealer - for example TME.

### Mechanical MX Switches (58 pcs)
You can use the original, but rather expensive Cherry MX, or, like me, a copy of the MX switches from AliExpress.
![MX](/Images/MX.png )

### Keycaps
Three types of keycaps are used:

#### - Standard buttons (53 pcs)
![KeyCap](/Images/KeyCap.jpg )

#### - Wide buttons (4 pcs)
![WideKeyCaps](/Images/WideKeyCaps.jpg )

#### - Space bar (1 pc)
![SpaceBar](/Images/SpaceBar.jpg )

### Mechanical stabilizers

#### - Wide buttons (4 pcs)
#### - Space bar (1 pc)
![Stabilisers](/Images/Stabilisers.jpg )


### 3D printed inserts
I divided the printing of the mat into 2 parts so that it would not be a problem to print it on a standard size 3D printer. The documents in STL format are in the [Stl](./Stl) directory.

### Labels
The labels were drawn in Inkscape and can be printed on any color printer on plain office paper. File in SVG format is in [Labels](./Labels) directory.
![Stitky](/Images/Stitky.png )




