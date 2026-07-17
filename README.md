# Autonomous-maze-solving-robot
**Maze Solving Robot:** An autonomous robot that uses three ultrasonic sensors and the Left-Hand Rule algorithm to detect walls, avoid obstacles, and navigate a maze. An Arduino Nano controls the robot through an L298N motor driver.

---

## Objectives

* Navigate an unknown maze autonomously.
* Detect walls and obstacles using ultrasonic sensors.
* Apply the Left-Hand Rule algorithm for path selection.
* Reach the maze exit without human intervention.

---

## Components Used

* Arduino Nano
* L298N Motor Driver
* 3 × HC-SR04 Ultrasonic Sensors
* 2 × DC BO Motors
* Robot Chassis
* Wheels
* 12V Battery (Li-ion/LiPo)
* Power Switch
* Jumper Wires

---

## Working Principle

1. The ultrasonic sensors continuously measure distances to the left, front, and right walls.
2. The Arduino Nano processes the sensor readings.
3. The robot follows the Left-Hand Rule:

   * Turn Left if the left path is open.
   * Otherwise, move Straight if the front is clear.
   * Otherwise, turn Right if available.
   * If all paths are blocked, perform a U-turn.
4. The Arduino controls the L298N motor driver to drive the motors accordingly.
5. The process repeats until the robot reaches the maze exit.

---

## Algorithm

* Read Left, Front, and Right sensor values.
* Compare each distance with the predefined threshold.
* Apply the Left-Hand Rule decision.
* Drive the motors.
* Repeat until the destination is reached.

---

## Project Features

* Autonomous navigation
* Real-time obstacle detection
* Three-direction wall sensing
* Left-Hand Rule maze-solving algorithm
* Low-cost hardware implementation
* Easy to modify and upgrade

---

## Project Images

* Circuit Diagram
* Block Diagram
* Robot Prototype
* Flowchart
* Maze Test Setup

---

## Future Improvements

* Implement shortest-path optimization.
* Add maze mapping and memory.
* Replace ultrasonic sensors with LiDAR.
* Enable Bluetooth/Wi-Fi monitoring.
* Improve navigation using PID control.

---

## 👨‍💻 Author

**Naveen Nekar**

Electronics and Communication Engineering (ECE)

Embedded Systems Enthusiast
