vixen_sequences
===============

Sequences from the "Vixen 3" program folder tracked by the software version control.

### Hardware
I'm using an Arduino Uno R3 connected to a PC (Windows 7) via USB. I'm interfacing Vixen 3.1u2 (build #66) via the
Generic Serial controller option. The Arduino sketch simply waits until it's recieved 16 bytes of serial data from 
Vixen and writes that info to the 16 pins (turning each one on or off). Those pins are connected to two Sainsmart
8 channel solid-state relays. Each relay is connected to 110V and an indoor extension-cord. Everything is housed
inside of a metal service box (there's a face-plate that is normally screwed into place for safety but I removed it
so you can see the fun stuff).
My Arduino sketch can be found [here](https://github.com/kbarre123/vixen_setup/tree/master/arduino_sketches/vixen_basic).

Here's the finished product:

![My image](https://github.com/kbarre123/kbarre123.github.io/blob/master/images/arduino_vixen_1.JPG)
![My image](https://github.com/kbarre123/kbarre123.github.io/blob/master/images/arduino_vixen_2.JPG)
![My image](https://github.com/kbarre123/kbarre123.github.io/blob/master/images/arduino_vixen_3.JPG)

### Music
Here's the md5sums for the songs used in each of my sequences in case you want to find the exact one.

* carol_of_bells.tim
  * asd;ljkfasd;ljf
