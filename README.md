Line Follower Robot
Description-
The Line Follower Robot is an autonomous mobile robot that follows a path drawn on the ground using infrared (IR) sensors. It detects the difference in reflectivity between the line and the surface and adjusts its movement accordingly to stay on track.
This project demonstrates the core concepts of robotics — including sensor integration, real-time decision-making, and feedback control.

Working Principle-
The IR sensors continuously sense the color contrast between the line (usually black) and the surface (usually white).
Based on the sensor readings, the microcontroller determines the robot’s position relative to the path.
Motor speeds are adjusted accordingly — turning left, right, or moving straight — to maintain alignment with the line.

Hardware Used:
Arduino Uno (or compatible microcontroller)
IR Sensor Array
L298N Motor Driver Module
DC Motors and Wheels
Chassis and Battery Pack

Software Used:
Arduino IDE
Embedded C/C++

Features:
Real-time path detection and correction
Smooth and accurate navigation on curves and intersections
Adjustable sensor sensitivity for different track surfaces
Easy to calibrate and modify
