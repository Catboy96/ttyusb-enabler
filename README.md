# ttyusb-enabler
Make ttyUSB accessible for your current account  
[中文説明](https://ralf.ren/2751)

## Screenshot
![](https://raw.githubusercontent.com/Catboy96/ttyusb-enabler/master/screenshot.png)

## Introduction
When you are working on an embedded linux or FPGA project using Vivado, you must change ttyUSB permission to `666` to make it accessible for non-root account.  
Files included in this repository make a easy way for you to do the thing by clicking a icon.

## Usage
1. Put `ttyusb-enabler` in `~/.local/bin`
2. Change `[USERNAME]` to your username in `ttyusb-enabler.desktop`
3. Give these two files execution permission by:
`chmod +x ~/.local/bin/ttyusb-enabler && chmod +x ttyusb-enabler.desktop`

Double-click `ttyusb-enabler.desktop` whenever you want.  
Also you can move `ttyusb-enabler.desktop` wherever you want.
