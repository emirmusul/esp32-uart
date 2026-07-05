# ESP32 UART Communication

Serial communication between ESP32 and computer via UART.

## What it does
Sends "Hello from ESP32!" message every second over UART to the host computer.

## Requirements
- ESP32 development board
- ESP-IDF v6.0
- USB cable

## How to run
source ~/esp-idf/export.sh
idf.py -p /dev/cu.usbserial-0001 flash monitor

## Topics
FreeRTOS, UART, Serial Communication, ESP-IDF
