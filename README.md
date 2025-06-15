# Read before using!!
This readme file will hopefully clear up some things.

## What exactly is a .xsv file?
It's a minimalistic vector image format, with support for compression and 512 colours.

## How does it work?
It works by drawing lines, and picking the pen up when it starts a new stroke.

## More detail:
### Handling strokes:
Brush strokes are seperated by 2 things; a colour value from RGB 0-7 (1xxx) and a flag for seperation (S). For example, if you start a stroke at x0,y50 with the RGB colour value of 652, it becomes (1652;S0,50)
### Compression:
Similiar to JSONCrush, but optimized for numbers. Each character from the list of 100 ASCII characters represents one number pair, from 00-99.

## How to use:
Download the .html file, and run it in your browser.
## How to make modifications:
Download the .sb3 file, and open it in [Turbowarp](https://turbowarp.org).
