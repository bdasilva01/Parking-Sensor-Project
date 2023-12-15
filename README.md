# Parking Sensor Project
The Parking Sensor Project says it in the name itself, is a parking sensor that uses a HC-SR04 Ultrasonic sensor to detect a range of motions detected at a distance. This also uses RGB LEDs to signify the distance the sensor is detecting at along with a buzzer that indicates the user being too close. This system is powered a ESP32 microcontroller using Arduino IDE software.


### Hardware Requirements
- ESP32 Arduino Microcontroller
- Red, Yellow and Green LEDs
- Breadboard and Male-to-Male wires
- HC-SR04 Ultrasonic Sensor

### Software Requirements
- Arduino IDE

### Setup and Configuration
1. ESP32 Setup: Ensure that the ESP32 board manager is installed in the Arduino IDE.
2. Code Setup: Make sure the code is set up to run on the Arduino IDE software.
3. Circuit Instrumentation: Connect ESP32 onto the breadboard alongside with HC-SR04 Ultrasonic sensor, RGB LEDs and 3V-DC buzzer.

### Hardware Explanation
- Ultrasonic Sensor: Used to detect motion within a distance
- RGB LEDs: Indicates how far the user is.
- Buzzer: Indicates that you are too close (red LED turns on aswell).

### How it Works
Once ESP32is powered on, put your hand 20-30cm away from sensor to show green, 10-20cm to show yellow and less than 10cm to show red and sound off the buzzer!

### Video of Project
https://github.com/bdasilva01/Parking-Sensor-Project/assets/145140928/9f6b9639-2af3-4640-ad33-d2a9d753b7c8

### Schematic
![pasted image 0](https://github.com/bdasilva01/Parking-Sensor-Project/assets/145140928/c709b804-b902-4303-b4d4-f33c55b9723f)

### Code
![pasted image 0](https://github.com/bdasilva01/Parking-Sensor-Project/assets/145140928/34d705a4-406d-4793-8226-a0035014b90e)
![pasted image 0](https://github.com/bdasilva01/Parking-Sensor-Project/assets/145140928/32850772-cade-4016-8cd3-34faf84f1480)

