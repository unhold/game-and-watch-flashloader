# game-and-watch-flashloader
A small tool to flash the SPI-flash using OpenOCD.

_This fork adds support for "MX25U51245G 54" 64MByte Flash. If you have not yet soldiered the chip
you are better of trying to get the "MX25U51245G" instead of the "MX25U51245G 54" first. The former
has better backwards compatibility._

## Usage

- (Optional) Initialize using STM32CubeMX or dowload all SDK files using `make download_sdk -j`
- Build the code using `make`
- Run `flash.sh`, point it to the image you want to flash
- Wait until your device blinks once a second
- Done
