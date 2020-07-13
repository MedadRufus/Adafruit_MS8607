# Adafruit MS8607 Driver (Pressure, Humidity, and Temperature Sensor) [![Build Status](https://github.com/adafruit/Adafruit_MS8607/workflows/Arduino%20Library%20CI/badge.svg)](https://github.com/adafruit/Adafruit_MS8607/actions)[![Documentation](https://github.com/adafruit/ci-arduino/blob/master/assets/doxygen_badge.svg)](http://adafruit.github.io/Adafruit_MS8607/html/index.html)

This driver is for the [Adafruit MS8607 Breakout](http://www.adafruit.com/products/XXXX)

<a href="https://www.adafruit.com/product/XXXX"><img src="assets/board.jpg" width="500"/></a>

## About the BMP280 ##


## About this Driver ##

Adafruit invests time and resources providing this open source code.  Please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Bryan Siepert for Adafruit Industries.

<!-- START COMPATIBILITY TABLE -->

## Compatibility

MCU                | Tested Works | Doesn't Work | Not Tested  | Notes
------------------ | :----------: | :----------: | :---------: | -----
Atmega328 @ 16MHz  |              |             |            |
Atmega328 @ 12MHz  |              |             |            |
Atmega32u4 @ 16MHz |              |             |            | Use SDA/SCL on pins D2 &amp; D3
Atmega32u4 @ 8MHz  |              |             |            | Use SDA/SCL on pins D2 &amp; D3
ESP8266            |              |             |            | SDA/SCL default to pins 4 &amp; 5 but any two pins can be assigned as SDA/SCL using Wire.begin(SDA,SCL)
Atmega2560 @ 16MHz |              |             |            | Use SDA/SCL on pins 20 &amp; 21
ATSAM3X8E          |              |             |            | Use SDA/SCL on pins 20 &amp; 21
ATSAM21D           |              |             |            |
ATtiny85 @ 16MHz   |             |              |            |
ATtiny85 @ 8MHz    |             |              |            |
Intel Curie @ 32MHz |             |             |             |
STM32F2            |             |             |             |

  * ATmega328 @ 16MHz : Arduino UNO, Adafruit Pro Trinket 5V, Adafruit Metro 328, Adafruit Metro Mini
  * ATmega328 @ 12MHz : Adafruit Pro Trinket 3V
  * ATmega32u4 @ 16MHz : Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
  * ATmega32u4 @ 8MHz : Adafruit Flora, Bluefruit Micro
  * ESP8266 : Adafruit Huzzah
  * ATmega2560 @ 16MHz : Arduino Mega
  * ATSAM3X8E : Arduino Due
  * ATSAM21D : Arduino Zero, M0 Pro
  * ATtiny85 @ 16MHz : Adafruit Trinket 5V
  * ATtiny85 @ 8MHz : Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->
