# Digital Clock Project

This project is a digital clock implemented on an STM32 microcontroller using STMicroelectronics' CubeMX HAL library. It displays the current time and date on an ST7735 TFT LCD display.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [License](#license)

## Description

This project demonstrates how to create a digital clock using an STM32 microcontroller and an ST7735 TFT LCD display. It utilizes the CubeMX HAL library for peripheral initialization and the ST7735 driver for interfacing with the display.

## Features

- Displays current time (hours, minutes, seconds) in HH:MM:SS format.
- Displays current date (day, month, year) in Day Month Year format.
- Supports automatic adjustment for leap years.
- Utilizes SPI communication for interfacing with the TFT LCD display.

## Setup

### Prerequisites

- STM32 microcontroller development board (e.g., STM32F103C8T6)
- ST7735 TFT LCD display
- STM32CubeIDE or STM32CubeMX for project setup

### Installation

1. Clone this repository to your local machine.
2. Open the project in STM32CubeIDE or import it into STM32CubeMX.
3. Connect the STM32 development board and ST7735 TFT LCD display to your computer.
4. Build and flash the project to the STM32 microcontroller.

## Usage

1. After flashing the project to the microcontroller, power it on.
2. The digital clock will start displaying the current time and date on the TFT LCD display.
3. The clock automatically updates in real-time.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute this code for personal or commercial purposes.

