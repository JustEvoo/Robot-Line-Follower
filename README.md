# Robot-Line-Follower

A robot line follower is an autonomous mobile robot designed to follow a specific path or track marked by a visible line on a contrasting surface.

## Features
*   **Autonomous Navigation**: Continuously tracks and follows a line using sensor input.
*   **Real-time Processing**: Rapidly processes sensor data to adjust motor speeds and maintain the path.
*   **Adjustable Calibration**: Sensor thresholds can be modified in the code for different track colors and lighting conditions.

## Hardware Requirements
To build this robot, you will need the following core components:
*   Microcontroller (e.g., Arduino Uno or Nano)
*   Motor Driver Module (e.g., L298N or L293D)
*   Infrared (IR) Line Sensors (typically 2 or more, e.g., TCRT5000)
*   2x DC Gear Motors with Wheels
*   Robot Chassis and Caster Wheel
*   Power Supply (e.g., Battery pack)
*   Jumper Wires and Breadboard

## Software Requirements
*   [Arduino IDE](https://www.arduino.cc/en/software) (if utilizing an Arduino-compatible board)

## Wiring Guide
*(Note: Replace the pin numbers below with the actual pins used in your specific build).*

*   **Left IR Sensor**: Connect to digital pin X
*   **Right IR Sensor**: Connect to digital pin Y
*   **Motor Driver**: Connect IN1, IN2, IN3, and IN4 to digital pins A, B, C, and D.

## Installation and Setup
1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/JustEvoo/Robot-Line-Follower.git](https://github.com/JustEvoo/Robot-Line-Follower.git)
    ```
2.  Open the source code file in your IDE.
3.  Verify that the pin definitions in the code perfectly match your physical wiring setup.
4.  Connect your microcontroller to your computer and upload the code.
5.  Place the robot on a clear, high-contrast track (e.g., a thick black line on a white background) and turn on the power supply.

## License
This project is open-source. Feel free to modify and use it for your own robotics projects.
