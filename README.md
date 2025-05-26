# IOT_research


---

**Smart Greenhouse Environment Automation Using IoT**

```markdown
# Smart Greenhouse Environment Automation Using IoT

This project presents a smart greenhouse automation system using Internet of Things (IoT) technologies. It compares two hardware platforms—Netduino and MicaZ—for real-time monitoring and control of environmental factors like temperature, humidity, light, and soil moisture.

## 📌 Key Features
- Automated environmental control (ventilation, irrigation, lighting)
- Real-time sensor data collection and cloud sync
- Comparison of two platforms: Netduino (active control) vs. MicaZ (passive sensing)
- Remote access via mobile/web interface

## 🧰 Technologies & Hardware
- Netduino 3 (WiFi-based, high processing power)
- MicaZ (low-power ZigBee-based sensor node)
- Sensors: DHT11, YL69, GL5528
- TinyOS and C#/.NET Micro Framework
- Cloud communication via ADO.NET

## 📊 Comparison Highlights
| Feature          | Netduino                | MicaZ                  |
|------------------|-------------------------|-------------------------|
| Processing Power | High (32-bit ARM)       | Low (8-bit AVR)         |
| Power Usage      | High                    | Ultra-low              |
| Control Support  | Full actuator control   | Monitoring only         |
| Programming      | C#, Visual Studio       | nesC, TinyOS           |

## 🚀 Getting Started
1. Connect sensors to Netduino or MicaZ boards.
2. Set up cloud service or local database to store readings.
3. Upload code to the respective boards.
4. Monitor and control using the provided web/mobile dashboard.

## 📄 License
This project was completed as part of a university research paper. For academic or non-commercial use only.
