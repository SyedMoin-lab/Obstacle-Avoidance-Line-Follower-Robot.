# Obstacle-Avoidance-Line-Follower-Robot.



This repository contains the code and resources for an Arduino-based robot capable of both obstacle avoidance and line following functionalities. The project integrates various components and sensors to achieve autonomous navigation and obstacle detection.

## Project Overview

### Parts List:
1. **Arduino Nano**: Used as the main microcontroller board.
2. **L298N Motor Driver**: Controls the motors used in the robot.
3. **TT Gear Motor (4x)**: Motors for driving the robot.
4. **Rubber Wheels (4x)**: Wheels for movement and traction.
5. **IR Sensor (2x)**: Infrared sensors for line following.
6. **Ultrasonic Sensor**: Used for obstacle detection.
7. **18650 Li-ion Battery (2x)**: Power source for the robot.
8. **Battery Holder**: To secure the batteries in place.
9. **5mm Acrylic Sheet**: Material for the robot chassis.

### Functionality

The robot is designed to accomplish two main functionalities:

1. **Obstacle Avoidance**: Utilizes the ultrasonic sensor to detect obstacles in the robot's path. It navigates around obstacles to avoid collisions.
2. **Line Following**: Employs IR sensors to follow a predefined path marked by a line on the surface.

## Repository Structure

- **/src**: Contains the source code for the robot's behavior, including obstacle avoidance and line following algorithms.
- **/documentation**: Includes project documentation, schematics, and assembly instructions.
- **/examples**: Code examples or demonstrations showcasing specific functionalities.

## Getting Started

To recreate or further develop this robot, follow these steps:

1. **Assembly**: Construct the robot chassis using the 5mm acrylic sheet and mount all the components according to the provided schematics (located in the /documentation folder).
2. **Wiring**: Connect the components as described in the schematics and ensure proper connections between the sensors, motors, and the Arduino Nano.
3. **Code Upload**: Upload the code from the /src folder to the Arduino Nano using the Arduino IDE or any compatible development environment.

## Contributing

Contributions to this project are welcome! Feel free to fork this repository, make improvements, and submit a pull request. Please adhere to the guidelines outlined in CONTRIBUTING.md.

## License

This project is licensed under the [MIT License](LICENSE).
