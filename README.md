# ali-zmk
VERY IMPORTANT PLEASE READ ALL

Parts Needed
- 42 MX style switches
- 42 1N4148 diodes
- 42 1u keycaps
- Insulated stranded/solid core copper wire
- 1 nice!nano v2 or suitable clone
- 1 3.7v lithium ion battery
- M2 10mm standoffs (important note about standoffs)
- M2 8mm screws

Standoffs - Dependning on which standoffs you buy, they may or may not fit in the holes on the case. The holes on the case are 4mm in diameter, but I have been M2 standoffs with outer diameters anywhere from 2.9-5mm. This was the case with me, but I got around it but by screwing the actual standoff to the plate alone, dabbing hot glue in the correct locations for the standoffs in the case, then pressing standoffs attacted to the plate into the glue. You can then unscrew the plate, and the standoffs will be the correct position. It is very important to note that hot glue dries very fast, so if you do this you need to move fast. The hot glue allows for you to remove it if your placement isn't how you like it. You can reinforce with super glue after you get the placement right if you wish, but the hot glue is pretty strong on its own. This is obviously not ideal, but the position of the screws/screwless design require this to have skinny standoffs to not interfere with handwiring. I would like to improve this in a Revision 2. 

Wiring Guide

IMPORTANT - This board was wired row2col instead of the more common col2row. This means when wiring, you need to make sure the strip of the diode is on the same side as the row. If you wire this board col2row, the keymap will be mirrored. This is shown in the picture below.

FOLLOWING THIS GUIDE ENSURES DEFAULT FIRMWARE FUNCTIONALITY, IF YOU DO NOT USE THE SAME PINS YOU WILL NEED TO CHANGE THE PINS IN THE OVERLAY FILE AND RECOMPILE.
You should know how to build and recompile firmware if you ever want to change your keymap anyways, but if you don't know how to I would recommend reading the ZMK documentation or this youtube video https://www.youtube.com/watch?v=O_urj-rF3bQ by Joe Scotto. (You should ideally do both)
