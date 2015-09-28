#GPIO Expander - Arduino Shield#
16 Channel general purpose IO expander for Arduino Uno R3 boards. Provides higher current (500mA) and voltages (50V) per pin than Arduino. Voltage via Vin from Arduino or separate DCC jack - up to 50V and 500mA per pin.  This uses the i2c interface, which is shared, so does not utilize any of the dedicated I/O pins of the Arduino.  Each board is addressable via jumpers for up to 8 expanders on one Arduino plus possibly additional i2C devices depending on the addresses.

##BOM:##

1x MCP23017 - Microchip MCP23017-E/SP - [Mouser Part](http://www.mouser.com/ProductDetail/Microchip-Technology/MCP23017-E-SP/?qs=sGAEpiMZZMtLck3p7ZBovcWu3APnHHes)

2x ULN2803A - STMicroelectronics - [Mouser Part](http://www.mouser.com/ProductDetail/STMicroelectronics/ULN2803A/?qs=sGAEpiMZZMvAvBNgSS9LqpP7ived4CP2)

1x CUI Inc PJ-202A - [Sparkfun PRT-00119](https://www.sparkfun.com/products/119) (Optional - Only needed if you plan to NOT use Vin from Arduino Uno)

**Optional Shield Stacking Headers - Useful to stack shield with other shield - not that all pins are transferred up to next shield.**

1x - Shield Stacking Headers Kit - [Adafruit](http://www.adafruit.com/products/85)

**Optional male pins for jumpers for board - since the spacing is standard .1 inch (2.54mm) there are many options.**

2x 2x5 90deg Header - suggested 90 deg headers for outputs if stacking shields - [Mouser Part](http://www.mouser.com/Search/ProductDetail.aspx?R=71764-0110virtualkey53810000virtualkey538-71764-0110)

4x Jumpers - [Mouser Part](http://www.mouser.com/Search/ProductDetail.aspx?R=969102-0000-DAvirtualkey51750000virtualkey517-9691020000DA)

1x 1x12 Header - Break into 4x 1x3 for A0, A1, A2, Power Selectors [Mouser Part](http://www.mouser.com/ProductDetail/Molex/22-28-4123/?qs=%2fha2pyFadug1w615h5TWM67RUKMyx5wkJTOjySvbUwE%3d)

##Arduino Library##
Use the [Adafruit MCP23017 library](https://github.com/adafruit/Adafruit-MCP23017-Arduino-Library) for this i2c connector.
