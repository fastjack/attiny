ATtiny
=======

This repo contains a set of "cores" which adds support for ATtiny family of microcontroller to the Arduino IDE. This branch only supports the 1.5.x version of the Arduino IDE.

The following micro controllers are supported

- ATtiny 45 (8 pin)
- ATtiny 85 (8 pin)
- ATtiny 44 (16 pin)
- ATtiny 84 (16 pin)

Installation and usage
----------------------

Clone this repository into the hardware directory (create it if it doesn't exist) of your Arduino IDE sketch folder and then restart the IDE. Make sure to switch to the `ide-1.5.x` branch after checking out.

To program an ATtiny without a dedicated programmer see [this guide](http://hlt.media.mit.edu/?p=1706) that explains how to use an Arduino Uno or Duemilanove as a programmer. Note that guide was written for version 1.0.x of the Arduino IDE. Some adjustments might be needed.

See also [this video](http://www.youtube.com/watch?v=30rPt802n1k) from Make magazine that shows how to program and use an ATtiny microcontroller with the Arduino IDE.

Known issues
------------

Currently the Arduino IDE doesn't always update the selected processor or clock speed in the footer of the editor window. If in doubt check the selected processor and clock speed in the menu.
