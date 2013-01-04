tinyPixel
=========

tinyPixel is a compact, open-source, I2C-ready, BlinkM-compatible high-power RGB LED driver that can be individually pre-programmed or daisy-chainned and controlled by an Arduino or other microcontroller platform (like my Lumiboard!). tinyPixel uses the open-source cyz_rgb firmware to emulate the behavior of BlinkM modules, so it can be used with BlinkM software.

BlinkM modules are great, but quite expensive, especially if you want to use them in an installation (as they were intended). DIY alternatives, such as the Ghetto Pixel, are great but can be a burden to assemble at scale and are limited in the types of LEDs they use. I wanted something that was cheap, small and would be easy to assemble in a hurry.

Board features
==============
* Standard BlinkM-style interface (4-pin 0.1" male header for +, -, c and d lines).
* On-board 2W power resistors, so that 3W and 5W RGB LEDs can be driven.
* On-board ATTiny85 with cyz_rgb preloaded.
* On-board ULN2003 Darlington transistor array to sink large amounts of current for the RGB LED.
* 4-pin 0.1" male header to decouple RGB LED from main board (R,G, B and + lines).
* On-board 10uF capacitor to smooth the power out on each board.
* 4-pin Molex / ATX power connector to supply power.

More information
================
Author's website: http://jason-webb.info
Project wiki: http://jason-webb.info/wiki/index.php?title=TinyPixel