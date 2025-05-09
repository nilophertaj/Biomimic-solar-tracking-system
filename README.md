# 🌻 Biomimic Sunflower-Inspired Solar Tracker

This project is a **biomimicry-based solar tracking system** designed to imitate a sunflower's behavior by intelligently following sunlight using **servo and stepper motors**, and converting sunlight into electricity using solar panels.

## 🚀 Project Highlights

- 🌞 **Triple-petal solar panels** arranged like a blooming sunflower
- 🎯 **Dual-axis tracking** using vertical and horizontal servo motors
- 🧠 **Light-sensing with LDRs** to detect and follow the sun’s direction
- 🌀 **Stepper motor for rotation** at the base
- ♻️ **Energy conversion** with real-time tracking for efficient power generation
- 🤖 **Biomimic Design**: Mimics a flower that opens and follows light, inspired by nature

## 📸 Demo

![Solar Tracker](images/demo_photo.jpg)

## 📽️ Video

Watch the project in action:
[Demo Video]("C:\Users\nilop\Documents\solartracker.mp4")

## ⚙️ Hardware Components

| Component           | Description                      |
|--------------------|----------------------------------|
| Arduino Uno/ESP32  | Microcontroller unit             |
| 3x LDRs            | Light sensors                    |
| 2x Servo Motors    | For tilt (vertical & horizontal) |
| 1x Stepper Motor   | For rotational movement          |
| Solar Panels       | Energy harvesting                |
| Battery + Regulator| Power supply                     |
| 3D Printed Frame   | Flower-inspired body             |

## 🔌 Wiring Diagram

See [`schematics/wiring_diagram.png`](schematics/wiring_diagram.png)

## 📂 Project Structure

- `Arduino_Code/`: Main tracking algorithm
- `CAD_Designs/`: Petal design and motor mounts
- `images/`: Project photos
- `schematics/`: Wiring diagrams and PCB (if any)

## 🧠 Future Enhancements

- 🌦️ Add a **rain/temperature sensor** to close petals in bad weather
- 📱 IoT integration: Send data to a mobile dashboard
- 🔋 Power storage monitoring with battery health feedback
- 🌍 GPS-based backup tracking in low-light environments

## 🛠️ How to Build

1. Assemble the 3D-printed flower model
2. Mount solar panels on each petal
3. Connect servos and stepper motors as per schematic
4. Upload `solar_tracker.ino` to Arduino
5. Power the system with a battery or regulated supply

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgements

- Inspired by nature 🌻
- Special thanks to open-source communities and biomimic design enthusiasts

---
