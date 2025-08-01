# 💓 IoT-Based Heart Rate Monitoring System using ESP8266 & AD8232 ECG Sensor

This project demonstrates a real-time ECG and heart rate monitoring system using the **AD8232 ECG sensor** and **ESP8266 NodeMCU**, with data displayed on a **web dashboard via Blynk IoT**. It helps to measure electrical activity of the heart and monitor vitals remotely, making it ideal for personal or telehealth applications.

---

## 🔧 Hardware Used

- **ESP8266 NodeMCU (Wi-Fi Module)**
- **AD8232 ECG Sensor Module**
- **Electrodes (3-lead ECG pads)**
- **Jumper Wires**
- **USB Cable** (for programming and power)
- **Laptop/PC** (for programming via Arduino IDE)

---

## 💻 Technologies & Tools

| Component      | Usage                                  |
|----------------|------------------------------------------|
| **Arduino IDE** | Code development & uploading             |
| **C++ (Arduino)** | Language for embedded programming     |
| **Blynk IoT Platform** | Real-time ECG graph and heart rate display on mobile |
| **Google Drive** | Video hosting for project demo          |

---

## ⚙️ Features

- Real-time ECG waveform display on Blynk dashboard
- Heart rate calculation and display
- Portable and low-cost design
- Wi-Fi enabled remote monitoring

---

## 📲 Blynk Dashboard Setup

- Create a new template in **Blynk IoT** (https://blynk.cloud/)
- Add:
  - **SuperChart** (to display ECG waveform)
  - **Label** (to show BPM – Beats Per Minute)
- Link Virtual Pins used in the code:
  - ECG waveform → `V0`
  - Heart Rate → `V1`

---

## 🎬 Project Demo Video

See the full working of the system in this short demo video:

▶️ [Click here to watch the demo](https://drive.google.com/file/d/1RES0kHuNz1DL4j32gdRkUMoI1DQK3nMW/view?usp=sharing)

---

## 🛠️ Getting Started

1. **Connect the AD8232 sensor** to the NodeMCU as per below:
   - `LO+` → D1 (GPIO5)
   - `LO-` → D2 (GPIO4)
   - `OUTPUT` → A0
   - `GND` → GND
   - `3.3V` → 3.3V of NodeMCU
2. **Install Blynk and ESP8266 boards** in Arduino IDE
3. **Update credentials in code**:
   - WiFi SSID and Password
   - Blynk Auth Token
4. **Upload code** to ESP8266
5. Open **Blynk app or web dashboard** to monitor ECG and heart rate

---

## 🙌 Authors

- **Likitha Bhavana**  

