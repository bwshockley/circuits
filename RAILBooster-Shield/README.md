#Railbooster Shield#

This design is based off of [RAILStars Railbooster](https://github.com/Railstars/RAILbooster).  It has been modified to fit onto an Arduino shield with a slightly different error check and control.

The shield should be good for DCC train control up to 12V and ~1.5Amps as is without heatsink.  Above that the LMD18200 will require some heatsink.  The voltage regulator is good as-is up to around 2Amps based off 15V input and 13V output.  The larger the deltaV between input and output voltage, the more likely a heatsink for the voltage regular will be required.  Please see the documentation on the voltage regulator.

The shield can provide voltage to the Arduino Uno R3 via the Vin pin of the Arduino.  It is fed off the shield voltage regulator.  In turn, the Arduino provides the 5V voltage for the shield's ATTINY, ICs, etc.

Adjust the output voltage of the voltage regulator with the adjustable resistor.

ATTINY44/84 can be programed via the Arudino UNO R3.

Design is provided as-is.  I cannot guarantee this will work and or not destroy your DCC trians.  Test the setup prior to powering the track.
