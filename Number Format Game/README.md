# ACM Number Format Game

## Author
> Nicholas Cieplensky

## Description 
I showed this game off at a tabling event for the club, and it got a little bit of attention I'd say. Basically, it asks you to convert a number into either binary, hexadecimal, or decimal format, and keeps a highscore in the EEPROM which I think is pretty cool.

## Parts Used
- 1x Arduino Uno R3
- Wires and 220 ohm resistors
- 16*2 Liquid Crystal Display
- 1x potentiometer
- 1x Numpad (with A B C and D)

## Bugs and Limitations
- The high score board writes to the EEPROM really weirdly
- Currently I can only test it with hex 00 through DD, since I'm missing E and F on the board
