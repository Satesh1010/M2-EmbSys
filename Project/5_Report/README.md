## Requirements
## Water Level Monitoring System using Atemga328
## Abstract 
Most of the people in residential areas face the problem of running out of water and overflow of water in water tanks due to excess supply of water. It becomes difficult for users to judge the level of water in water tanks. When the pump is turned ON, users will not realize that the water tank is filled, which may result in overflow. Water level indicator and controller system is used to sort out the issues associated with water tank. It is also possible to check the level of the water using sensor so that whenever the water goes below, pump gets turned ON automatically. Also when there is overflow of water in water tank it uses sensor to detect the water level so that if the water level goes above, the pump gets turned off automatically. This system prevents wastage of water.

 ## Features
1. Shows water level  in the tank.
2. Cut off water automatically.
3. Consume very little energy ,ideal for continous operation.
4. The system ensures no overflows or dry running of pump there by saves energy  and water.

## SWOT ANALYSIS

## Strengths
1.Conservation of water resource.  
2.Manual effort reduction.

## Weakness
Maintanance is required.
## Opportunities

It is used in places like home,office,industry.
## Threats

Competitive due to more versions of Products.
## 4W's and 1H

## Who

This Product can be used by any consumers because its simple user friendly.
## What

It makes water tank fill and cut off water automatically.
## When

When the water level is low the tank fill automatic.
## Where

This system can be used in places like home,office,industry.
## Why
To save water and save electricity.
## How

The system controled by atmega328 which act as a brain.
## High level and and Low level Requirements
## HIGH LEVEL REQUIREMENTS
| ID |Description  |Status|
|--|--|--|
|HLR1  | Display water level |IMPLEMENTED|
|HLR2|Flow water when level is low|IMPLEMENTED|
|HLR3|Stop water flow when level is reached|IMPLEMENTED|
## LOW LEVEL REQUIREMENTS
|ID |Description  |Status|
|--|--|--|
| LLR1 |If low level switch open before uplevel the water won't flow  |IMPLEMENTED|
|LLR2|The system works without errors|IMPLEMENTED|
## Behavourial Diagram
![sssss](https://user-images.githubusercontent.com/98962050/157184789-801dbf84-8d48-4cab-9723-7bd17f1db6e4.jpg)
## Block Diagram
![sssss (2)](https://user-images.githubusercontent.com/98962050/157194300-1e29e6ba-6cab-4241-aea6-8f69274d2fa0.jpg)
## Structural Diagram
![sssss-Page-1](https://user-images.githubusercontent.com/98962050/157185059-9a6e4713-328e-4c8d-83b4-c6785ccab296.jpg)
# Components Discription:
## Atmega328
It is the controlling device of the system.
## LCD Display
It is used to display the output data.
## LED
It is used to indicate the water flow.
## Pump
It is used to pump the water to the tank.
## Ultrasonic sensor
It is used to sense the water level from the surface and top of the tank.
﻿## TEST PLAN
## High Level Test Plan
| Test ID | Description | Exp I/P | Exp O/P |  Actual O/P|Status |
|--|--|--|--|--|--|
|HLR1 |  Display Level of Water|NA|0L - 3000L|700L|Pass|
|HLR2|LED Glows when both Switches Open|NA|LED Glows|LED Glows|Pass|
|HLR3|LED OFF when both Switches Closed|NA|LED OFF|LED OFF|Pass|
## Low Level Test Plan
|  Test ID| Description |Exp I/P|Exp O/P|Actual O/P|Status |
|--|--|--|--|--|--|
| LLR1 | LED Glows when UCC only open |NA|LED Glows|LED Glows|Pass|
|LLR2|Level of water varies from 0L - 3000L|NA|varies from 0L - 3000L|varies from 0L - 3000L|Pass|
Stimulation
![Simulation](https://user-images.githubusercontent.com/98962050/157188315-fda87b4f-d1cf-40e0-8277-fab2538f5486.jpg)
## APPLICATION
* The main aim of this system is to monitor the water level at rural areas so that they help in detecting the wastage of water and measures can be taken to avoid unnecessary overflowing of water in the areas where monitoring is a difficult task. 
* The LED switches on when the particular water level is detected.
* Can be used in water tanks to control water levels.
* Can be used in factories, commercial complexes, apartments, home.
