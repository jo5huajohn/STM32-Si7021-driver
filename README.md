# Temperature & Humidity Monitor

Firmware project demonstrating register-level I2C sensor integration and modular driver design on an STM32 microcontroller.

This project implements a reusable driver for the Si7021 on the STM32 Nucleo-F411RE using STM32 HAL.

The firmware performs:
- Relative humidity measurement
- Temperature measurement
- Heater control and resolution configuration
- Sensor reset
- Electronic serial number retrieval
- Firmware revision detection

All communication is performed over I²C following the device datasheet command protocol.