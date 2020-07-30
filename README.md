# Bootloader for nrf52-watch


This is a CDC/DFU/UF2 bootloader based on
[Adafruit's](https://github.com/adafruit/Adafruit_nRF52_Bootloader). 

Fork exists for custom board definition; see adafruit's docs for all
documentation.

Install the included udev rule to make things easier.

Build with `make BOARD=watch`
Upload with `make BOARD=watch SERIAL=/dev/nrf52WatchUpdate`
