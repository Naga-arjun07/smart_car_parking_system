# 🚗 Arduino-Based Car Parking System

A smart and affordable parking system built using **Arduino**, **IR sensors**, **servo motor**, and an **I2C LCD display**. This system monitors available parking slots and automatically opens/closes a gate for vehicle entry and exit.

---

## 📦 Components Used

- Arduino UNO/Nano
- 2 × IR Sensors (Entry & Exit)
- Servo Motor (SG90/MG90S)
- I2C 16x2 LCD Display
- Jumper wires
- Breadboard or PCB
- USB cable
- Optional: Buzzer, LEDs for indicators

---

## 🔌 Wiring Overview

| Component       | Arduino Pin |
|----------------|-------------|
| IR Sensor 1     | D2          |
| IR Sensor 2     | D3          |
| Servo Motor     | D4          |
| I2C LCD SDA     | A4          |
| I2C LCD SCL     | A5          |

---

## 🧠 How It Works

- IR1 detects **vehicle entry**.
- IR2 detects **vehicle exit**.
- If a slot is available, gate opens via servo.
- After a 2-second delay, gate automatically **closes**.
- LCD displays:
  - Welcome message
  - Real-time slot availability
  - "Parking Full" if no slots remain

---

## 🧾 Arduino Code Features

- Uses `LiquidCrystal_I2C` for LCD
- Uses `Servo` library for gate control
- Slot count auto-updates
- Fully autonomous logic

---

## 🖼️ LCD Display Output

WELCOME!
Slot Left: 3

less
Copy
Edit

When full:
SORRY :(
Parking Full

yaml
Copy
Edit

---

## 📂 File Structure

Car_Parking_System/
├── Car_Parking_System_code.ino
├── README.md

yaml
Copy
Edit

---

## 📸 Demo / Video (Optional)

> 🔗 Add demo video or Tinkercad simulation link here (if available)

---

## 🔧 Future Improvements

- Add individual slot detection using more IRs or ultrasonic sensors
- Connect with Blynk/IoT dashboard
- Add automatic billing/ticketing system

---

## 📜 License

MIT License – feel free to use, modify, and share.

---

## 🙌 Credits

Developed by [Naga arjun]  
Based on the tutorial from [letsmakeprojects.com](https://letsmakeprojects.com/arduino-based-car-parking-system-with-full-project-report/)

---
