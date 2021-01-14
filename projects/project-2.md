---
layout: project
type: project
image: images/ee296.png
title: Arduino Security Check System
permalink: projects/ee296
# All dates must be YYYY-MM-DD format!
date: 2020-12-14
labels:
  - Engineering
  - Arduino
  - C
summary: A sophomore design group project completed for EE 296. It is designed to improve the security of rooms and buildings.
---
<p align="center">
  <img src="../images/ee296-door-front.png" width="40%" height="40%" />
  <img src="../images/ee296-door-back.png" width="40%" height="40%" /> 
</p>

The Arduino Security Check System was a team project by me and another student in EE 296. The system was designed to detect any intruders going through a door. The intended environment for such device could range from a house front door, room door, or business door. It consisted of two RFID scanners inside and outside that would unlock the door if a valid RFID tag was scanned. If there was no valid RFID scanned but the door still opens, this is seen as a possible intruder and an alarm will sound which can only be turned off using a valid RFID. All tags being scanned were outputted into a web server so the RFID scans can be tracked by looking at the output history. Therefore, this can alternatively be used as a clock in and out system for work so employers know the exact time the employees started and ended work.

I wired and programmed two RFID-RC522 sensors (which required pins to be soldered), a reed switch, piezo buzzer, and two LEDs into the Arduino. I also programmed all of these components to work with each other. Once the wiring was completed, a small prototype door was modeled where all of these electrical components were attached. One RFID was used for each side of the door. I tested the product multiple times to ensure the program was consistent, which it was. I then began doing wire management to minimize the mess of the wiring around the model.

Upon completion of this project, I advanced my knowledge in arduino by using more complicated components, such as the RFID scanner, as well as programming because a lot of libraries were required for the RFID scanner and web server.
