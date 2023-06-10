# LiquidCrystal
MicroPython library to control LiquidCrystal displays (LCDs) based on the Hitachi HD44780 (or a compatible) chipset.  
Credits go to the [Arduino LiquidCrystal library](https://github.com/arduino-libraries/LiquidCrystal).

## Compatibility
This library is compatible with RP2040 boards running MicroPython.

## Releases
0.1 (current)

## Usage
To use this library:
* Download the LiquidCrystal.py file from this repo;
* Upload LiquidCrystal.py to your board;
* In your main.py code add the class using `from LiquidCrystal import LiquidCrystal`.

## Functions
All functions work similar to how they would in the original Arduino library. Please see the reference documentation [here](https://www.arduino.cc/reference/en/libraries/liquidcrystal/).

LiquidCrystal()  
begin()  
clear()  
home()  
setCursor()  
write()  
print()  
cursor()  
noCursor()  
blink()  
noBlink()  
display()  
noDisplay()  
scrollDisplayLeft()  
scrollDisplayRight()  
autoscroll()  
noAutoscroll()  
leftToRight()  
rightToLeft()  
createChar()  