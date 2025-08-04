Voice Controlled Vacuum Cleaner Robot

A smart Arduino-based robotic vacuum cleaner that can be controlled wirelessly via Bluetooth voice commands or Bluetooth app button controls. The robot uses four DC motors for movement and can respond to directional commands such as forward, backward, left, right, and stop using a mobile phone.


🚀 Features

- 🔊 **Voice control** via Bluetooth using mobile apps  
- 🎮 **App-based remote control** (using arrow/button commands)  
- ⚡ Powered by **Arduino Uno + Adafruit Motor Shield**  
- 🔄 Supports movement in all directions (forward, backward, left, right)  
- 🧹 Can be attached to a vacuum suction motor
  

 🛠 Hardware Components

| Component                      | Quantity |
|--------------------------------|----------|
| Arduino Uno                    | 1        |
| Adafruit Motor Shield (L293D)  | 1        |
| DC Motors (for wheels)         | 4        |
| HC-05 / HC-06 Bluetooth Module | 1        |
| Vacuum Motor (optional)        | 1        |
| Power Supply                   | 1        |


📱 Control Input

| Mode           | Input Character | Action     |
|----------------|-----------------|------------|
| Bluetooth App  | U               | Forward    |
| Bluetooth App  | D               | Backward   |
| Bluetooth App  | L               | Left       |
| Bluetooth App  | R               | Right      |
| Bluetooth App  | S               | Stop       |
| Voice Control  | ^               | Forward    |
| Voice Control  | -               | Backward   |
| Voice Control  | <               | Left       |
| Voice Control  | >               | Right      |
| Voice Control  | *               | Stop       |


📂 File Structure
vacuum_cleaner/

├── vacuum_cleaner.ino → Arduino source code


🔧 How to Upload Code

1. Open Arduino IDE  
2. Connect your Arduino Uno via USB  
3. Select: **Board → Arduino Uno**  
4. Select: **Tools → Port → (COM Port)**  
5. Open `vacuum_cleaner.ino`  
6. Click **Upload (→)** button  


📲 Recommended Mobile Apps

- Arduino Bluetooth Controller
- BT Voice Control for Arduino
- Bluetooth Terminal


📌 Future Improvements

- Add obstacle detection using Ultrasonic sensor  
- Connect vacuum suction motor on pin 10  
- Add IR remote control support
  
