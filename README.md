🚗 Smart Airport Car Parking Management System 🚗
Overview
This project tackles parking congestion at airports by providing real-time parking slot availability, monitoring environmental conditions, and automating parking charges using IoT and embedded systems.

Problem Statement
Airports often face parking delays, causing inconvenience to travelers. This system helps reduce parking time, automate entry/exit, and enhance the user experience.

Solution Concept
Real-time Slot Detection (Ultrasonic Sensors):

<7 cm: Slot occupied.
7-15 cm: Slot in use.
>15 cm: Slot available.
Automated Entry/Exit (RFID): Entry and exit using RFID tags for easy vehicle tracking.

Environmental Monitoring (DHT11): Tracks temperature and humidity, with fire detection when temperature exceeds 70°C.

Servo Motor Gate Control: Automatically opens/closes gates for authorized vehicles.

Parking Charge Calculation: 1 rupee per minute, based on RFID tag entry/exit.

Firebase Integration: Stores parking and environmental data, accessible remotely.

Parking Status Display (16x2 LCD): Shows slot availability at the entrance.

Full Parking Prevention: Prevents new vehicle entry when the parking lot is full.

Component Functionality
Arduino UNO: Controls sensor data and manages the system.
NodeMCU ESP8266: Uploads data to Firebase for remote updates.
Ultrasonic Sensors: Detect vehicle presence in each parking spot.
RFID Module: Automates entry/exit, calculates parking charges.
DHT11 Sensor: Monitors temperature and humidity.
Servo Motor: Controls gate for authorized vehicle access.
16x2 LCD (I2C): Displays real-time slot availability.
Firebase: Stores real-time parking data for monitoring.
Tech Stack
Hardware: Arduino UNO, NodeMCU ESP8266
Sensors: Ultrasonic, RFID, DHT11
Servo Motor: Gate control
Display: 16x2 LCD with I2C
Database: Firebase (cloud data storage)
Key Benefits
✅ Reduces parking search time.
✅ Automates entry/exit and calculates parking charges.
✅ Provides real-time parking management.
✅ Monitors environmental conditions with fire alerts.
✅ Prevents entry when parking is full.
Conclusion
This project demonstrates my passion for solving real-world problems using embedded systems and IoT. Developed in just 24 hours, it integrates Arduino, NodeMCU, and Firebase to create an efficient and smart airport parking solution.

Feel free to connect for more details or to discuss IoT, embedded systems, and innovative solutions!
