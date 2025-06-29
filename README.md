# Autonomous GPS-Navigated Robotic Car

## Project Description
This project involved designing and developing a 4-wheel robotic car capable of autonomously navigating toward a specified destination using GPS coordinates and compass-based direction correction. The system integrates multiple hardware modules to achieve real-time navigation and heading stabilization.

## Key Features
- **Autonomous Navigation**: Uses real-time GPS data to determine current location and navigate toward destination coordinates.
- **Direction Stabilization**: Employs a digital compass (QMC5883L) to maintain accurate heading.
- **Wireless Communication**: Receives destination coordinates via Bluetooth from a mobile device.
- **Embedded Control**: Arduino Mega handles sensor integration and motor control logic.

## Technologies Used
- **Hardware**: Arduino Mega, Neo6M GPS Module, QMC5883L Compass, HC-06 Bluetooth Module, L298N Motor Driver, 4-wheel robotic car chassis.
- **Software**: Arduino IDE for programming and serial communication.
- **Communication Protocols**: UART for Bluetooth, I2C for compass module.

## What I Learned
- Gained hands-on experience with GPS-based navigation and compass calibration.
- Learned to integrate multiple sensors and modules for real-time decision-making.
- Improved skills in embedded systems design, sensor fusion, and autonomous robotics.

## Future Scope
- Enhance navigation accuracy using GPS filtering techniques (e.g., Kalman Filter).
- Add obstacle detection using ultrasonic or infrared sensors.
- Implement dynamic rerouting and path planning algorithms.

## Acknowledgments
Special thanks to my mentors and peers for their guidance and support throughout the project. Their insights and encouragement were instrumental in bringing this idea to life.
