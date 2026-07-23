1. Introduction

     1.1 Project Description

Floods are one of the most common natural disasters in many regions, especially in countries like Bangladesh. During such disasters, many people become stranded in areas that are difficult to access. This project introduces a floating robotic system designed to assist in detecting human presence in flooded environments.
The robot is capable of floating on water using a lightweight base and can move using DC motors. It uses sensors such as a PIR sensor to detect human motion and an ultrasonic sensor to detect obstacles. When a human is detected, the system provides an alert using LED and a buzzer.
This project demonstrates the practical application of robotics, embedded systems and sensor integration using Arduino.


     1.2 Objectives

The main objectives of this project are:
•	To design and develop a floating robot capable of operating in water environments.
•	To detect human presence using sensors.
•	To provide alert signals (visual and sound) for rescue operations.
•	To implement a low cost and efficient solution using Arduino.
•	To understand real world applications of robotics in disaster management.
•	To enhance teamwork and problem solving skills.

     1.3 Problem Statement

Flood situations create severe challenges for rescue teams. People often get trapped in isolated areas where manual search becomes dangerous, slow and inefficient. Visibility is often low and the affected areas may be inaccessible by traditional vehicles.
This project aims to address these challenges by developing a floating robot that can move across water surfaces and detect human presence. The robot can help rescuers quickly identify affected individuals and take necessary actions, thereby improving rescue efficiency and reducing risks.

2. Components Used

The following components were used to build the system:


     2.1 Hardware Components

1.	Arduino Uno and USB Cable: Main microcontroller used to control the system
2.	Ultrasonic Sensor (HC-SR04): Used to measure distance and detect obstacles
3.	PIR Sensor (HC-SR501): Detects human motion
4.	L298N Dual H-Bridge Motor Driver Module: Controls DC motors
5.	DC Motors: Used for movement of the robot
6.	LED (Red): Indicate system status
7.	Active Buzzer: Provides sound alert when human is detected
8.	Li-ion (18650) Battery: Power source for the system
9.	Battery Holder: Holds and connects the battery
10.	Breadboard: For circuit connections
11.	Jumper Wires: For connecting components used Male to Male and Male to Female wires.
12.	Resistor (220 Ohm): For protecting devices like LED by limiting excess current.
13.	Switch: To on and off the system.
14.	Floating Base: Made of PVC Board to keep the robot afloat
15.	Propeller: To move along with the DC motors.

     2.2 Software Components

•	Arduino IDE


3. System Overview and Working Principle

     3.1 System Overview

The system is a floating robotic device designed to operate on water surfaces. It consists of sensors, motors, a microcontroller and output devices. The robot continuously monitors its surroundings using sensors and responds accordingly.


     3.2 Working Principle
The working process of the system can be described step by step as follows:

1.	Power Supply Initialization: The robot is powered using a Li-ion battery which provides the necessary voltage and current to all components of the system.
2.	System Startup: Once powered on, the Arduino Uno initializes all connected sensors, motors and output devices, ensuring they are ready for operation.
3.	Continuous Monitoring Begins: The system enters a continuous loop where it constantly monitors the environment in real-time.
4.	Obstacle Detection (Ultrasonic Sensor): The ultrasonic sensor sends ultrasonic waves and receives the reflected signals to calculate the distance from nearby objects. This helps the robot detect obstacles and avoid collisions.
5.	Human Detection (PIR Sensor): The PIR sensor detects infrared radiation changes caused by human movement. If motion is detected, it indicates the possible presence of a human.
6.	Condition Check: The Arduino processes the sensor data and checks whether a human is detected or not.
7.	If Human is Detected:
a.	The LED is turned ON to provide a visual indication.
b.	The buzzer is activated to generate an audible alert signal.
c.	This helps rescuers easily identify the presence of a human in the flooded area.
8.	If Human is Detected:
a.	The LED and buzzer remain OFF.
b.	The system continues scanning the environment without interruption.
9.	Movement Mechanism: The DC motors are used to move the robot across the water surface. These motors are mounted on the floating base for propulsion.
10.	Motor Control: The L298N motor driver module controls the speed and direction of the DC motors based on signals received from the Arduino.


 Challenges Faced

     4.1 Problems Encountered

•	Difficulty in designing a stable floating structure.
•	Sensors giving inaccurate readings in outdoor conditions.
•	Power supply issues and battery drainage.
•	Complex wiring connections.
•	Water protection for electronic components.
•	Motor control and balancing movement.
•	Arduino was not supporting the code.
•	Did not have a kind of jumper wires and tools like screw driver, tester.
•	Managing time and team members.


     4.2 Solutions

•	Used lightweight and waterproof materials for floating base.
•	Calibrated sensors properly for better accuracy.
•	Used a stable Li-ion battery system.
•	Organized wiring carefully using breadboard.
•	Protected components using insulation and casing.
•	Tested motor control multiple times to ensure smooth movement.
•	Some parts of Arduino were opened and checked the problem, then solved it.
•	Used the type of wire we had by DIYing it.
•	Had a communication and discussed the urgency and by staying calm.



