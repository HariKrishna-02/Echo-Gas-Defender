# Echo-Gas-Defender
Echo Gas Defender is an ESP32-based safety system that monitors gas leaks (MQ2), flames (IR sensor), and high temperature (DHT22). Green LED shows SAFE status, Red LED and buzzer alerts DANGER. OLED displays real-time T/H/Gas values. Power bank compatible, room-sized coverage.

# Materials Required

ESP32 DevKit V1

MQ2 Gas Sensor Module

DHT22 Temperature & Humidity Sensor

IR Flame Sensor Module

SSD1306 OLED Display (128x64, I2C)

Active Buzzer (5V)

Red LED + Green LED

220Ω Resistors (2 nos)

Breadboard & Jumper Wires

USB Power Bank (5V)


# Connection Procedure

ESP32 → Sensors

VIN(5V)    → MQ2 VCC

3.3V       → DHT22 VCC, Flame VCC, OLED VCC

GND        → All GND

GPIO36     → MQ2 AO (Analog)

GPIO15     → MQ2 DO (Digital)

GPIO4      → DHT22 DATA

GPIO5      → Flame DO

GPIO23     → Buzzer +

GPIO19     → Red LED + (220Ω)

GPIO18     → Green LED + (220Ω)

GPIO21     → OLED SDA

GPIO22     → OLED SCL



## Credits

Created by **[JP HariKrishna Raj]**  
Project: **Echo Gas Defender**

