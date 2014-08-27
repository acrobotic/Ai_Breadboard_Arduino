Create your own Breadboard Arduino
==================================

Using ATMega 328, used on the Arduino Uno, you can build your own Arduino Uno.

* Remove ATMega microcontroller from existing Arduino Uno board.
* Connect Rx, Tx pins from Uno to pins 2, 3 on ATMega 328.
* Tools -> Board -> Arduino Uno
* Tools -> Burn Bootloader

Your chip is now an Arduino Uno compatible and ready for sketches!

TODO
====

Schematic
* Change oscillator capacitors to 22pF
