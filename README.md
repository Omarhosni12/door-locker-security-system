# door-locker-security-system
Overview: This project implements a door locker security system using two ATmega32 microcontrollers operating at a frequency of 8MHz. The system is designed based on a layered architecture model, consisting of the Human Machine Interface (HMI_ECU) and Control ECU (CONTROL_ECU). The HMI_ECU interacts with the user via a 2x16 LCD and a 4x4 keypad, while the CONTROL_ECU manages all system processing, including password verification, door unlocking, and alarm activation.
Specifications:
1.	Microcontrollers: Two ATmega32 microcontrollers operating at 8MHz.
2.	Layered Architecture:

  	 •	HMI_ECU: Interfaces with the user via a 2x16 LCD and a 4x4 keypad.

  	•	CONTROL_ECU: Responsible for all system processing, including password validation, door unlocking, and alarm activation.

4.	HMI_ECU Functionality: Receives user inputs from the keypad and displays messages on the LCD screen.
5.	CONTROL_ECU Functionality: Processes user inputs, verifies passwords, controls the door lock mechanism (using EEPROM, Buzzer, and DC-Motor), and activates the system alarm if necessary.![image](https://github.com/user-attachments/assets/30b9cff9-eeb7-4ccc-b2d5-fc6c3884c609)

