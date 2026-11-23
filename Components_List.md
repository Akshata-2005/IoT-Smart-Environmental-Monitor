# Hardware Components

| Sl. No. | Component | Purpose |
|---|---|---|
| 1 | ESP32 Development Board | Main microcontroller |
| 2 | DHT22 Sensor | Temperature and humidity measurement |
| 3 | MQ-135 Sensor | General air-quality monitoring |
| 4 | OLED Display (0.96 inch) | Display sensor readings |
| 5 | Buzzer | Audible warning |
| 6 | LED | Visual alert |
| 7 | Resistors | Current limiting and signal conditioning |
| 8 | Breadboard | Circuit prototyping |
| 9 | Jumper Wires | Electrical connections |
| 10 | 5V Regulated Power Supply | System power source |

## Hardware Description

The ESP32 is the central controller. The DHT22 and MQ-135 collect environmental data. The OLED displays processed readings, while the buzzer and LED provide alerts. The regulated power supply provides electrical power to the circuit.

**Note:** Verify voltage compatibility before connecting modules, especially the MQ-135 analog output to the ESP32 ADC.
