# ESP32-DCload
An ESP32-based WiFi controlled DC load

These files relate to a project published in Silicon Chip magazine in October 2022.  https://www.siliconchip.com.au/ 

Key features:

•	150V and 30A maximum values within a 300W power envelope.

•	Constant voltage (CV) current (CC), power (CP) and resistance (CR)modes

•	Short-circuit, battery and solar cell testing

•	Step test modes (square, ramp and triangle) with variable rise/fall times

•	Data logging

•	Touchscreen control panel 

•	Power off settings memory

•	Remote control via WiFi browser interface

•	SCPI programmable over WiFi and isolated USB

•	Over-voltage, over-current and reverse voltage protection

•	Definition files for the open source SCPI TestController instrument control application (https://lygte-info.dk/project/TestControllerIntro%20UK.html). 

Only compiled code is provided for a 3.5" TFT (ILI9488 controllers) because the number of libraries and complexity of code would make it difficult for others to get a clean compile.

The Laser_Templates folder has SVG files for the front panel of the load. 

The front panel was cut from 2mm acrylic, and the support back panel from 3mm acrylic.

The laser templates are designed for a 270mm x 210mm x 140mm blue metal enclosureavailable from eBay, Banggood and AliExpress. The templates have been tested with LightBurn, but should work with other laser cutter software.

The front panel was made with clear acrylic, coated on the BACK with black spray paint. Wood filler, in a contrasting colour, was squeegeed into the etched labels and then polished off with very fine DRY sandpaper (600 grit). A final coat of clear spray was then appled to seal the wood filler and restore a gloss finish to the acrylic.


