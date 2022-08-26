# Conservation of energy using IoT

#### Built a roller coaster setup using conveyor belts to show the Conservation of Energy, designed using, Arduino IDE and the ESP-32 microcontroller. Implement a dashboard interface using ESP-32 camera which allows users to view the experiment live from elsewhere.

## Overview

 
 
* Ultrasonic sensor senses the distance of object every 0.3 seconds
* When the distance sensor becomes zero on the left side, clockwise conveyor belt motor is triggered.
* The object is lifted up the left ramp by conveyor belt.
* The conveyor belt stops when the object reaches the top of the left ramp. 
* The object now falls down freely on the right ramp, its distance is again sensed by the right side distance sensor
* Again when the distance sensor becomes zero, the motor of conveyor belt is triggered, but this time in anticlockwise direction. And the loop continues.
