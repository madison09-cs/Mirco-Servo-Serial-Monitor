# 🔄 Micro Servo with Serial Monitor

A beginner-friendly Arduino project that allows real-time control of a **micro servo motor** using the **Serial Monitor**. Send commands like `"left"`, `"center"`, or `"right"` — or just type angles like `0`, `90`, or `180` — to move the servo to precise positions.

---

## 📝 Description

**Micro Servo with Serial Monitor** is an interactive project where you can control a servo motor via the **Serial Monitor** in the Arduino IDE. The servo rotates to preset angles (0°, 90°, or 180°) based on either numeric input or predefined command words such as:

- `left` → 0°
- `center` → 90°
- `right` → 180°

This is a great way to learn about **serial input**, **servo control**, and how to map text-based commands to mechanical motion.

---

## 🔧 Components Used

| Component               | Quantity |
|-------------------------|----------|
| Arduino Uno R3          | 1        |
| Micro Servo Motor       | 1        |
| Breadboard              | 1        |
| Jumper Wires / Cables   | Several  |
| USB Cable (for Arduino IDE) | 1     |

---

## 🚀 Installation & Setup

1. **Circuit Setup**:
   - Servo **Signal** wire (orange or yellow) → Digital Pin 9
   - Servo **VCC** (red) → 5V on Arduino
   - Servo **GND** (brown or black) → GND on Arduino

2. **Upload the Code**:
   - Open the Arduino IDE.
   - Connect your Arduino Uno via USB.
   - Upload the sketch to the board.
   - Ensure the correct board and COM port are selected under the **Tools** menu.

3. **Use the Serial Monitor**:
   - Open the Serial Monitor from the top-right corner of the Arduino IDE.
   - Set the baud rate to **9600**.
   - Enter one of the following commands and press enter:
     - `left` or `0`
     - `center` or `90`
     - `right` or `180`

---

## ⚙️ How It Works

- The Arduino listens to serial input through the Serial Monitor.
- It reads either a number (`0`, `90`, `180`) or a command word (`left`, `center`, `right`).
- Based on the input, it sends a signal to the servo to rotate to the corresponding angle.
- This system maps readable commands to specific mechanical positions, similar to interfaces in robotics or automation.

---

## 💼 Portfolio

Explore more projects and documentation here:  
🔗 [My Portfolio](https://sites.google.com/d/1kRYFgoPpI5KiRHlfU4u9C--i8z4OA6I5/p/1_ZLDAirpPNf5aijgyz-LQdDFrC5D1Gd2/edit)

---

## 🔬 Simulation

Try the project online using **Tinkercad**:  
▶️ [Tinkercad Simulation - Servo Motors Serial Control](https://www.tinkercad.com/things/7SYizRDpveM-servo-motors-serial-control)

---

## 🙌 Credits

- Project by **[Madison Diggs]**
- Powered by **Arduino Uno R3**
- Inspired by real-world robotics and automation input systems

---

## 📄 License

This project is open-source and available under the Code in Schools.

---
