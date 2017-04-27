# Arduino Pro Mini LoRa Node

## Arduino code for low cost, low power LoRa nodes using SX1272, SX1276 tranceivers (and HopeRF RFM9xx modules which use that chip).

Features :
- Uses LoRaWan protocol to communicate with gateways. 
- Based on <a href="https://github.com/rocketscream/Low-Power">Low power Arduino library</a> and <a href="https://github.com/matthijskooijman/arduino-lmic">LoRaMAC-in-C (LMIC) </a> library.
- Customised to run the free band 865-867 MHz in india excluding the primary 868Mhz band.
- This fails with RN2483 modules as the frequency cannot be altered.
- Payload can be modified for the corresponding sensor by altering the struct variables and changing the corversion mechanism in the loop.

`The above code hasn't been tested yet and is unverified. The developer assumes no liability for any problems resulting from the use of the given  code. Please use at your own risk.`
`Currently, the device on the node side is switched based on the acknowledgrmrnt from the gateway. The data reception is incomplete for LoRa and this problem has not yet been solved.`

### Files :
- basic.ino : Arduino sketch to transmit sensor values to the gateway using LoRaWan protocol.
