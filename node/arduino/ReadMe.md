# Arduino pro mini LoRa Node

## Arduino code for low cost, low power LoRa nodes using SX1272, SX1276 tranceivers (and HopeRF RFM9xx modules which use that chip).

Features :
- Uses LoRaWan protocol to communicate with gateways. 
- Based on <a href="https://github.com/rocketscream/Low-Power">Low power Arduino library</a> and <a href="https://github.com/matthijskooijman/arduino-lmic">LoRaMAC-in-C (LMIC) </a> library.
- Customised to run the free band 865-867 MHz in india excluding the primary 868Mhz band.
- This fails with RN2483 modules as the frequency cannot be altered.

`The above code hasn't been tested yet and is unverified. The developer assumes no liability for any problems resulting from the use of the given  code. Please use at your own risk.`