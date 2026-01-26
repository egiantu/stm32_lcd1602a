# STM32 board drive a 1602a LCD

Drive a 1602A LCD from a STM32 Nucleo-F103RB board without I2c

Description from the STMicroelectronics website:

"The STM32 Nucleo-64 board provides an affordable and flexible way for users to try out new concepts and build prototypes by choosing from the various combinations of performance and power consumption features provided by the STM32 microcontroller. For the compatible boards, the internal or external SMPS significantly reduces power consumption in Run mode."

https://www.st.com/en/evaluation-tools/nucleo-f103rb.html

With this project, I gather the basic instructions and code, to manage LCD from the STM board

## Table of Contents

- [STM32_LCD1602](STM32-board-drive-a-1602a-LCD)
  - [Table of Contents](#table-of-contents)
  - [Version](#version)
  - [Contents](#contents)
  - [Restrictions](#restrictions)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Usage](#usage)
  - [Changelog](#changelog)
  - [Authors](#authors)

## Version

For version information check [CHANGELOG.yaml](CHANGELOG.yaml)

## Requirements

These are the components used for this experiment

- [STM32 development board](https://www.st.com/en/evaluation-tools/nucleo-f103rb.html) 
- [16×2 LCD module](https://www.winstar.com.tw/products/lcd-display/character-lcd-display-module/dot-matrix-lcd.html)
- 10 kΩ potentiometer for contrast
- Jumper wires and
- Breadboard

## Installation

## Configuration

<img width="1955" height="1799" alt="circuit_image" src="https://github.com/user-attachments/assets/5a0508b1-f539-4517-9c8e-3a0b228c510c" />

Pinout configuration

- STM32 PC8 -> RS LCD
- STM32 PC5-> EN LCD

- STM32 PA12 -> D4 LCD
- STM32 PA11 -> D5 LCD
- STM32 PB12 -> D6 LCD
- STM32 PB11 -> D7 LCD

## Usage

## Changelog

Change log is maintained in [CHANGELOG.yaml](CHANGELOG.yaml)

## Authors
- Emanuele Gianturco


