# ESP32 Pin Connections

| Component | ESP32 Pin |
|---|---|
| DHT22 Data | GPIO 4 |
| MQ-135 Analog Output | ADC GPIO 34 |
| OLED SDA | GPIO 21 |
| OLED SCL | GPIO 22 |
| Buzzer | GPIO 25 |
| LED | GPIO 26 |
| VCC | Suitable regulated supply |
| GND | Common Ground |

**Important:** Use suitable voltage conditioning for the MQ-135 analog output. Check the specific ESP32 board and sensor module pin specifications before wiring.
