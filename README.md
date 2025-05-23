# 🌞 Smart Solar Tracking System

This project demonstrates the development of a **single-axis solar tracking system** using an **ESP8266**, **LDR**, and **servo motor**, with **real-time data monitoring** on **Adafruit IO**.

---

## 📌 Project Overview

Solar panels work best when they are directly facing the sun. This system automatically aligns the panel throughout the day using a Light Dependent Resistor (LDR) and a servo motor controlled by the ESP8266. LDR readings are sent to **Adafruit IO** for monitoring and performance analysis.

---

## 🎯 Objectives

- Increase solar panel efficiency by adjusting its orientation.
- Track the sun's position using a single LDR.
- Send and visualize LDR data in real-time via Adafruit IO.

---

## 🛠️ Components Used

- **ESP8266 NodeMCU**
- **LDR (Light Dependent Resistor)**
- **Servo Motor (SG90)**
- **Lithium Battery + Charging Module**
- **DC Power Supply**
- **Adafruit IO (via MQTT)**

---

## 🔧 Working Principle

1. The **LDR** senses sunlight intensity.
2. The **ESP8266** processes the analog data.
3. The **servo motor** adjusts the solar panel’s orientation.
4. LDR readings are sent to **Adafruit IO** using MQTT for real-time monitoring.

![System Diagram](images/system-diagram.png)

---

## 💻 Code

You can find the Arduino code in the `code/` folder:  
[`solar_tracker.ino`](code/solar_tracker.ino)

---

## 📊 Real-Time Monitoring

The system pushes live sensor data to [Adafruit IO](https://io.adafruit.com/). Here's an example dashboard setup:

- LDR Intensity Graph
- Servo Position Indicator
- System Logs

---

## 📈 Results

Compared to static panels, this tracker increased light exposure and efficiency. Adafruit IO helped track performance, giving insight into solar patterns and opportunities for fine-tuning.

---

## 📘 Conclusion

This **IoT-enabled Smart Solar Tracker** is a low-cost, efficient solution for maximizing solar energy harvesting. With real-time cloud integration, it’s ideal for DIY projects, research, and energy optimization.

---

## 📄 License

MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contribution

Feel free to fork, improve, or suggest changes via Pull Requests!

