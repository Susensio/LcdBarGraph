LcdBarGraph
===========

Forked in 2015 and modified for personal project

## Changes:

* Added public function `createAllChar()` allows using 4 aditional LCD custom characters.
This method restores the LcdBarGraph custom characters when needed.
* Added `forceRedraw()` that will force redraw bar graph even when value hasn't change.
This redraw will happen when `drawValue(value,maxvalue)` is called.


## Credits

Original library by [**prampec**](https://github.com/prampec)


## Original readme

>An Arduino library to draw bar graph on a Liquid Chrystal display.
>
>See page http://playground.arduino.cc/Code/LcdBarGraph for details.
