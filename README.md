**Name**: SNEHA KHEDEKAR  
**Company**: CODTECH IT SOLUTIONS  
**ID**: CT08DS147  
**Domain**: EMBEDDED SYSTEMS  
**Duration**: NOVEMBER 30th, 2024 to DECEMBER 30th, 2024  
**Mentor**: NEELA SANTHOSH

### Overview of the Project
The project involves monitoring temperature and humidity levels using a DHT sensor (DHT11 or DHT22) with an Arduino microcontroller. The objective is to learn how to interface the DHT sensor with the Arduino platform and collect real-time temperature and humidity data. The project demonstrates how to read sensor data, process it, and display the values on an LCD or Serial Monitor for further analysis. This is a crucial step toward understanding how environmental sensors work in embedded systems.


### Project: Temperature and Humidity Monitoring with DHT Sensor

This project uses an Arduino board (e.g., Arduino Uno) in combination with a DHT sensor (DHT11/DHT22) to measure temperature and humidity in real-time. The sensor data is then displayed on an LCD screen or sent to a Serial Monitor for user observation. The project introduces the concepts of sensor interfacing, data processing, and real-time display/output using basic embedded systems components.

---

### Objective
The primary objectives of this project are to:

- Understand the working of the DHT sensor and how to interface it with the Arduino platform.
- Learn to write and execute a program (Arduino sketch) that reads data from the DHT sensor and outputs it on a display or Serial Monitor.
- Gain practical experience in embedded systems concepts such as sensor integration, data acquisition, and real-time output.
- Implement simple error handling mechanisms to ensure accurate sensor readings.

---

### Key Activities

#### 1. **Setup Arduino IDE:**
   - Installed and configured the Arduino IDE on the system.
   - Set up the Arduino Uno board as the platform for this project.
   - Added necessary libraries to interface with the DHT sensor (e.g., `DHT.h` library).

#### 2. **DHT Sensor Circuit Design:**
   - Designed the hardware circuit by connecting the DHT sensor to the Arduino board:
     - VCC pin of the DHT sensor to 5V on Arduino.
     - GND pin of the DHT sensor to GND on Arduino.
     - Data pin of the DHT sensor to a designated digital I/O pin on Arduino (e.g., pin 2).
     - Used a pull-up resistor (typically 10kΩ) between the data pin and VCC to ensure stable data transmission.

#### 3. **Writing the Arduino Sketch:**
   - Wrote the Arduino code to read data from the DHT sensor:
     - Initialized the DHT sensor using the `DHT.begin()` function.
     - Set the sensor to read temperature and humidity values using `DHT.readTemperature()` and `DHT.readHumidity()` functions.
     - Printed the temperature and humidity readings to the Serial Monitor using `Serial.print()` and `Serial.println()`.

#### 4. **Uploading Code to the Arduino:**
   - Uploaded the Arduino sketch to the board using the Arduino IDE.
   - Monitored the Serial Monitor to observe the real-time temperature and humidity readings.

#### 5. **Troubleshooting:**
   - Ensured proper wiring and connections to the DHT sensor.
   - Verified that the correct sensor type (DHT11 or DHT22) was specified in the code.
   - Handled errors, such as "Failed to read from DHT sensor," by re-checking sensor wiring and the sensor's operational state.

#### 6. **Testing and Debugging:**
   - Ran multiple tests to ensure that the readings were accurate and consistent.
   - Made adjustments to the delay times to balance the refresh rate of sensor readings.
   - Verified data accuracy by cross-checking with external thermometers and hygrometers.

---

### Technologies Used

- **Arduino IDE**: For writing and uploading the code to the Arduino board.
- **Arduino Uno**: A microcontroller board used to interface with the DHT sensor.
- **DHT11/DHT22 Sensor**: The temperature and humidity sensor used to capture environmental data.
- **LCD Screen **: To display temperature and humidity readings locally, or Serial Monitor for real-time feedback.
- **C++**: The programming language used for writing the Arduino sketch.

---

### Key Insight

This project provided a practical introduction to working with environmental sensors in embedded systems. Key insights gained include:

- **Sensor Interfacing**: The ability to interface sensors with microcontrollers allows for a wide range of applications, from monitoring environmental conditions to controlling systems based on sensor input.
- **Data Acquisition**: Reading real-time data from sensors and displaying it is a foundational skill in embedded systems. This project taught how to handle raw data and process it into a usable format.
- **Error Handling**: Ensuring that sensor data is read correctly, and implementing error-checking mechanisms are vital skills. This project included simple error handling to recover from failed sensor readings.
- **Real-time Display**: Displaying sensor data in real-time provides valuable feedback for users, and the ability to troubleshoot hardware or software issues effectively.
- **Practical Application**: This setup has broad applications, such as in weather stations, home automation systems, and industrial monitoring systems.

