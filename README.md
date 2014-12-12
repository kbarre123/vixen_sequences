vixen_sequences
===============

My sequences from the "Vixen 3" program folder as by the software's version control. Admitedly, they're quite
basic but I enjoy the 100% DIY factor as opposed to buying a fancy controller.

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
Here's the info and md5sums for the songs used in each of my sequences in case you want to find the exact one. I
had to rename my files because the original names had spaces in them and I'm anal like that. Luckily, I was able
to grab the following info from the meta-data of the files. Happy hunting!

* carol_of_bells.tim
  * Title: Carol Of The Bells
  * Artist: John Williams
  * Album: Home Alone
  * md5sum: ca59ac7ada3405cf72e856409568f30a  carol_of_the_bells.wav

* rocking_around_the_xmas_tree.tim
  * Title: Rockin' Around the Christmas Tree
  * Artist: Brenda Lee
  * Album: Now That's What I call Christmas/Disc 2 2013
  * md5sum: 0a91139b3f96c21f5050b56a35b618fc  rockin_around_the_xmas_tree.mp3
 
* wizards_in_winter.tim
  * Title: Wizards In Winter
  * Artist: Trans-Siberian Orchestra
  * Album: The Lost Christmas Eve
  * md5sum: 9fce10f01c1091a79e571b12f5b6a9e4  wizards_in_winter.mp3

### Parting Thoughts
If you decide to use one of my sequences, I just ask that you credit me where possible and let me know because I'd
think it was cool.

##Happy Holidays!!!
