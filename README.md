# Autonomous 4WD Line Following Robot

## 🚀 Overview
This project is an autonomous line following robot built using Arduino Uno, TCRT5000 IR sensors, and L298N motor driver. The robot follows a black line on a white surface and provides real-time audio-visual feedback using LEDs and a buzzer.

---

## 📸 Project Image
![image 1](https://github.com/user-attachments/assets/a2ad30e9-47c1-4f88-84df-1d08b1cd01cf)

---

## 🔧 Features
- 4WD robot for better stability
- Real-time line detection using IR sensors
- Motor control using L298N driver
- LED and buzzer feedback
- Simple and modular design

---

## 🧰 Components Used
- Arduino Uno  
- TCRT5000 IR Sensors (2)  
- L298N Motor Driver  
- DC Motors (4WD)  
- 12V Battery  
- LEDs and Buzzer  

---

## ⚙️ Working Principle
- Black surface → Sensor = 1  
- White surface → Sensor = 0  

| Left Sensor | Right Sensor | Action       |
|------------|-------------|-------------|
| 1          | 1           | Forward     |
| 1          | 0           | Turn Left   |
| 0          | 1           | Turn Right  |
| 0          | 0           | Stop        |

---

## 🎥 Demo Video
https://youtu.be/0k2JIg4Dxvs

---

## 📂 Project Structure

```
line-following-robot/
│
├── code/
│   └── line_follower.ino
├──diagrams/
├── images/
└── docs/
```

---

## 🚀 Future Improvements
- PID control for smoother movement  
- Obstacle detection  
- Bluetooth control  

---

## 👨‍💻 Author
Eshwar Prasad Y
| ECE | Embedded Systems
