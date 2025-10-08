Line Follower Robot<br>
Description-<br>
The Line Follower Robot is an autonomous mobile robot that follows a path drawn on the ground using infrared (IR) sensors. It detects the difference in reflectivity between the line and the surface and adjusts its movement accordingly to stay on track.<br>
This project demonstrates the core concepts of robotics — including sensor integration, real-time decision-making, and feedback control.<br>

Working Principle-<br>
The IR sensors continuously sense the color contrast between the line (usually black) and the surface (usually white).
Based on the sensor readings, the microcontroller determines the robot’s position relative to the path.
Motor speeds are adjusted accordingly — turning left, right, or moving straight — to maintain alignment with the line.

Hardware Used:<br>
Arduino Uno (or compatible microcontroller)<br>
IR Sensor Array<br>
L298N Motor Driver Module<br>
DC Motors and Wheels<br>
Chassis and Battery Pack<br>

Software Used:<br>
Arduino IDE<br>
Embedded C/C++<br>

Features:<br>
Real-time path detection and correction<br>
Smooth and accurate navigation on curves and intersections<br>
Adjustable sensor sensitivity for different track surfaces<br>
Easy to calibrate and modify<br>
