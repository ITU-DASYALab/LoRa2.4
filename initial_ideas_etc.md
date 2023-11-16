# project ideas

## space

  * assemble and test TinyGS2.4 stations from kits we have

  * build a mockup satellite, place it some place far and high

	hookup a sx1280 to a toradex or such
	t-beam 2.4


  * sending images over LoRa, scheduling partial transfers

  * a 2.4 "beeper"  <== beacons

## chips, boards, components

2 possible chips:

   * SX1280
   * LR1120


### SX1280

see overview of modules using SX1280:
https://github.com/thingsat/tinygs_2g4station/blob/main/README.md

NiceRF modeule:

https://www.nicerf.com/item/sx1280/sx1280-lora-module-lora1280f27

Full boards, MCU, ESP32 - LilyGo 

https://www.banggood.com/LILYGO-T3S3-V1_0-ESP32-S3-LoRa-SX1262-or-SX1276-SX1280-2_4G-Development-Board-WiFi-Bluetooth-Wireless-Module-0_96-Inch-OLED-Display-Type-C-p-1997240.html?cur_warehouse=CN&ID=6324172&rmmds=search


## amplifiers

#### SMD amps - $1 range:

33 dB -
https://www.mouser.dk/ProductDetail/Skyworks-Solutions-Inc/SE2576L-R?qs=WMHGlxXAKT%252BgTam3WBvNxQ%3D%3D

28 dB -
https://www.mouser.dk/ProductDetail/Qorvo/RF5102TR7?qs=tkvX2tz6JTEeDHFjgybyMQ%3D%3D

30 dB -

https://www.mouser.dk/ProductDetail/Microchip-Technology/LX5518LQ-TR?qs=8oSzWg8cI46KfpA8algP0A%3D%3D


#### big outdoor amps, up to 30 W -
https://www.gnswireless.com/product-category/products/wireless-amplifiers/2-4-ghz-amplifiers/outdoor-2-4-ghz-amplifiers/

#### eval amp kits, with connectors and stuff

analog devices, 20 dB -
https://www.everythingrf.com/news/details/13094-analog-devices-introduces-usb-powered-2-4-ghz-rf-power-amplifier-evaluation-board

TI, 25 dB -
https://www.ti.com/product/CC2595



## Grenoble Thingsat 2.4 mission, Sork-1 etc

very worth reading -

https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/blob/master/cubesat_mission/README.md
https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/tree/abbc4336b722b259d66ea14cfae539ba931b1ded/cubesat_mission_2
https://github.com/thingsat/tinygs_2g4station/blob/main/README.md

## LoRa meets CANBus


https://www.seeedstudio.com/LoRa-E5-CAN-FD-dev-kit-CANBUS-p-5398.html

CAN32—an ESP32-Based CAN Bus Board - should work on a TTGO 2.4 ?
https://www.hackster.io/news/the-can32-an-esp32-based-can-bus-board-af5c9e1bd8ec

================================================================================================================================

# Further reading

Janssen, T.; BniLam, N.; Aernouts, M.; Berkvens, R.; Weyn, M. LoRa 2.4 GHz Communication Link and Range. Sensors 2020, 20, 4366. https://doi.org/10.3390/s20164366 

https://pycubed.org

TinyGS: https://tinygs.com/

LoRa basics: lora-alliance https://lora-alliance.org/

thethingsnetwork https://www.thethingsnetwork.org/docs/lorawan/

wndw, the "green book" is about wi-fi, but provides some basics (antennas, free space loss, ..): https://wndw.net/book.html#readBook

other keywords:

Cubesat

Canbus

csp CUBESAT PROTOCOL




