Oxford Flood Network
====================

*Building a citizen-led flood detection network with the Internet of Things & TV Whitespace*

This repository contains and overview and the material for developing the flood network (not just code). For an introduction, read the [PDF guide to Oxford Flood Network](./blob/master/Oxford%20Flood%20Network.pdf)

##Current Project Overview
###Technical Summary
####Sensor device v1:
 * Ciseco RFu (Cisceco SRF Radio + ATMega 328)
 * Ciseco RFu development board
 * Donated Grove ultrasonic rangefinder
 * Large IP55 case
 * **Status: **Deployed successfully x1, recalled due to battery bug & poor RF performance

####Sensor device v2:
 * Ciseco RFu 
 * Oxfloodnet custom PCB with temperature compensation
 * Maxbotix Rangefinder
 * 3D Printed cone to direct rangefinder signal
 * **Status: **Test PCBs fabricated & working, need to develop case & RF connection

####Sensor gateway:
 * Raspberry Pi running a Ciseco SRF radio and LLAP listener
 * Node-red code reading a serial port and outputting to a database backend
 * **Status: **Code functional, but perhaps Node Red is overkill for purpose
 
####Database backend: 
 * TODO (see code from https://github.com/sushack)

####Frontend App & Visualisation:
 * TODO (see code from https://github.com/sushack)

####Device Management
 * TODO: Define spec

###Project Summary
 * Technology transfer
 * Sustainability models for a deployment
 * Aims
