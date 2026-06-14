# stm32-bluetooth-home-automation
# Smart Home Automation using STM32 and HC-05 Bluetooth Module

## 📌 Overview

This project demonstrates a Bluetooth-based Smart Home Automation system using the STM32F446RETX microcontroller and HC-05 Bluetooth module. The system enables wireless control of household appliances such as LED lights and DC fans through a smartphone application using UART communication.

The project focuses on embedded systems design, wireless communication, relay interfacing, and real-time appliance control.

# 🚀 Features

* Wireless control of appliances using Bluetooth
* UART interrupt-based communication
* LED ON/OFF and Blink control
* DC fan ON/OFF control using relay module
* Real-time response system
* Portable battery-powered design
* Low-cost and energy-efficient solution

# 🛠️ Hardware Components

* STM32F446RETX Nucleo Board
* HC-05 Bluetooth Module
* 5V Relay Module
* 5V DC Fan
* LED
* 3.7V Li-Ion Battery Pack
* Buck Converter Module
* Breadboard and Connecting Wires

# 💻 Software Used

* STM32CubeIDE
* Embedded C
* ARM GCC / Keil Compiler
* Serial Bluetooth Terminal Application
* UART Communication Protocol

# ⚙️ Working Principle

The smartphone sends Bluetooth commands to the HC-05 module. The STM32 microcontroller receives these commands through UART communication and processes them to control connected appliances via relay switching.

The relay module safely switches the appliances ON/OFF while maintaining electrical isolation between the control and power circuits.

# 📡 Command Functions

| Command | Function  |
| ------- | --------- |
| 1       | LED ON    |
| 2       | LED BLINK |
| 3       | LED OFF   |
| 4       | FAN ON    |
| 5       | FAN OFF   |

# 🧠 Key Concepts Used

* Embedded Systems
* UART Communication
* Interrupt-Based Programming
* Bluetooth Communication
* Relay Interfacing
* GPIO Control
* Power Regulation
* Real-Time Embedded Control

# 🔧 Future Improvements

* Mobile application development
* Wi-Fi / IoT integration
* Voice assistant support
* Sensor-based automation
* PCB implementation
* Cloud monitoring system

# 📈 Results

* Successful Bluetooth communication established using HC-05 module
* Reliable real-time appliance control achieved
* Stable relay switching using STM32 GPIO control
* Fast response within Bluetooth operating range
* Efficient battery-powered operation using buck converter regulation

# 📚 Learning Outcomes

* STM32 peripheral configuration
* UART interrupt handling
* Embedded C programming
* Hardware-software integration
* Wireless communication using Bluetooth
* Relay module interfacing
* Embedded debugging and testing

# 🎯 Applications

* Smart Home Systems
* Wireless Appliance Control
* IoT Prototyping
* Embedded Systems Education
* Energy-Efficient Automation

# 👨‍💻 Author

Harshitha s
Department of Electronics and Communication Engineering
