# 🤖 Arduino 4-Wheel Line Following Robot

A four-wheel autonomous line-following robot built using an Arduino Uno, an L293D motor driver, and two infrared (IR) line tracking sensors. This project demonstrates the fundamentals of embedded systems, robotics, and motor control.

---
## 📖 Overview

This robot detects a black line on a white surface using two IR sensors and adjusts the speed and direction of its motors to follow the path automatically.

This project was created to learn:

- Arduino programming
- Motor driver control (L293D)
- Digital sensor interfacing
- Differential drive robots
- Embedded systems fundamentals

---

## ✨ Features

- 🚗 Four-wheel differential drive
- 🔍 Dual IR line tracking sensors
- ⚡ PWM motor speed control
- 🧠 Autonomous line following
- 🔧 Modular hardware design
- 📚 Beginner-friendly project

---

## 🛠 Hardware

| Component | Quantity |
|-----------|---------:|
| Arduino Uno | 1 |
| L293D Motor Driver IC | 1 |
| TT DC Motors | 4 |
| Wheels | 4 |
| IR Line Tracking Sensors | 2 |
| Breadboard | 1 |
| Battery Pack (Recommended: 2×18650 or 6×AA) | 1 |
| Jumper Wires | Several |
| Chassis | 1 |

---

## 📦 Software

- Arduino IDE
- Arduino AVR Boards
- Tinkercad (for simulation)

---

## 🔌 Wiring

### Arduino Pins

| Arduino | Function |
|----------|----------|
| D5 | Motor Enable A (PWM) |
| D6 | Motor Enable B (PWM) |
| D7 | Motor A IN1 |
| D8 | Motor A IN2 |
| D9 | Motor B IN3 |
| D10 | Motor B IN4 |
| D2 | Left IR Sensor |
| D3 | Right IR Sensor |

---

## 🚀 Getting Started

1. Clone this repository.

```bash
git clone https://github.com/yourusername/LineFollowerRobot.git
```

2. Open the project in Arduino IDE.

3. Connect the Arduino Uno.

4. Upload the sketch.

5. Place the robot on a line track.

6. Turn on the power.

The robot should automatically follow the line.

---

## 🧠 How It Works

The robot continuously reads two IR sensors.

| Left Sensor | Right Sensor | Action |
|-------------|--------------|--------|
| White | White | Move Forward |
| Black | White | Turn Left |
| White | Black | Turn Right |
| Black | Black | Stop / Recenter |

The Arduino processes the sensor inputs and controls the L293D motor driver to steer the robot.

---

## 🎯 Future Improvements

- PID line following
- Bluetooth control
- ESP32 WiFi remote monitoring
- Obstacle avoidance
- OLED display
- Battery voltage monitoring
- Encoder feedback
- Maze solving algorithm

---

## 📚 What I Learned

Through this project I learned:

- Arduino programming
- Reading digital sensors
- Motor driver control
- PWM speed control
- Robot navigation
- Embedded systems debugging
- Basic electronics

---

## 🤝 Contributing

Pull requests are welcome.

If you have suggestions or improvements, feel free to open an issue.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Author: MrBaconPresident

Student interested in Robotics, Embedded Systems, and Electrical Engineering.

GitHub: https://github.com/hoanghaiteen12-ship-it
