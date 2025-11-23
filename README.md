# IOT_research

## 💡 Smart Greenhouse Environment Automation Using IoT

This project presents a **smart greenhouse automation system** using Internet of Things (IoT) technologies. It compares two hardware platforms—**Netduino** and **MicaZ**—for real-time monitoring and controlling environmental factors like temperature, humidity, light, and soil moisture.

---

## 📌 Key Features
* **Automated environmental control** (ventilation, irrigation, lighting)
* **Real-time sensor data collection** and cloud sync
* **Comparison of two platforms**: Netduino (active control) vs. MicaZ (passive sensing)
* **Remote access** via mobile/web interface

---

## 🧰 Technologies & Hardware
* **Microcontrollers**: Netduino 3 (WiFi-based) and MicaZ (ZigBee-based sensor node)
* **Sensors**: DHT11 (Temperature/Humidity), YL69 (Soil Moisture), GL5528 (Light)
* **Programming**: TinyOS and C#/.NET Micro Framework
* **Cloud Communication**: ADO.NET

---

## 📊 Comparison Highlights

| Feature | Netduino | MicaZ |
| :--- | :--- | :--- |
| **Processing Power** | High (32-bit ARM) | Low (8-bit AVR) |
| **Power Usage** | High | Ultra-low |
| **Control Support** | Full actuator control (Active) | Monitoring only (Passive) |
| **Programming** | C\#, Visual Studio | nesC, TinyOS |

---

## 🚀 Getting Started
1.  Connect sensors (DHT11, YL69, GL5528) to your chosen board (**Netduino** or **MicaZ**).
2.  Set up a cloud service or a local database to store real-time sensor readings.
3.  Upload the corresponding code to the respective boards.
4.  Monitor and control the greenhouse environment using the provided web/mobile dashboard.

---

## 📄 License
This project was completed as part of a university research paper, for **academic or non-commercial use only**.
