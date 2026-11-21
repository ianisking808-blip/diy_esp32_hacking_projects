# diy_esp32_hacking_project(:<

NOTE: This is only for educational purposes only

Hi i am Jhon i will be teaching and showing you simple hacking devices and how to use
What you need for some projects

contents:[m5 stack stick s3](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L13)
,[esp32 marauder](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L34)
,[esp8266 deauther](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L120)
,[Credits & Acknowledgements](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/edit/main/README.md#L221)


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



esp8266 deauth you [can buy one](https://dstike.com/products/dstike-wifi-deauther-mini?srsltid=AYCX9vIDw-9Hq-6xPS5ixksbyq0SnOedBFWNUeOaF1hb-wkfWueySQ_I)or you can build one 

things to buy:
1.esp8266 mini d1 or d1 pro

2.oled 4 pin display screen 

3. wires

4. 3 buttons

4 pin display pins:

• OLED VCC → 3V3 

• OLED GND → GND

• OLED SDA → GPIO 4 (D2) 

• OLED SCL → GPIO 5 (D1)


Button pins:

•UP	D5	GPIO 14	GND	

•DOWN	D6	GPIO 12	GND	

•SELECT (BUTTON_A)	D7	

•BACK (BUTTON_B) (Optional)	D3	GPIO 0	GND

![esp8266 mini d1 or d1 pro](Images/deathur_wiring.jpg)


to flash download [esp8266 d1/esp8266 d1 pro](https://github.com/ianisking808-blip/diy_esp32_hacking_projects/blob/main/esp8266_deauther_2.6.1_WEMOS_D1_MINI.bin)
































































# Credits & Acknowledgements

A huge thank you to the developers and open-source projects that made these projects possible.

### ESP32 Marauder
- **Creator:** JustCallMeKoko
- GitHub: https://github.com/justcallmekoko
- Original project: https://github.com/justcallmekoko/ESP32Marauder

### ESP8266 Deauther
- **Creator:** Spacehuhn
- GitHub: https://github.com/Spacehuhn
- Original project: https://github.com/SpacehuhnTech/esp8266_deauther

### Acknowledgement
ESP32 Marauder was originally inspired by ESP8266 Deauther.

All original developers retain credit for their respective work. This project is independently maintained and is not an official release of either project.

Please refer to the original repositories for their respective licenses and usage conditions.

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
