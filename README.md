# Room-Stats-Node

BME680 environmental sensor to measure temperature, humidity, atmospheric pressure, and VOC gas levels. The system architecture includes an STM32 microcontroller for data acquisition and processing, and an ESP32 module for wireless communication over Wi-Fi.

Hardware Components:
- MAIN Board: STM32F446RE (NUCLEO-F446RE)
- Wireless Communication Board: ESP-WROOM-32
- Sensor: BME680 Digital Temperature Humidity Sensor Module
- Display: TBD

Interfaces:
- Sensor to STM32: SPI
- STM32 to ESP32: UART
- ESP32 to Wi-Fi: Wireless Communication

Drivers:
- Hal Drivers
- BME68x_SensorAPI (boschsensors) for BME680
