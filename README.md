# Smart Home IoT System

**Name :** Susan Mary  
**Company :** CODTECH IT SOLUTIONS  
**ID :** CT04DS5631  
**Domain :** Embedded Systems  
**Duration :** July to August 2024  
**Mentor :** Muzammil Ahmed  
 
## Overview of Project

**Project :** SMART HOME IOT

### Objective : 
The objective of the Smart Home IoT project is to design and simulate a comprehensive home automation system using IoT technology.  
The system aims to enhance comfort, energy efficiency, and security within a smart home environment by automating the control of lights, fans, and monitoring room occupancy and temperature.  
Additionally, the project includes a security feature with a keypad password system for controlled access to the home.

### Key Activities :
- **Occupancy Detection**: Integrated 2 PIR sensors to detect the presence of people in the room, enabling occupancy monitoring. 
- **Automatic Light Control**: Implemented logic to automatically turn lights on or off based on room occupancy and LDR-light intensity levels.
- **Automatic Fan Control**: Developed a system to turn the fan on or off based on occupancy and room temperature, with a threshold set at 25 degrees Celsius.
- **Keypad Password System**: Added a keypad password system to ensure only authorized individuals can enter the house by knowing the correct password.
- **System Design and Simulation**: Designed and simulated the entire Smart Home IoT system using Proteus, integrating various sensors and actuators to automate home functions.

### Technologies Used :
- **Simulation Software**: Proteus Design Suite
- **Programming Language**: Python 3.12
- **Hardware Used**:
  - Raspberry Pi
  - PIR Sensors 
  - LDR Sensor
  - LM35 Temperature Sensor
  - ADS1110 ADC Converter
  - MCP23008 GPIO Expander
  - LCD Display
  - Relay 
  - Keypad (phone)
  
### Working : 
- The system begins by using the first PIR sensor to detect if a person enters the room. If the sensor detects motion, it triggers the next steps in the system  
- Once motion is detected by the first PIR sensor, the system checks the keypad for a password. Access to the room or house is granted only if the correct password is entered, ensuring security  
- The second PIR sensor monitors for any movement indicating the person’s presence or exit from the room. It helps in accurately tracking the occupancy status  
- Based on the input from both PIR sensors, the system counts the number of people currently in the room and displays this count on the LCD screen  
- The fan is activated if the room is occupied and the temperature (measured by the LM35 sensor) exceeds 25 degrees Celsius. It turns off when the room is empty or the temperature falls below this threshold
 The system uses the LDR sensor to check the ambient light intensity. If the light level is low, the lights automatically turn on. If there are no people present or the light is sufficient, the lights turn off

### Simulation :


![image](https://github.com/user-attachments/assets/c152c322-53c3-414c-93b2-719289013a94)
