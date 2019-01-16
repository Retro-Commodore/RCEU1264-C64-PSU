# C64-PSU
A C64/C128/Vic20 PSU
This is a full replacement PSU with modern electronics that won't kill your computer when it gets bad.. the original PSU's short input to output, when they break, feeding approx 10v.
While it is possible to use wall warts, this design is created to be easy to diy, somewhat pretty and closer to the old designs with off the shelf items.

The PSU can be used for the C64 even with i.e. 1541 Ultimate and Vic20, and it's powerful enough to feed the C128 and/or 17xx REU.

All parts can be bought at [tme.eu](https://www.tme.eu/), and the pcb has been designed with parts from there.
A few parts like the DIN connector and fuse socket can be aqcuired from ebay where they're much cheaper.

*If you are a reseller, and use my designs, though the projects are open source, I'd like to ask you to donate a small amount of money, to cancer research for each sold device.*

The Mean Well IRM-20-5 is Short circuit / Overload / Over voltage protected (pdf's from Mean Well are in the documentation folder).

**The trafo is a 230v trafo, so countries that use 115v will need a different trafo.**

If you want to add an on/off switch, the easiest might be a switch on the 230v cable, or a round one, the round one is easiest to make holes to -by drilling-, rather than cutting a square one. But that is entirely up to you :-) .

The gerber files which is the zip file found in [hardware/eagle](https://github.com/Retro-Commodore/C64-PSU/tree/master/Hardware/Eagle Gerber) can be uploaded as is to PCB manufacturing companies like [JLCPCB](http://jlcpcb.com).

The PCB is created with Eagle which has a limiting size of 100x100mm (or is it 100x80mm?). And the PCB is within this size.
The newest version of KiCAD should be able to import the eagle files, in case you prefer this. 

**TODO**
* Add possibility to use PTC (one has to be sourced first), if you read this and know of one already please don't hesitate to add a ticket with the info. You'll providing the community a service :-)
* Add LED. 



![PSU](https://github.com/Retro-Commodore/C64-PSU/blob/master/Pictures/Closed%20PSU.jpg)
