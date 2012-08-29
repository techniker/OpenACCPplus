Documentation, tools and software for the Roche AccuChek Compact plus blood glucose meter

Bjoern Heller <tec@hellercom.de> (c) 2012

This Software is licensed under GNU/GPL


This Project serves as documentation/demo for using the AccuChek Compact plus
blood glucose meter as a compact general purpose portable developement platform.

### Hardware ###

Documentation regarding the PCB, schematics and needed datasheets can be found in /doc .

Pictures can be found here:
http://www.flickr.com/photos/hellercom/sets/72157622084668976/

The AccuChek Compact plus features:

-full-color OLED display with SSD1325X (Displaycontroller) 160x132 pixel (active area 35mmx28mm)
-Atmel ATMEGA2561V 8-Bit RISC CPU
-fully battery powered (two AAA-Cells) + RTC battery
-3V Supply-Voltage
-low power consumption
-Infrared Interface
-RTC (Real-time-clock)
-EM4094 13.56 MHz ISO 15693 and ISO 14443A&B compliant RFID IC with 3 wires serial interface

### Get one ###

So, where to get one?

-eBay (~ 1-10 EUR)


### Debugger used ###

### Programming ###


### Device pinout ###

#### Bottom PCB (IR facing right)  ####

##### Four bigger Pads in the middle  #####

1 - PE0 (RxD0) (CPU pin 2)
2 - PE1 (RxD0) (CPU pin 3)
3 - PG0 (WR-)  (CPU pin 51)
4 - AVCC/(RST-)(CPU pin 100/30)


!!Disclaimer!!

This project is not affiliated in any way with AccuChek (Roche) or other companies.
I'm not responsible for harm or damage that is done to anyone using this project.
If you are dependent on your AccuChek blood glucose meter, you should never open the device or try
to flash firmware into the device.
This project is NO enhancement for your Wellion meter nor will it EVER be able to measure blood glucose!!
So far, you've been warned!
