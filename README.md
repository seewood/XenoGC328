# XenoGC is a modchip for the Nintendo Gamecube 

The idea is a micro sitting on the communication bus between the cpu and the dvd driver board injecting code to patch the dvd controller to make it able to read unsigned code.

The original sofware is been released as opensource here:

http://www.gc-forever.com/forums/viewtopic.php?t=439

This version run on an ATmega8L, not a lot of ports are been made, mostly because you don't really need them, the Atmega8L is cheap and still in production. Someone made a Raspberry Pi port of it.

I'm looking forward to implement some spare cool features.

# Atmega328:
* For now it is only tested on a Arduino Pro Mini with Atmega328 / 5V@16MHZ
* it should work on every Atmega328, but its no tested yet!
* Chip needs to be flashed via ISP!

# Soldering Diagram:
**You only need one Color wiring up to the Mainboard. The other Points are alternativ solder Points**

![Diagramm_final_Xeno328](https://user-images.githubusercontent.com/33197691/75441025-2ec95b00-595d-11ea-850d-fb022cc918fa.png)

## Credits:

* Thanks to emukidid, megalomaniac, meneerbeer and everyone who worked on the offical XenoGC Fork
* Thanks to AndreaCampanella for the initial Port to XenoGC328
* Thanks to rama for finishing the Port and making it working on the Atmega328. He is like a mentor to me on the project
