# PicoW I2C scanner

A simple I2C scanner which finds all I2C device addresses connected to a Raspberry Pi PicoW. There are lots of examples for the pico, however the picow default SDA and SCL ports are different, 8 and 9 respecively.

This project uses PlatformIO as the template.

Please note the platform.ini file as it uses the Arduino libraries for simplicity, specifically Wire.h, which are maintained at [github.com/maxgerhardt/platform-raspberrypi](https://github.com/maxgerhardt/platform-raspberrypi)

Enjoy!
