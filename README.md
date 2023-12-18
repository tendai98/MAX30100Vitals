# MAX30100 Sensor Data Monitoring 🏥📊

This project involves two main functionalities:

## `max30100.h` (MAX30100 Sensor Setup)

### Functionality:
- **`initMAX30100Sensor()`:** 🚀 Initializes the MAX30100 Sensor for data collection.
- **`validateData()`:** 🛠️ Validates the collected data (BPM and SpO2) to ensure they are within acceptable ranges.
- **`sensorUpdate()`:** 🔄 Updates sensor readings periodically and captures data for BPM and SpO2.
- **transmission:**  ↕️ The system can also send the data via the serial port using the **Serial.printf** method

## `MAX30100.ino` (Main Code)

### Functionality:
- **`setup()`:** 🎮 Sets up the MAX30100 Sensor and initializes serial communication.
- **`loop()`:** 🔄 Continuously updates sensor data and transmits it over serial if valid.
