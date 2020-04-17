# DISCIPLINE / 55%

![fiftyfivepercent](./images/PCB_Eagle.png)

***flashing guides are for the DISCIPLINE specifically, not the 55% version, but should work the same***

A precompiled hex file is in the "55percent" folder

[QMK Toolbox Flashing Guide (Recommended)](https://static1.squarespace.com/static/5c533d33348cd92b886e544d/t/5d90521b1d22d176452c44a5/1569739293092/DISCIPLINE+FLASHING+GUIDE.pdf)

[Command Line Flashing Guide (Advanced)](https://static1.squarespace.com/static/5c533d33348cd92b886e544d/t/5d7f3c43fef3e33f1b03bfe2/1568619588036/DISCIPLINE+FLASHING+GUIDE+-+COMMAND+LINE.pdf)

[Bootloader](./bootloader)


***Build guide is similar to DISCIPLINE, with a few notable alterations:***

1: The line on the PCB indicates where the lever mount side of the microswitch should face. Putting them in reversed will leave teh common terminal disconnected. Be sure to have them fully seated against the board when soldering.

2: As the fuse was omitted from the design, take extra care to not cause shorts between VCC and GND - in particular, the electrolytic capacitor and zener diode orientation, and to not bridge connections on the USB-C port. The baseplate will protect the bottom from shorts on the desk when in use.

3: When installing the baseplate and cover, use the 10mm M2 screws from the underside of the baseplate, through a spacer, through the pcb, and into the female end of the standoff. The male end of the standoff then only needs to pass though the cover.
