# Guard-Dog-Robot

Guard Dog Robot
Project Description

This project is a Guard Dog Robot designed as a quadruped robotic dog. The robot is built to demonstrate autonomous movement, object detection, and servo control using Arduino and an ultrasonic sensor.

The robot is designed with four legs and multiple servo motors, allowing it to move and perform different actions while monitoring its surroundings.

Main Features
Four-legged quadruped robot design.
Servo motors used to control the robot's leg movement.
HC-SR04 Ultrasonic Sensor for detecting nearby objects.
Arduino used as the main controller.
The robot can respond when an object is detected within a specified distance.
The robot can be programmed to move to a specific position when an object is detected.
LED can be added as a visual indicator when the robot detects an object.

Guard Dog Function

The main idea of the project is to make the robot work as a guard dog.

When an object or person approaches the robot and the ultrasonic sensor detects a distance of 10 cm or less, the robot responds by moving the servo to a predefined angle.

When the object moves away, the servo returns to its original position.

          Object / Person
                 ↓
          HC-SR04 Sensor
                 ↓
              Arduino
                 ↓
        ┌────────┴────────┐
        ↓                 ↓
   Object ≤ 10 cm    Object > 10 cm
        ↓                 ↓
   Servo moves       Servo returns
        ↓                 ↓
   Guard response    Home position

   Components
Arduino
Quadruped Robot Body
Servo Motors
HC-SR04 Ultrasonic Sensor
LED (Optional)
Resistor
Jumper Wires
Battery / Power Supply
Expected Result

The final result is a four-legged Guard Dog Robot that can detect nearby objects using an ultrasonic sensor and react through servo motor movement.

The system demonstrates the integration of mechanical design, servo control, Arduino programming, and distance sensing in one robotic platform.


A buzzer is added to the Guard Dog Robot. When the ultrasonic sensor detects an object within 10 cm, the buzzer sounds as an alarm to simulate a guard dog alert.

:
Components
Arduino
Quadruped Robot Body
