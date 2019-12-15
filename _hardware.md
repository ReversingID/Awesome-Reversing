# Awesome Hardware Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Table of Contents

- Resources
    - [Books](#books)
    - [Courses](#courses)
    - [Channels](#channels)
    - [References](#references)
    - [Protocol List](#protocol-list)
- Tools
    - [Firmware Extract](#firmware-extract)
    - [Disassemblers](#disassemblers)
    - [Debuggers](#debuggers)
    - [Bus Interface](#bus-interface)
    - [Logic Analyzer](#logic-analyzer)
    - [Dev Board](#dev-board)
    - [Radio Frequency](#radio-frequency)
    - [Magnetic Strip](#magnetic-strip)

- - - 

## Books

* [The Hardware Hacker: Advetures in Making and Breaking Hardware](https://amzn.com/159327758X)

## Courses

* [Software Defined Radio with HackRF](https://greatscottgadgets.com/sdr/)

## Channels

## References

Learning Assembly

* [Low-level Code Reference](https://github.com/ReversingID/LowLevelCode-Reference) - coming soon

- - - 

## Firmware Extract

* [Binwalk](https://github.com/ReFirmLabs/binwalk)

## Disassemblers & Decompilers

Multi-architecture

* [Radare2](http://www.radare.org/r/) // [Cutter](https://cutter.re)
* [objdump](http://linux.die.net/man/1/objdump)

## Debuggers

Hardware debugger

* [OpenOCD](http://openocd.org/) - On-Chip Debugger

Signal Analysis

* [Sigrok](https://sigrok.org/) // [PulseView](https://sigrok.org/wiki/PulseView)

Firmware debugger

* [GDB](https://www.gnu.org/software/gdb/)

## Bus Interface

Multi-interface

* [Shikra](https://int3.cc/products/the-shikra) - JTAG, SPI, I2C, UART, GPIO
* [Hydrabus](https://hydrabus.com/) - UART, I2C, USB, smartcard, 2-wire, wiegand, SPI, CAN, SDIO, DAC, 1-wire
* [Bus Pirate](http://dangerousprototypes.com/docs/Features_overview) - 1-wire, I2C, SPI, JTAG, UART
* USB to TTL/UART

Programmer

* [Xpliot Nano](https://expliot.io/products/expliot-nano)
* STM32 programmer - enter DFU (Device Firmware Upgrade) mode for programming and debugging
* AVR programmer

JTAG

* [JTAGulator](https://github.com/grandideastudio/jtagulator)

CAN

* [CANtact](https://linklayer.github.io/cantact/) - CAN (Controller Area Network) to USB interface

OBD adapter

* [ObdDiag](http://www.obddiag.net/) - open source ELM327 OBD adapter, connect to On-Board Diagnostic (OBD) port for connecting to car's self-diagnostic system.
* [M2](https://www.macchina.cc/m2-introduction) - 

## Logic Analyzer

- [Logic Pirate](http://dangerousprototypes.com/docs/Logic_Pirate) - 8 channels
- [Saleae](https://www.saleae.com/)
- USB Logic Analyzer
- [BeagleBone as Logic Analyzer](https://github.com/abhishek-kakkar/BeagleLogic)

## Dev Board & Breakout Board

* [GoodFET](http://goodfet.sourceforge.net/)
* [GreatFET One](https://greatscottgadgets.com/greatfet/one/)

## Radio Frequency

*Analyze, modify, and replay Radio Frequency signal.*

General-purpose

* [HackRF](https://greatscottgadgets.com/hackrf/) - half duplex, 1 MHz - 6 GHz
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - full duplex, 
* [RTL-SDR](https://www.rtl-sdr.com/) - RX, 500 kHz - 1766 MHz
* [YARD Stick](https://greatscottgadgets.com/yardstickone/) - half duplex, 300-348 MHz, 391-464 MHz, 782-928 MHz

Zigbee

* [ApiMote](https://github.com/riverloopsec/apimote) - IEEE 802.15.4/ZigBee sniffing hardware
* [Freakduino](https://freaklabs.org/documentation/freakduino/)

Bluetooth

* [Ubertooth](https://greatscottgadgets.com/ubertoothone/)
* [Bluefruit LE Snifferluef](https://www.adafruit.com/product/2269)

RFID & NFC

* [Proxmark3](https://proxmark.com/)
* [Chameleon](https://lab401.com/products/chameleon-mini-reve-rebooted) - NFC emulation and manipulation tool
* [HydraNFC](https://hydrabus.com/hydranfc-1-0-specifications/)
* ACR-122U - RFID/NFC reader/writer

## Magnetic Strip

* [MagSpoof](https://samy.pl/magspoof/) - wireless credit card / magnetic stripe spoofer