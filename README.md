# line-following-robot

This project implements a **Line Following Robot** using **IR sensors** and **DC motors**, controlled via an **Arduino Uno**. The robot follows a black line on a white surface by adjusting motor speeds and directions based on sensor input.

The robot uses **two IR sensors** positioned on the left and right to detect the black line. Based on the sensor input, the robot decides whether to go straight, turn left, turn right, or stop.

| Left IR Sensor | Right IR Sensor | Robot Action     |
|----------------|------------------|------------------|
| LOW            | LOW              | Move Forward     |
| HIGH           | LOW              | Turn Left        |
| LOW            | HIGH             | Turn Right       |
| HIGH           | HIGH             | Stop             |
