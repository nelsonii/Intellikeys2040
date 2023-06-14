# Intellikeys2040
Intellikeys software for the Adafruit Feather RP2040 USB Host

If the board seems to be working but doesn't appear to be sending keys, check the CPU speed.


The CPU Speed must be either 120 or 240 Mhz. If you do a compile from source, select this under > CPU SPEED >

If compiling from source:
  You must have the pio_usb library installed along with Adafruit TinyUSB.
  Uploading is wishy-washy. I compile and get the UF2 file in the temp directory and then manually drop onto board.




