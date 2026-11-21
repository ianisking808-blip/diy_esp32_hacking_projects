For esp32 marauder it is gonna be very hard to do don't worry it will take you 1-3 days to do 
things needed to buy

1.TFT 2.4 Inch SPI LCD Screen Module

2.esp32 devkitc v4 with ESP-32u

3.wires lots of wires

4.32 or less gb sd card

5.GPS Module NEO-6M (optional)

6. 3.7 v lipo battery (kinda optional)

7.TP4056 (kinda optional)

8.bread broad

First wire like 

Pin connections:
2.4" TFT Module Pin	

 VCC	3.3V (or 5V if U1 regulator is populated)	Power supply
 
 GND	GND	Ground
 
 CS	GPIO17	Display Chip Select
 
 RESET	GPIO05	Display Reset
 
 DC / RS	GPIO16	Data / Command select
 
 SDI (MOSI)	GPIO23	Shared SPI MOSI
 
 SCK	GPIO18	Shared SPI Clock

 LED	GPIO32 (or 3.3V for always-on)	Backlight control
 
 SDO (MISO)	GPIO19	Shared SPI MISO

 T_CLK	GPIO18	Touch SPI Clock (shared)

 T_CS	GPIO21	Touch Chip Select
 
 T_DIN	GPIO23	Touch MOSI (shared)

 T_DO	GPIO19	Touch MISO (shared)

 T_IRQ	(Leave unconnected)	Touch interrupt (unused)

SD_CS (4-pin header)	GPIO12	MicroSD Chip Select

SD_MOSI (4-pin header)	GPIO23	MicroSD MOSI (shared)

SD_MISO (4-pin header)	GPIO19	MicroSD MISO (shared)

SD_SCK (4-pin header)	GPIO18	MicroSD Clock (shared)

Gps pins:
NEO-6M Module Pin	ESP32 DevKit V4 Pin	Notes

VCC:	3.3V (or 5V)	Most GY-NEO6MV2 boards include an onboard 3.3V regulator and accept 3.3V–5V

GND:	GND	Common ground

TX: (GPS Transmit)	GPIO04 (IO04)	Sends NMEA GPS data into the ESP32 (GPS_TX in Marauder)

RX: (GPS Receive)	GPIO13 (IO13)	Receives commands from the ESP32 (GPS_RX in Marauder)

battery pins (optional)

![Battery Connector](Images/battery%20connecter.png)


To flash it go to https://justcallmekoko.github.io/MarauderInstaller/

chose marauder v4 or v6 than on the right select the latest version 

press continue and tick first install press continue agin and tick skip 

press continue and scroll down and press the flash button and connect to the esp32 dev kit v4

