# stm32-bluetooth-home-automation
# 🏠 Smart Home Automation using STM32 & HC-05

## 📖 About the Project

This project is a simple and efficient smart home automation system developed using the STM32F446RETX microcontroller and HC-05 Bluetooth module. It allows users to wirelessly control home appliances like LED lights and DC fans using a smartphone through Bluetooth communication.
The main aim of this project is to provide an easy, low-cost, and user-friendly home automation solution without using internet connectivity.

## ✨ Features

* 📱 Wireless appliance control using Bluetooth
* 💡 LED ON/OFF and blinking control
* 🌪️ DC fan ON/OFF control
* ⚡ Real-time response using UART communication
* 🔋 Battery-powered portable system
* 🛡️ Safe appliance switching using relay module

## 🛠️ Components Used

* STM32F446RETX Nucleo Board
* HC-05 Bluetooth Module
* Relay Module
* 5V DC Fan
* LED
* Li-Ion Battery
* Buck Converter
* Breadboard & Connecting Wires


## 💻 Software & Tools

* STM32CubeIDE
* Embedded C
* UART Communication
* Serial Bluetooth Terminal App


## ⚙️ How It Works

The smartphone sends commands through Bluetooth to the HC-05 module. The STM32 microcontroller receives these commands using UART communication and controls the connected appliances through the relay module.

The system can:

* Turn LED ON/OFF
* Blink LED
* Turn fan ON/OFF
All operations happen wirelessly within the Bluetooth range.


## 📡 Command Controls

| Command | Action    |
| ------- | --------- |
| 1       | LED ON    |
| 2       | LED BLINK |
| 3       | LED OFF   |
| 4       | FAN ON    |
| 5       | FAN OFF   |

## 🧠 What I Learned

* STM32 programming
* UART communication
* Interrupt handling
* Bluetooth interfacing
* Relay control
* Embedded C programming
* Hardware and software integration


## 🚀 Future Improvements

* Mobile app development
* IoT/Wi-Fi integration
* Voice control system
* Sensor-based automation
* PCB design implementation

## 🎯 Applications

* Smart home systems
* Wireless appliance control
* Embedded system projects
* Home energy management

## 👨‍💻 Author

Harshitha S


