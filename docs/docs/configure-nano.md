<IMG SRC="../img/arduino-nano-rp2040-connect.png" align="right" width="300">

This is documentation for configuring and using an [Arduino Nano rp2040 connect](https://store-usa.arduino.cc/products/arduino-nano-rp2040-connect?selectedStore=us) with CircuityPython.

We will be programming the Arduino using the [CircuitPython](https://circuitpython.org/) language which is a derivative of [Python](https://www.python.org/)

## Install CircuitPython on the Nano

Download circuitpython [here](https://circuitpython.org/board/arduino_nano_rp2040_connect/).

From that link, you will be saving a file to your computer named `adafruit_circuitpython_etc.uf2`.

Continue by following the instructions [here](https://learn.adafruit.com/circuitpython-on-the-arduino-nano-rp2040-connect/install-circuitpython).

1) Connect the Nano to your computer with a USB cable.

2) To enter the bootloader, double-tap the reset button (highlighted in red). After that, the RPI-RP2 drive will appear as a new disk drive. 

3) Drag the `adafruit_circuitpython_etc.uf2` file to RPI-RP2.

The RPI-RP2 drive will disappear and a new disk drive called 'CIRCUITPY' will appear.

That's it, you're done! :)

**Troubleshooting**

 - If the drive does not appear, release the reset button, and then repeat the process above.

 - A lot of people end up using charge-only USB cables and it is very frustrating! So make sure you have a USB cable you know is good for data sync.

