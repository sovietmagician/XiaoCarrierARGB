# XiaoCarrierARGB
![Board preview](img/board.png)
Adressable RGB carrier board for Seeed Xiao Esp32 modules, deisgned for c6 or s3 variants. Input voltage designed to be 12-24V and has an back current protection mechanism to allow the Xiao to be connected to a pc while the board is powered from elsewhere. 
- NOTE the 5v level shifters needed for the RGB data signalling are only powered from the 12-24v input and only connecting the xiao to power will not allow for RGB strip control. 
---
## Features

- 3 Dedicated 5V levelshifted outputs for LED strip data lines
- 8 GPIO breakouts capable of all features the selected Xiao is capable of including
  - SPI
  - I2C
  - Analog inputs
  - UART
- optional pull up/down resistors for GPIO breakouts can be pulled to:
  - 5V
  - 3.3V
  - GND
- 1.5 Amps of 5V output 
- 1 Amp of 3.3V output

---

### USER INFO
[Interactive Bill of Materials](https://sovietmagician.github.io/XiaoCarrierARGB/bom/ibom.html "IBOM")
