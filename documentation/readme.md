# RGB-LED Raspberry Pi Hat  (Version 5)
Raspberry Pi shield that has support for both SPI-driven DotStar LEDs and RGB Matrix. Barrel power supply, backflow current protection, and 5V signals to LEDs.

Contains power protection circuit that prevents under- or over-voltage to the Pi and LED strips, includes diode to prevent back powering the Pi from 5V LED connectors. Capacitors to smooth voltage and handle inrush current spikes.

Provides 2 sets of 5V, Clock, Signal, and Ground pins to drive DotStar LEDs. Clock and signal are connected to SPI0 and SPI1 registers for driving DotStar LEDs from hardware without software SPI. All signal pins for LED and RGB flow through ‎74AHCT245 chips to convert 3.3V to 5V signal voltage for better compatibility.

This is based loosely on the [Adafruit RGB Matrix Bonnet](https://learn.adafruit.com/adafruit-rgb-matrix-bonnet-for-raspberry-pi/), but has been enhanced to handle [DotStar](https://www.adafruit.com/category/885) and [NeoPixels](https://www.adafruit.com/category/168). The ADC was also added to support a little more project possibilities as RPi does not have analog ports.
## Features
 - Under- and Over-voltage protection
 - Negative voltage protection
 - Powers Raspberry Pi from one source
 - RGB Matrix Support
 - DotStart and LED support through SPI ports
 - 4 Channel Analog-to-Digital converter
 - Pi Zero Size (but fits all Pi layouts)

## Schematic
<a href="https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/schematic.pdf"><img src='https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/schematic.PNG' width="200"></img></a>
## Circuit Board
<a href="https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/fullboard.png"><img src='https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/fullboard.png' width="200"></img></a> <a href="https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/frontboard.png"><img src='https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/frontboard.png' width="200"></img></a> <a href="https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/backboard.PNG"><img src='https://raw.githubusercontent.com/jrowe88/RPi-LED-RGBMatrix-Hat/master/documentation/backboard.PNG' width="200"></img></a>
## OSH Park Board Project
<a href="https://oshpark.com/shared_projects/K0GEaa4e"><img src='https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/d76e7188bc10d15a657f97c2744a44c5.png' width="200"></img></a> &nbsp;<a href="https://oshpark.com/shared_projects/K0GEaa4e"><img src='https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/5962378cf38d954da379bb5472164afd.png' width="200"></img></a>

## DigiKey BOM
[Link to cart in DigiKey](https://www.digikey.com/short/p8nr4q).  Larger multiples might yield small discounts.  OshPark allows boards to be built in multiples of 3.

