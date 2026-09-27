# CH641

English reference material and examples for the WCH CH641 wireless SoC.

## Overview

The CH641 is a low-power wireless microcontroller based on the QingKe RISC-V2A core. It integrates Bluetooth Low Energy functionality and supports USB PD and Type-C control, making it suitable for compact wireless accessories and battery-powered devices.

## Key features

- 48 MHz QingKe RISC-V2A core
- 2 KB SRAM and 16 KB Flash
- Three general-purpose DMA controllers
- Multiple 10-bit ADC channels
- BLE master, slave, and mesh-capable roles
- USART, I2C, USB, USB PD, Type-C, and PHY support
- BC charging interface and differential ISP/ISS programming support
- Hardware QSPI/ISP/ISS support and internal QR code storage
- GPIO, four high-voltage drive pins, five low-voltage drive pins, and 16/20/28-pin QFN package options

## Repository layout

| Path | Contents |
| --- | --- |
| `src/` | Reference source code and example resources |
| `docs/` | Device and reference documentation |
| `project/` | Project files and example applications, where provided |

## Development notes

Confirm the selected package, supply voltage, clock configuration, GPIO electrical limits, and debugger/programmer connection before programming a target board. The examples are reference material and may require board-specific adaptation.

## License

This repository retains the included [MIT License](LICENSE). Keep the license and copyright notices when redistributing the material.
