# Awesome Hardware Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Introduction 

`Hardware Reverse Engineering` focus on circuitry (boards, ICs) and intercomponent relation.

The scope and level of analysis can be vary greatly, some common targets:

- firmware.
- board layout.
- chip circuit design.

Some notable process:

- teardown: product disassembly, component/subsystem identification
- interface: protocol monitoring/analysis/emulation
- firmware: extract/modify code or data
- circuit: silicon modification

## Table of Contents

- Resources
    - [Books](#books)
    - [Courses](#courses)
    - [Channels](#channels)
    - [References](#references)
    - [Protocol List](#protocol-list)
- Hadware Tools
    - [Bus Interface](#bus-interface)
    - [Programmers & Flashers](#programmers--flashers)
    - [Hardware Debuggers](#hardware-debuggers)
    - [Protocol Analyzers](#protocol-analyzers)
    - [Logic Analyzers](#logic-analyzers)
    - [Osciloscopes](#osciloscopes)
    - [Dev & Breakout Boards](#dev--breakout-boards)
    - [Radio Frequency](#radio-frequency)
    - [Magnetic Strip](#magnetic-strip)
- Software Tools
    - [EDA](#eda)
    - [Firmware Extract](#firmware-extract)
    - [Disassemblers & Decompilers](#disassemblers--decompilers)
    - [Software Debuggers](#software-debuggers)

- - - 

## Books

Electronics, VHDL, and circuit design

* [Digital Electronics](https://amzn.com/8125939369)
* [Digital Fundamentals](https://amzn.com/0132737965)
* [Digital Design](https://amzn.com/B00HQ1CYUU)
* [The Art of Electronics](https://amzn.com/0521809266)

Hardware hacking

* [The Hardware Hacker: Advetures in Making and Breaking Hardware](https://amzn.com/159327758X)
* [Hardware Hacking: Have Fun while Voiding your Warranty](https://amzn.com/B001UN2WDY)
* [Hardware Hacking Projects for Geeks](https://amzn.com/0596003145) 
* [Game Console Hacking: Xbox, PlayStation, Nintendo, Game Boy, Atari and Sega](https://amzn.com/B001V7U7AE)

## Courses

Electronic

* [Lessons in Electric Circuits](https://www.ibiblio.org/kuphaldt/electricCircuits/) - Free high quality textbooks and worksheets with emphasys on theory, simulation, and the socratic method.
* [Ultimate Electronics: Practical Circuit Design and Analysis](https://ultimateelectronicsbook.com/) - Free online book with interactive schematics & simulations by CircuitLab (under development).
* [Khan Academy - Electrical Engineering](https://www.khanacademy.org/science/electrical-engineering) - Non-profit learning platform with a full course on electrical engineering and related topics.
* [NEETS (Navy Electricity and Electronics Training Series)](https://www.fcctests.com/neets/Neets.htm) - U.S. Navy Non-Resident Training Course Material.
* [Berkeley EECS](http://inst.eecs.berkeley.edu/classes-eecs.html) - Comprehensive EE & CS course website archives.
* [Dr. Jacob Baker](http://cmosedu.com) - Courses and tutorials, professor at The University of Nevada, Las Vegas.
* [Dr. Abraham](https://www.cerc.utexas.edu/~jaa/teaching.html), [Dr. McDermot](http://users.ece.utexas.edu/~mcdermot/), and [Dr. Valvano](http://users.ece.utexas.edu/~valvano/) - Courses materials, professors at UT Austin

Radio Frequency

* [Software Defined Radio with HackRF](https://greatscottgadgets.com/sdr/)

## Channels

## References

Learning Assembly

* [Low-level Code Reference](https://github.com/ReversingID/LowLevelCode-Reference)

Development Boards

* [Arduino](https://www.arduino.cc/) | based on AVR or ARM 
* [NodeMCU](https://www.nodemcu.com) | based on ESP8266
* [Teensy](https://www.pjrc.com/teensy/) | based on ARM
* [MSP430 Launchpad](http://www.ti.com/tool/MSP-EXP430G2ET) | based on TI MSP430
* [STM32 Nucleo](https://www.st.com/en/evaluation-tools/stm32-nucleo-boards.html)

Single-Board Computer (family)

* [Raspberry Pi](https://www.raspberrypi.org/)
* [BeagleBoard](https://beagleboard.org/)
* [Onion Omega](https://onion.io/)
* [Pine64](https://www.pine64.org/)
* [ODROID](https://www.hardkernel.com)

## Protocol List

Inter-circuitry protocol (Internal)

This protocol used for communication between circuit or modules, such as EEPROM, RAM, RTC, sensors, etc.

* SPI: *Serial Peripheral Interface*, synchronous protocol with master-slave design.
* I2C: *Inter-Integrated Circuit*, synchronous protocol with multi-master and multi-slave support.

System communication (External)

* CAN: *Controller Area Network*, device communication popular in vehicle.
* USB: *Universal Serial Bus*
* UART & USART: *Universal Synchronous Asynchronous Receiver-Transmitter*
* RS232

Debugging protocol

* JTAG: *Joint-Test Action Group*
* SWD: *Serial-Wire Debug*, ARM specific protocol

- - - 

## Bus Interface

* [Shikra](https://int3.cc/products/the-shikra) - JTAG, SPI, I2C, UART, GPIO
* [Hydrabus](https://hydrabus.com/) - UART, I2C, USB, smartcard, 2-wire, wiegand, SPI, CAN, SDIO, DAC, 1-wire
* [Xpliot Nano](https://expliot.io/products/expliot-nano)
* [Bus Pirate](http://dangerousprototypes.com/docs/Features_overview) - 1-wire, I2C, SPI, JTAG, UART
* USB to TTL/UART

OBD adapter

* [ObdDiag](http://www.obddiag.net/) - open source ELM327 OBD adapter, connect to On-Board Diagnostic (OBD) port for connecting to car's self-diagnostic system.
* [M2](https://www.macchina.cc/m2-introduction) - 

## Programmers & Flashers

*read/write device which contain memory*

Universal

* [EE Tools](https://eetools.com/product-category/programmers/)

Microcontroller/Microprocessor Specific

* STM32 programmer - enter DFU (Device Firmware Upgrade) mode for programming and debugging
* AVR programmer

## Hardware Debuggers

SWD (Serial Wire Debugger), ARM specific

* [ST-Link](https://www.st.com/en/development-tools/st-link-v2.html)

JTAG (Joint-Test Action Group)

* [JTAGulator](https://github.com/grandideastudio/jtagulator) - scan and identify JTAG pin
* [JTAGEnum](https://github.com/cyphunk/JTAGenum) - using arduino to identify JTAG pin
* [RIFF Box](http://www.riffbox.org/)
* [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - JTAG debugger
* [Segger J-Link](https://www.segger.com/products/debug-probes/j-link/)
* Shikra
* ST-Link

## Protocol Analyzers

*real-time, non-intrusive monitoring/capture/decoding of wired communication*

Multi

* [TotalPhase Beagle](https://www.totalphase.com/products/beagle-i2cspi/) - USB/I2C/SPI

USB 

* Teledyn [LeCroy Voyager](https://teledynelecroy.com/protocolanalyzer/usb) series
* [OpenVizsla](http://openvizsla.org/)
* [Daisho](https://greatscottgadgets.com/daisho/)

CAN

* [CANtact](https://linklayer.github.io/cantact/) - CAN (Controller Area Network) to USB interface
* [TotalPhase Komodo](https://www.totalphase.com/products/komodo-canduo/) - CAN

## Logic Analyzers

*concurrently capturing, visualizing, and decoding large quantities of digital data*

* [Logic Pirate](http://dangerousprototypes.com/docs/Logic_Pirate) - 8 channels
* [Saleae](https://www.saleae.com/)
* USB Logic Analyzer
* [BeagleBone as Logic Analyzer](https://github.com/abhishek-kakkar/BeagleLogic)

## Osciloscopes

*visual display of electrical signals and how they change over time*

Standalone

* HP/Agilent
* Tektronix
* Rohde & Schwarz
* LeCroy
* Rigol

PC_based

* ProcScope
* USBee
* PicoScope

## Dev & Breakout Boards

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

- - -

## EDA

EDA (Electronic Design Automation) and ECAD (Electronic Computer-Aided Design)

* [Eagle](https://www.autodesk.com/products/eagle/overview)
* [KiCad](https://www.kicad-pcb.org/)
* [Altium](https://www.altium.com/) and free [Altium CircuitMaker](https://circuitmaker.com/)
* [Pulsonix](https://www.pulsonix.com/)
* [DesignSpark PCB](https://www.rs-online.com/designspark/pcb-software)
* [gEDA](http://geda-project.org/)
* [DipTrace](https://diptrace.com/)
* [LibrePCB](https://librepcb.org/)
* [Horizon EDA](https://github.com/horizon-eda/horizon)

## Firmware Extract

* [Binwalk](https://github.com/ReFirmLabs/binwalk)

## Disassemblers & Decompilers

Multi-architecture

* [Radare2](http://www.radare.org/r/) // [Cutter](https://cutter.re)
* [objdump](http://linux.die.net/man/1/objdump)

## Software Debuggers

Hardware debugger

* [OpenOCD](http://openocd.org/) - Open On-Chip Debugger, give GDB support.
* [UrJTAG](http://www.urjtag.org) - Universal JTAG Library

Signal Analysis

* [Sigrok](https://sigrok.org/) // [PulseView](https://sigrok.org/wiki/PulseView)
* [Open Bench Logic Sniffer](http://dangerousprototypes.com/docs/Open_Bench_Logic_Sniffer)

Firmware debugger

* [GDB](https://www.gnu.org/software/gdb/)