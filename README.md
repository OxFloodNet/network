Oxford Flood Network
====================

*Building a citizen-led flood detection network with the Internet of Things & TV Whitespace*

This repository contains and overview and the material for developing the flood network (not just code). For an introduction, read the [PDF guide to Oxford Flood Network](./blob/master/Oxford%20Flood%20Network.pdf)

###Current Project Overview
Sensor device v1:
 * Ciseco RFu (Cisceco SRF Radio + ATMega 328)
 * Ciseco RFu development board
 * Donated Grove ultrasonic rangefinder
 * Large IP55 case

Sensor device v2:
 * Ciseco RFu 
 * Oxfloodnet custom PCB with temperature compensation
 * Maxbotix Rangefinder
 * 3D Printed cone to direct rangefinder signal

Sensor gateway:
 * Raspberry Pi running a Ciseco SRF radio and LLAP listener
 * Node-red code reading a serial port and outputting to a database backend
 * 
 
Database backend: 
 * TODO (see code from https://github.com/sushack)

Frontend App & Visualisation:
 * TODO (see code from https://github.com/sushack)


