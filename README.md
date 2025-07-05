# Smart Water Level Indicator

# Overview

This project implements a Smart Water Level Indicator using an Arduino Uno and an ultrasonic sensor to automate water tank monitoring. The system prevents overflow and dry-run situations by providing visual and auditory alerts based on current water levels.

# Features

1. Real-time water level detection using HC-SR04 ultrasonic sensor

2. Multi-level alerts via LED indicators (Green/Yellow/Red) and buzzer

3. Optional LCD display for detailed level visualization

4. Simple, cost-effective solution suitable for homes and schools

# Hardware Requirements

1. Arduino Uno

2. Ultrasonic Sensor (HC-SR04)

3. Buzzer

4. LEDs (Green, Yellow, Red)

5. 220Ω Resistors (for LEDs)

6. Breadboard

7. Jumper wires

8. 16x2 LCD Display with I2C module


# Installation

1. Connect components as shown in the circuit diagram

2. Upload the provided Arduino sketch to your board

3. Position the ultrasonic sensor at the top of the water tank facing downward

# Usage

1. The system automatically monitors water levels

2. LED indicators show current status:

3. Green: Normal level

4. Yellow: Medium level (warning)

5. Red: Critical level (alert)

6. Buzzer sounds when tank is nearly full or empty

7. Displays exact water level percentage

