# Ep_Hackathon

Smart embedded monitoring and alert system for Autonomous vehicle using STM32F407VG microcontroller.

## Features

* Ultrasonic obstacle detection
* MQ7 gas sensor monitoring
* DHT11 temperature & humidity sensing
* Float sensor fuel monitoring
* Servo motor control
* Bluetooth communication using HC-05
* LED and buzzer alerts

## Hardware Used

* STM32F407VG
* HC-SR04 Ultrasonic Sensor
* MQ7 Gas Sensor
* DHT11 Sensor
* HC-05 Bluetooth Module
* Servo Motor
* Float Sensor
* LEDs & Buzzer

## Installation

```bash
git clone https://github.com/your-username/epHackV1.git
cd epHackV1
```

## Usage

### Open in STM32CubeIDE

Import the project into STM32CubeIDE.

### Build Project

```text
Project -> Build Project
```

### Flash Firmware

Upload the firmware using ST-Link programmer.

## Project Structure

```text
Core/
 ├── Inc/
 ├── Src/
 └── Startup/

Drivers/
 ├── CMSIS/
 └── STM32F4xx_HAL_Driver/
```

## Technologies Used

* Embedded C
* STM32 HAL Drivers
* STM32CubeIDE
* UART Communication
* Bluetooth Communication

## Functional Overview

* Reads sensor data continuously
* Detects gas leakage and obstacles
* Monitors temperature and humidity
* Activates buzzer and LEDs during alerts
* Sends data through UART/Bluetooth

## Future Improvements

* IoT cloud integration
* Mobile app support
* GPS tracking
* SD card logging
* Real-time dashboard

## Author

Krutika Pingale

## License

MIT License
