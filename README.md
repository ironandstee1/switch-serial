# switch-serial

This repository hosts the hex files, executable files, and instructions for setting up switch controllers and scripts that involve serial connection. No source code will be here - only flashable hexes and executables. If you want source code, this can be found in my other repositories starting [here](https://github.com/ironandstee1/swemu-plus-plus). 

## swemu-plus-plus

This folder deals with all of my pokemon scripts. 

### Hardware

1. FT232H USB to UART device

1. ATmega32u4 based board with TX and RX pins

### Instructions

1. Download the [hex file](https://github.com/ironandstee1/switch-serial/blob/master/swemu-plus-plus/swemuplusplus.hex). You'll probably just want to clone the repo or download it as a zip from the root from [here](https://github.com/ironandstee1/switch-serial). 

1. Flash the hex file to your ATmega32u4 board [as shown here](https://youtu.be/TzfHGD3JPSo) with QMK Toolbox or Atmel Flip. 

1. Downlaod the exe file located [here](https://github.com/ironandstee1/switch-serial/blob/master/swemu-plus-plus/SwemuMenu.exe)

1. Plug the FTDI chip into the computer. 

1. Connect the FTDI's TX to the Arduino's RX and the FTDI's RX to the Arduino's TX. 

1. Start your game, prepare for the script, and plug your board into your PC.

1. Run the exe file and choose your script using the menu. 

### Status

This program and its associated hex file are fully functional. The scripts that do not currently have options are: fossil reviving, EV training, and egg hatching straight from boxes. The first two require specific inputs that I have not taken the time to hash out in the script you. The third one is not a script I have fully developed yet. If you want to use the fossil reviving or EV training scripts you'll have to program them from [here](https://github.com/ironandstee1/swemu-plus-plus). 

## HM-10 bluetooth controller (coming soon)

## Twitch plays switch (coming soon)
