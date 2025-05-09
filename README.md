# TI-MSP430

Small Project with TI's MSP430 MCU

## 01 - IDE Setup

**Objective:** Set up the development environment for programming the MSP430FR235x.

**Instructions:**

- Install Code Composer Studio (CCS)
- Connect the MSP430FR235x Development Board via USB
- Open CCS and create a new project for MSP430FR235x

## 02 - GPIO and External Interrupts

**Objective:** Learn how to configure GPIO ports and manage external interrupts.

**Example Code:** GPIO_LED_Blink

**Instructions:**

- Configure pins as input and output
- Develop code to blink an LED
- Implement external interrupt handling for a button press

## 03 - UART Polling and Interrupts

**Objective:** Understand UART communication using polling and interrupt-driven methods.

**Example Code:** UART_Example

**Instructions:**

- Set up UART for asynchronous serial communication
- Implement UART polling method for sending and receiving data
- Modify the example to use UART interrupts for handling communications

## 04 - ADC Data Acquisition

**Objective:** Execute ADC conversions to acquire analog sensor data.

**Example Code:** ADC_Temperature_Sensor

**Instructions:**

- Set up the ADC module
- Acquire and process data from a temperature sensor

## 05 - Timer Operations (Including PWM)

**Objective:** Understand Timer_A and Timer_B and implement PWM functionalities.

**Example Code:** Timer_PWM_Control

**Instructions:**

- Configure timer interrupts for periodic events
- Implement PWM signal generation for motor control

## 06 - SPI Communication

**Objective:** Explore SPI protocol and interface with external devices like displays or sensors.

**Example Code:** SPI_Display_Interface

**Instructions:**

- Configure SPI master/slave settings
- Develop code to interface with an SPI-enabled display

## 07 - I2C Communication

**Objective:** Learn master/slave I2C configurations and data exchange.

**Example Code:** I2C_EEPROM_ReadWrite

**Instructions:**

- Set up an I2C master to communicate with an EEPROM
- Execute read and write operations on the EEPROM

## 08 - Introduction to FreeRTOS

**Objective:** Learn the basics of FreeRTOS and set up a simple multitasking environment.

**Example Code:** FreeRTOS_Basic

**Instructions:**

- Set up FreeRTOS on the MSP430FR235x
- Implement real-time scheduling for efficient task management
- Use queues and semaphores for inter-task communication
