# USB LiIon/LiPoly charger

<a href="http://www.adafruit.com/products/259"><img src="assets/board.jpg?raw=true" width="500px"></a>

This is a Lithium Ion and Lithium Polymer battery charger based on the [MCP73833](http://www.microchip.com/wwwproducts/Devices.aspx?dDocName=en027785). It uses a USB mini-B for connection to any computer or 'USB wall adapter'. Charging is performed in three stages: first a preconditioning charge, then a constant-current fast charge and finally a constant-voltage trickle charge to keep the battery topped-up. The fast-charge current is 500mA by default, but is easily adjustable from 100mA up to 1000mA by soldering a through-hole resistor on-board.

This board is great for DIY projects because it has 3 indicator LEDs - one for power, one for charging status and a third that indicates when charging is complete. Keep the battery connected to the charger and pass power through the additional JST connector using the included cable!

For use with Adafruit Lipoly batteries only! Other batteries may have different voltage, chemistry, polarity or pinout.

- Comes assembled and tested, includes a JST cable!
- 5V input via mini-B USB connector
- For charging single Lithium Ion/Lithium Polymer 3.7/4.2v batteries (not for older 3.6/4.1v cells)
- 500mA charge current, adjustable from 100mA to 1000mA by soldering in a resistor
- Separate JST connectors for battery and load system so batteries don't have to be removed for charging
- Chip supports a [10K NTC thermistor](http://www.adafruit.com/products/372) which we have stuffed as a plain 10K. For people who require temperature monitors (using high charge rates), remove the 10K and solder in the thermistor in its place
- 0.1" (2.54mm) breakouts for the battery, DC, and status LEDs
- Free 2-pin JST cable included!
- [Batteries](http://www.adafruit.com/products/258) and [USB cable](http://www.adafruit.com/products/260) not included.
