# shiny-hunt
Automated pokemon breeding in Sword and Shield for shiny hunting.


### Getting Started With Teensy
* Purchase a [Teensy](https://www.pjrc.com/store/teensypp.html) ++ V2.0 USB development board from PJRC. At the time of this repository readme write up it was $24.00. PJRC shipped my order within 24 hours and it took about a week to arrive.

* The Teensy board uses micro USB to USB 2.0. If you want to plug the Teensy directly into the Switch you will need a USB 2.0 to Type-C. You could also just plug the 2.0 directly into the Nintendo Switch Dock, allowing for the Switch to stay charged while the script runs for potentially an unlimited amount of time.

### Teensy Download/Install
* Download/install the [Teensy Loader application](https://www.pjrc.com/teensy/loader.html)
* To compile this project you will need the AVR GCC Compiler and Tools. On Mac I used homebrew:
  * `brew tap osx-cross/avr`
  * `brew install avr-gcc`.

### LUFA
* I included LUFA in this project which is required for the Teensy board to emulate the HORI Pokken Tournament Pro Pad for Wii U which the switch recognizes as a pro controller.
* If LUFA is not working after cloning this repo, You can download the LUFA library in a zipped folder at the bottom of [this page](http://www.fourwalledcubicle.com/LUFA.php).
### Thanks
* Special thanks to github user [bertrandom](https://github.com/bertrandom/snowball-thrower) who made a similar script for legend of zelda breathe of the wild. I learned how to approach this problem through his well written write up on [medium](https://medium.com/@bertrandom/automating-zelda-3b37127e24c8).
