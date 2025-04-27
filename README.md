# OLED_Display_With_ESP32
0.96'' OLED Display Setup with ESP32

# OLED Display With ESP32 Project

Demonstrates SSD1306 OLED display features using ESP32.

## Features
- All standard display tests
- Optimized for ESP32
- Custom "HMS_Tech Subs..!" message

## Hardware
- ESP32 Dev Board
- SSD1306 OLED (128×64)
- Wiring:
  - SDA → GPIO 21 (default)
  - SCL → GPIO 22 (default)
  - VCC → 3.3V
  - GND → GND

## Libraries
- Adafruit_GFX
- Adafruit_SSD1306
- Wire (built-in)

## Installation
1. Clone this repo
2. Open in Arduino IDE or PlatformIO
3. Install libraries via Library Manager
4. Upload to ESP32

## PlatformIO
If using PlatformIO, add to `platformio.ini`:
```ini
[env:esp32dev]
platform = espressif32
board = esp32dev
framework = arduino
lib_deps = 
    adafruit/Adafruit GFX Library@^1.11.5
    adafruit/Adafruit SSD1306@^2.5.7
