<h1>Seeed SSD1306 OLED displays</h1>
<p>OLEDs we have in hackSpace are small displays; they are also known as monochrome displays, they are only about 1” diagonal, but very readable due to the high contrast. This display is made of 128x64 individual white OLED pixels, each one is turned on or off by the micro-controller. Because the display makes its own light, no backlight is required, allowing better energy saving. Briefly saying an OLED display is just better and modified version of and LCD display.</p>

<p>The OLED screen communicates via I2C protocol. You need two pins on the arduino UNO, two for data (SDA SCL), two for power(VCC GND). On an arduino UNO, the SDA port is A4 and the SCL port is A5.</p>
 
<p>Inthe arduino IDE go to sketch -> include Libraries -> Manage libraries. search for SSD1306 OLED and choose to install the library.</p>

<p>The libraries for OLED displays can be found here...</p>

<link>https://github.com/adafruit/Adafruit_SSD1306</link>

<p>A list of all the available methods for the oled object can be found here...</p>

<link>https://www.instructables.com/Arduino-and-the-SSD1306-OLED-I2C-128x64-Display/</link>

<p>The highest frame rate on an arduino UNO on full performance mode is around 7 fps.</p>
