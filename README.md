# IoT Climate Monitor Firmware

Firmware for the IoT climate monitoring sensor module developed using Zephyr RTOS.

## Project Overview

This firmware supports a distributed sensor module that measures:

- Temperature
- Relative humidity
- Illuminance
- Dew point

The temperature and humidity subsystem uses the Texas Instruments HDC3022DEJR sensor over I2C.

## Development Environment

- Operating System: Ubuntu 26.04 LTS
- Zephyr Version: v4.5.0-rc2-179-gf78c4deb452
- west Version: v1.5.0
- Zephyr SDK Version: 1.0.1
- Target MCU: STM32U575RIT6Q
- RTOS: Zephyr

## Project Structure

```text
iot_climate_monitor/
├── src/
│   └── main.c
├── boards/
├── docs/
├── CMakeLists.txt
├── prj.conf
├── README.md
└── .gitignore 
