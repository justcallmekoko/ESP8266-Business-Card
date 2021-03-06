# ESP8266 Business Card

## Table of Contents
- [About](#about)
- [Assembly and programming](#assembly-and-programming)
- [List of Parts](#list-of-parts)
- [Schematic](#schematic)

## About
Pretty cool, right? A business card made out of fiberglass, copper, and (not)lead [RoHS](https://en.wikipedia.org/wiki/Restriction_of_Hazardous_Substances_Directive). What does it do other than just look cool or make your friends wonder why you're walking around with it like a nerd? Other than serving as a means by which to exchange contact information, it provides the recipient with a chance try their hand at basic electrical engineering and programming. Whether you want to become involved in the world of IoT development or you are just the O-est of G's and need the sickest business card on the block, the ESP8266 Business Card is a fun way to learn a little bit more about what goes on in the MountainDew dungeons of beta-males everywhere.

Make home automation tools. Disable your neighbor's WiFi. Make a WiFi enabled music visualizer that only responds to voice commands in Vietnamese. I don't care what you do with this hunk of junk as long as you enjoy messing with it.

## Assembly and programming
Ready to get started? Visit the [Wiki](https://github.com/justcallmekoko/ESP8266-Business-Card/wiki) for assembly and programming instructions

## List of Parts
|Footprint |Part/Value           |Specifications                                 |
| -------- |:-------------------:| --------------------------------------------- |
|C3, C4, C6|100nF                |[C38141](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_100nF-104-10-50V_C38141.html) |
|C5        |10uF                 |[C48181](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_10uF-106-20-25V_C48181.html) |
|R1, R2    |470Ω                 |[C114564](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_470R-470R-1_C114564.html) |
|R3        |220KΩ                |[C137568](https://lcsc.com/product-detail/_RC0805FR-07220KL_C137568.html)|
|R4-R10    |10KΩ                 |[C25804](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Uniroyal-Elec-0603WAF1002T5E_C25804.html) |
|R11       |100KΩ                |[C25611](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Uniroyal-Elec-0805W8J0104T5E_C25611.html)|
|MK1       |ESP8266 ESP-12       |[C82891](https://lcsc.com/product-detail/WIFI-Modules_ESP-12F-ESP8266MOD_C82891.html) |
|Q1, Q2    |S8050                |[C139514](https://lcsc.com/product-detail/Transistors-NPN-PNP_S8050_C139514.html)|
|SW1       |8-1437565-0          |[C266214](https://lcsc.com/product-detail/Others_TE-Connectivity_8-1437565-0_TE-Connectivity-8-1437565-0_C266214.html)|
|U1        |AMS1117-3.3          |[C6186](https://lcsc.com/product-detail/Low-Dropout-Regulators-LDO_AMS_AMS1117-3-3_AMS1117-3-3_C6186.html)  |
|U2        |CH340C               |[C84681](https://lcsc.com/product-detail/USB_CH340C_C84681.html) |
|USB1      |Micro USB-B 5P_C40942|[C40942](https://lcsc.com/product-detail/USB-Connectors_Jing-Extension-of-the-Electronic-Co-LCSC-micro-5PAll-posts-are-not-guided-Flat-welding-High-temperature_C40942.html) |

### Schematic
<p align="center">
    <img src="https://github.com/justcallmekoko/ESP8266-Business-Card/blob/master/design/Schematic_ESP8266-ESP12-Business-Card-4_ESP8266-ESP12-Business-Card-4-Schematic_20190524164315.png">
</p>
