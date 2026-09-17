# XiaoCarrierARGB
Adressable RGB carrier board for Seeed Xiao Esp32 modules, deisgned for c6 or s3 variants. Input voltage designed to be 12-24V and has an back current protection mechanism to allow the Xiao to be connected to a pc while the board is powered from elsewhere. NOTE the 5v level shifters needed for the RGB data signalling are only powered from the 12-24v input and only connecting the xiao to power will not allow for RGB strip control. 
---
## Features
The board breaks out all available GPIO for external sensors or any other digital/analog circuitry one might expect with 3 GPIO lines dedicated to RGB signalling. The GPIO breakout has optional pull up/down resistors with jumpers allowing the lines to be pulled to either ground 3.3V or 5V. The RGB data lines have optional series resistor footprints to mitigate ringing in the event the wire from the board to the first LED driver IC is exceptionally long, if not needed a 0 ohm ressistor can be used or a solder bridge.
