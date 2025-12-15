# Real-Time Fault Detection for Power Inverter

## 📌 Project Overview
The **Real-Time Fault Detection for Power Inverter** is an IoT-based monitoring system designed to detect electrical and environmental faults in a power inverter. The system continuously monitors current, voltage, power, energy consumption, temperature, and humidity. Collected data is transmitted to a web server in real time for analysis and fault detection.

---

## 🔧 Hardware Components
- ESP8266 (NodeMCU)
- Current Sensor (via Analog Pin A0)
- DHT11 Temperature and Humidity Sensor
- Power Inverter
- Wi-Fi Network
- Cloud/Web Server

---

## 💻 Software Requirements
- Arduino IDE
- ESP8266 Board Package
- DHT Sensor Library
- ESP8266WiFi Library

---

## ⚙️ Working Principle
The ESP8266 reads current values from the analog input and calculates power and energy consumption. A DHT11 sensor measures temperature and humidity to monitor inverter operating conditions. These parameters help in identifying abnormal behavior such as overload, overheating, or environmental stress.

The system uploads real-time data to a remote web server using HTTP requests, enabling continuous monitoring and early fault detection.

---

## 📡 Parameters Monitored
- Current
- Voltage (assumed constant)
- Power
- Energy Consumption
- Temperature
- Humidity

---

## 🌐 Cloud Communication
Sensor data is sent periodically to a web server using an HTTP GET request. This allows:
- Remote monitoring
- Data logging
- Fault analysis
- Preventive maintenance

---

## 🚨 Fault Detection
Faults are identified based on abnormal readings such as:
- High current or power
- Sudden energy spikes
- High temperature
- Excessive humidity

Early detection helps prevent inverter damage and improves system reliability.

---

## 🧠 Applications
- Solar inverter monitoring
- Industrial power systems
- Smart grid applications
- Energy management systems

---

## ✅ Advantages
- Real-time monitoring
- Remote access to data
- Low-cost and efficient
- Improves inverter lifespan
- Prevents unexpected failures

---

## 🔚 Conclusion
The Real-Time Fault Detection for Power Inverter provides a reliable IoT solution for continuous inverter health monitoring. By combining electrical and environmental sensing with cloud connectivity, the system enhances safety, efficiency, and maintenance planning.

---

## 👨‍💻 Developed Using
- Embedded C
- Arduino IDE
- IoT and Cloud Technology
