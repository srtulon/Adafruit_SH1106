I slightly modified [wonho-maker](https://github.com/wonho-maker)'s library to also work on a Wemos D1 clone. I only ested this on a single board with a single sketch.

Adafruit_SH1106
===============

Adafruit graphic library for SH1106 driver lcds.

some small oled lcd use SH1106 driver.

I change the adafruit SSD1306 to SH1106 

SH1106 driver similar to SSD1306. thus, just change the display() method. 
 
However, SH1106 driver don't provide several functions such as scroll commands.


 Adafruit-GFX-Library
 https://github.com/adafruit/Adafruit-GFX-Library
