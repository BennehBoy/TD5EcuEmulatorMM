# TD5 Ecu Emulator
STM32 & SSD1306 based TD5 ECU Emulator - I2C LCD, Emulated K-line

You can use a Maple Mini/clone or Bluepill as a hardware target (or most STM32 microcontrollers but you may have to change pin assigments / serial device for the k-line)

Requires the official stm32 core -> https://github.com/stm32duino/Arduino_Core_STM32

Updated to include Fuelling PID - sniffed from real ECU on bench (values output are zeros for no, until in car sniff can be completed)

Pins for OLED changed in line with LRDuinoTD5 project.

Adapted from Luca72's Arduino based TD5 ECU Emulator

# Working PID's

Initialisation

Diags

Seed

KeyResponse

RPM

Temperatures

MAP

Battery Voltage

AAP

Speed

Fuelling (NEW Oct 2023)

Keep Alive

# Requirements

An STM32 Microcontroller (Maple Mini or Bluepill)

An SSD1306 SPI OLED

Adafruit_GFX library

Adafruit_SSD1306 Library

Official STM Arduino core -> https://github.com/stm32duino/Arduino_Core_STM32
