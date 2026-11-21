# diy_esp32_hacking_project

NOTE: This is only for educational purposes only

Hi i am Jhon i will be teaching and showing you simple hacking devices and how to use
What you need for some projects

contents:[m5 stack stick s3](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L13)
,[esp32 marauder](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L34)
,[esp8266 deauther](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L50)


We will be using bruce
stuff you need


1.m5 sticks3

2.RFID module (optional)

3.CC1101 or nRF24L01 (optional)

OK that is the most you need also the links are at line 89

First go to https://bruce.computer/flasher

select latest scroll down and you will see a lot of options.

select m5 stack than find stick s3 press flash and it should work.

if any problems go to [troubleshooting.md](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/blob/main/troubleshooting.md)


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
1. VCC	3.3V (or 5V if U1 regulator is populated)	Power supply
2. GND	GND	Ground
3. CS	GPIO17	Display Chip Select
4. RESET	GPIO05	Display Reset
5. DC / RS	GPIO16	Data / Command select
6. SDI (MOSI)	GPIO23	Shared SPI MOSI
7. SCK	GPIO18	Shared SPI Clock
8. LED	GPIO32 (or 3.3V for always-on)	Backlight control
9. SDO (MISO)	GPIO19	Shared SPI MISO
10. T_CLK	GPIO18	Touch SPI Clock (shared)
11. T_CS	GPIO21	Touch Chip Select
12. T_DIN	GPIO23	Touch MOSI (shared)
13. T_DO	GPIO19	Touch MISO (shared)
14. T_IRQ	(Leave unconnected)	Touch interrupt (unused)
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
[![Battery pins](Images/batterypins.png)](Images/esp32.jpg)






































































CREDITS & ACKNOWLEDGEMENTS

Bruce Firmware:
https://github.com/pr3y/Bruce

Original project and contributors:
https://github.com/bmorcelli
https://github.com/IncursioHack
https://github.com/Luidiblu
https://github.com/eadmaster
https://github.com/rennancockles
https://github.com/7h30th3r0n3
https://github.com/Tawank
https://github.com/geo-tp

All original authors retain credit
for their respective work.
