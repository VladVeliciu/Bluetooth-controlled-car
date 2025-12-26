# Bluetooth-Controlled Car

Arduino-based car controlled via smartphone through **Bluetooth**, with basic autonomous features.  
The system integrates distance and light sensors to improve safety and adapt to the environment.

**Main features:**
- Remote control via HC-05 Bluetooth module (F/B/L/R/S commands)
- Obstacle detection (front & back) with HC-SR04 ultrasonic sensors
- Automatic braking & warning LEDs when obstacle < 30 cm
- Light sensor (photoresistor) controls headlights and taillights
- L298N H-bridge used for 4 DC motor control (direction & motion)

**Technologies & components:**
- Arduino Uno, Bluetooth HC-05, HC-SR04 sensors
- L298N motor driver, photoresistor, LEDs
- Power: 9V for MCU, 12V for motors

Code: Arduino C/C++ (`code.ino`)  
Documentation included in repository (PDF)
