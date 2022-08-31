## Adafruit MAX17048 LiPoly / LiIon Fuel Gauge and Battery Monitor PCB

<a href="http://www.adafruit.com/products/5580"><img src="assets/5580.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MAX17048 LiPoly / LiIon Fuel Gauge and Battery Monitor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5580

### Description

Low cost Lithium Polymer batteries have revolutionized electronics - they're thin, they're light, they can be regulated down to 3.3V and they're easy to charge. On your phone, there's a little image of a battery cell that tells you the percentage of charge - so you know when you absolutely need to plug it in and when you can stay untethered.

The Adafruit MAX17048 LiPoly / LiIon Fuel Gauge and Battery Monitor does the same thing. Connect it to your Lipoly or LiIon battery and it will let you know the voltage of the cell, it does the annoying math of decoding the non-linear voltage to get you a valid percentage as well!

Since this nice chip is I2C, it works with any and all microcontroller or microcomputer boards, from the Arduino UNO up to the Raspberry Pi. And you don't have to worry about logic level, as the gauge runs with 3.3V or 5.0V power and logic equally fine.

To use, connect a 1S 3.7-4.2V Lithium Ion or Polymer battery to one of the JST 2 PH ports (either one). Then use the included JST PH jumper cable to connect to your boost converter, Feather, whatever! Use the I2C interface and our Arduino or CircuitPython/Python library code to read the voltage and percentage whenever you like. There are various alerts, low power modes that can be customized as desired.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the MAX17048 or to chain it with a wide range of other sensors and accessories using a compatible cable. QT Cable is not included, but we have a variety in the shop

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
