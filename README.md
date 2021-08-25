## Adafruit SCD-4x CO2, Temperature and Humidity Sensor PCB

<a href="http://www.adafruit.com/products/5190"><img src="assets/5190.jpg?raw=true" width="500px"></a><br/>
<a href="http://www.adafruit.com/products/5187"><img src="assets/5187.jpg?raw=true" width="500px"></a><br/>
Click above to purchase one from the Adafruit shop!

PCB files for the Adafruit SCD-4x CO2, Temperature and Humidity Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5190

### Description

Take a deep breath in...now slowly breathe out. Mmm isn't it wonderful? All that air around us, which we bring into our lungs, extracts oxygen from and then breathes out carbon dioxide. CO2 is essential for life on this planet we call Earth - we and plants take turns using and emitting CO2 in an elegant symbiosis. But it's important to keep that CO2 balanced - you don't want too much around, not good for humans and not good for our planet.

The SCD-40 is a photoacoustic 'true' CO2 sensor that will tell you the CO2 PPM (parts-per-million) composition of ambient air. Unlike the SGP30, this sensor isn't approximating it from VOC gas concentration - it really is measuring the CO2 concentration! That means it's bigger and more expensive, but it is the real thing. Perfect for environmental sensing, scientific experiments, air quality and ventilation studies, and more.

Compared to the illustrious SCD-30, this sensor uses a different measurement technique, which allows it to be much smaller. The overall data quality should be very similar, however. Like the SCD-30, this sensor has data read over I2C, so it works very nicely with just about any microcontroller or microcomputer. There's both Arduino and Python/CircuitPython code so you can get started in a jiffy.

There are two variants of this sensor - the SCD-40 and SCD-41

* The SCD-40 is lower cost, and is perfect for indoor/outdoor air quality and CO2 measurements. It has a range of 400~2000 ppm with an accuracy of ±(50 ppm + 5% of reading)
* The SCD-41 is more expensive, and while it can definitely be used for air quality, it's wide range means its best used for industrial or scientific CO2 measurements where the ppm can get very high. It has a range of 400~5000 ppm with an accuracy of ±(40 ppm + 5% of reading)

Nice sensor, right? So we made it easy for you to get right into your next project. The sensor is soldered onto a custom-made PCB in the STEMMA QT form factor, making them easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the SCD-4x or to chain it with a wide range of other sensors and accessories using a compatible cable.

This sensor can run from 3.3 to 5V but it's more important for it to have a quiet power supply with low ripple, than any particular voltage. For that reason we've added a 3.3V regulator and level shifters: when connecting to a 5V microcontroller like an Arduino UNO the 5V supply is often shared with other electronic components that add noise. The onboard regulator will keep the voltage nice and quiet. For advanced hackers, they can cut/solder the back traces to change whether the regulator is enabled and what I2C logic level is desired.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
