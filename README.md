# Arduino-Matrix-Clock v1.3

Simple Arduino Clock with LED matrix display 32 x 8 pix. In this sketch is LedControl library (https://github.com/wayoda/LedControl) used.

Version 1.3 can show temperature and it is posible to turn font UpsideDown.


Menu:
- H: Hours
- M: Minutes

- y: year
- m: month
- d: day

- /: 12/24h time format (00 = 12h time format, 01 = 24h time format)
- f: Font (show nr of font in select font style)
- :: Dot style (0 - hide, 1 - show, 2 - blinking)
- b: Backlight intensity
- D: Show date (what second is date shown; 00 = newer, 60 = always)
- t: Show temperature (what second is temperature shown 00 = newer, 60 = always)
- R: Font turning 1 (turn each character)
- r: Font turning 2 (turn all diplay)
- U: Turn font UpsideDown (new)
- Strt: Reset second after press the button and show actual time

You need:
- Arduino Nano
- DS3231 module
- 4x LED matrix with MAX7219 driver (used LedControl library)
- 2x button


For use external power supply (no USB) you need:
- 1N4148 diode
- 5V power supply

![alt Arduino Matrix Clock](https://www.mylms.cz/obrazky/elektronika/arduino-matrix-clock-1.jpg)

![alt Arduino Matrix Clock - Schematics](https://www.mylms.cz/obrazky/elektronika/arduino-matrix-clock-9.png)



More info in Czech language: https://www.mylms.cz/text-arduino-hodiny-s-maticovym-displejem/ You can use forum there.

See video: https://youtu.be/HDweqN9cDNA
