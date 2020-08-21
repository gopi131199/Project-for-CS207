# Project-for-CS207
I am Gurpreet Singh, i'll be making group with Karanbir Singh. We still have to select which project to work on.

We decided to make a project using an ultrasonic sensor. Sensor is mounted on the car. The car will detect the obstacles through ultrasonic sensors and will avoid them.

To get familiar with the repository following is a map of all contents:
  * **/src** - Code for the project
  * **/hardware** - Hardware sketch/ model.
  * **/build** -
  * **/img** - Required images.
  * **/LICENSE** - License file.
  * **/README.md** - About Project that will help you to get started.

**REQUIREMENTS AND MATERIALS**
===============================

Components Needed:
 * Arduino UNO
 * UltraSonic Sensor - HC-SR04
 * Modulo Motor Driver
 * Servo motors
 * Battery
 * Jumper Wires
 * DC Motor
 * Wheels
  
 Libraries that are required:
  Servo.h (inbuilt in Arduino App)
  NewPing.h -: Ultrasonic SEnsor function library (have to install the library, download it from /libraries)
  
**About Our Project(UltraSonic Car):**
======================================

 BUILD INSTRUCTIONS:
   ![L298N-Module-Pinout](https://user-images.githubusercontent.com/68705731/90843524-155b0780-e31f-11ea-8164-4157b7a28a13.jpg)
 out1 and out2(of L298N Driver)
 out3 and out4
 12V and ground(of L298N) is connected to batteries.
 Ground(of L298N) is connected to Ground of Arduino.
 5V(of L298N) is connected to Vin of Arduino.
 IN1, IN2, IN3, IN4()is connected to Pin4, Pin5, Pin6, Pin7(of Arduino) respectively.
 Ground(of Ultrasonic sensor) to Ground (of Arduino)	
 VCC(of Ultrasonic sensor) to 5V (of Arduino)
 Trig (of ultrasonic sensor) to Analog Pin A2 (of Arduino)
 Echo(of ultrasonic sensor) to Analog Pin A1 (of Arduino)
 Orange wire to Digital Pin10
 Red wire(of Servo motor) to 5V (of Motor Driver)
 Brown wire(of servo motor) to Ground (of Arduino)

 Ultrasonic Sensor is mounted on top of Servo Motor at front of car.
 
 Usage:
  You just have to upload the code on arduino and the motors will start. Put the car on ground and if
  there will be any obstacle in front of the car, it will change the path.
  



Team:
  Gurpreet Singh @gopi131199,
  Karanbir Singh @karanbir11
