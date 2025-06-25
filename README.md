# Smart Room Monitor 🏠

An Arduino-based project designed to monitor a room’s environmental and motion status using multiple sensors. Built to explore real-world embedded systems and home automation.

---

## 🧰 Components Used

- Arduino UNO
- PIR Motion Sensor (HC-SR501)
- DHT11 (Temperature & Humidity Sensor)
- Photoresistor (LDR)
- LED
- Breadboard + Jumper Wires

---

## 🔌 Circuit Overview

- **Motion Detection:** PIR sensor triggers LED when motion is detected.
- **Environmental Monitoring:** DHT11 outputs temperature and humidity.
- **Light Level Detection:** Photoresistor reads room brightness.
- All data is printed to Serial Monitor (optional: OLED or remote logging).

---

## 💻 Features

- Real-time motion alerts via onboard LED
- Serial monitoring of room environment:
  - Temperature (°C)
  - Humidity (%)
  - Light Intensity (analog value)
- Low-cost and beginner-friendly setup

---

## 📋 How to Use

1. Wire up the components as shown in `circuit_diagram.png`
2. Upload the code from `smart_room_monitor.ino`
3. Open the Serial Monitor (9600 baud)
4. Trigger motion, light changes, or heat to see live readings

---



