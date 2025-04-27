# 🌋 Landslide Monitoring System via Bluetooth & Mobile App

A real-time landslide monitoring system that uses sensors to detect soil movement and sends alerts to a mobile application via Bluetooth. The system aims to enhance early warning and disaster management for landslide-prone areas.

---

## 🚀 Features
- 🛰️ Real-time soil movement and vibration detection.
- 📲 Wireless data transmission to a mobile app via Bluetooth (e.g., HC-05 module).
- 📢 Instant alert notification on mobile devices.
- 🔋 Low power consumption and portable system.

---

## ⚙️ Components Used
- **Microcontroller**: Arduino Uno
- **Sensors**: 
  - Vibration Sensor (SW-420) / Accelerometer (like MPU6050)
  - Optional: Soil moisture sensor
- **Bluetooth Module**: HC-05
- **Power Supply**: 9V Battery / Rechargeable battery pack
- **Mobile App**: Custom-built or generic Bluetooth Terminal app
- **Miscellaneous**: Jumper wires, breadboard, resistors

---

## 🛠️ How It Works
1. **Sense**: Sensors continuously monitor ground vibrations or soil movement.
2. **Process**: Arduino processes the sensor data and detects anomalies.
3. **Transmit**: Upon detecting unusual activity, Arduino sends a warning signal via the HC-05 Bluetooth module.
4. **Notify**: The mobile app receives and displays an immediate alert.

---

## 📚 Applications
- Early warning system for landslides in hilly and mountainous regions.
- Disaster management and rescue operations.
- Can be adapted for earthquake monitoring or flood alerts.



