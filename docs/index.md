---
title: Welcome
tags:
- tag1
- tag2
---
<center>
<font size= "6"> Christopher Plumley Datasheet</font><br>
as part of<br>
<font size= "8"> Dohicky</font><br>
for<br>
<font size= "5"> Team 207 </font><br>

**Submission: September, 02, 2026**
</center>

## Introduction

* The Dorm Room Relaxing Light, a system designed to create a comfortable lighting environment by combining user controls with environmental sensing. Although each subsystem performs a different task, they all use a Microchip PIC18F57Q43 Curiosity Nano microcontroller and communicate through connectors to operate as one complete system. The first subsystem focuses on user interaction and system control. It includes an LED array, several buttons, and indication LEDs. The indication LEDs provide information to the user while the buttons allow the user to change or control system settings. The microcontroller uses PWM to control the LEDs, allowing their brightness or lighting behavior to be adjusted. The second subsystem focuses on temperature sensing. A temperature sensor measures the surrounding temperature and sends its signal through an operational amplifier before reaching the microcontroller's analog-to-digital converter (ADC). The microcontroller can then interpret the temperature data and use it as part of the lighting system's control. The third subsystem focuses on ambient light sensing. A light sensor detects the amount of light in the room and sends the signal through an operational amplifier to the ADC. This allows the system to determine the surrounding light level and potentially adjust the LEDs accordingly. Overall, the three subsystems have distinct purposes: user control, temperature measurement, and light measurement. Working together, they allow the relaxing light to respond to both the user's inputs and the surrounding environment, creating a more adaptable and personalized lighting system.

### Project Summary

* The Dohicky has three PCB boards that communicate with one another. This board in particular has the LED outputs and user interface push buttons.
* The board has 1 LED for troubleshooting and on/off status.
* It has 2 LEDs to display temperature information. When no LEDs are lit the temperature is below 0C. When one is lit the temperature is above 0C. When 2 LEDs are lit the temperature is above 100C.
* The board also has an array of red, green, and blue LEDs that will provide mood lighting. The lighting output is based on the brightness of the room and the user selected mode.    
* For a more detailed system overview see the team page. [team 207 report.](https://asu-egr304-2026-f-207.github.io/TEAM207_EGR304-FALL_2026/)

### My Contribution

* My main responsibilites are to act as the assignment leader and project manager. 
* Content should also help an unfamiliar reader navigate to areas of interest. Information like:

To review the details listed of the material used to construct the subsection, you can review it in the ["BOM"](https://embedded-systems-design.github.io/EGR314DataSheetTemplate/04-BOM/BOM/) section of the datasheet.

>Continue for all the remaining/missing sections.
