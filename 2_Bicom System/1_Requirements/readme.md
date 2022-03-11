# RKE BI-DIRECTIONAL COMMUNICATION SYSTEM
# Description:
this project focus on the BI-Directional ways.A BiCom system is a extension of undirectional RKE to bidirectional RKE ststem .which is a capable of two way communication system and it is from uni -directional system

The term bi-com, is also called keyless entry or remote central locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity. Widely used in automobiles, an RKS performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions
# Functions of RKE Bi-directional system:
* to get alaram in the car ,then all LED should OFF at the same time
* to get window status of the car, then all LED should ON at the same time.
* to get battery information about the car ,then all LED should be in colckwise manner.
* to get Door status of the car ,then all LED should be in anti-clockwise manner.

Based on the press count of the switch (1-4)the above mentioned features are going to work accordingly. 
# Components
## Microcontroller:
We are using STM32 Discovery Board to compute our project.It is a 32-bit microcontroller integrated circuits Design by STMicroelectronics.
## STM32CubeIDE:
It is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors.
# Requirements
## High level requirements:
|ID|DESCRIPTION|
|:----|:---|
|HLR1|System shall be able to print Alarm status of automobile   | 
|HLR2| System shall be able to print Window status of automobile  |
|HLR3| System shall be able to print Car Battery information  |
|HLR4| System Shall be able to print Door status of the automobile  |
## Low level requirements:
|LLR ID|DESCRIPTION| HLR ID|
|:----|:---|:---|
|LLR01.1|When the button is pressed all the LED's shall be on  |HLR01  |
|LLR01.2| All the LED's shall be on at the same time-Green-->on Orange-->on Red-->on Blue-->on  | HLR01 |
|LLR02.1|When the button is pressed all the LED's shall be off at the same time|HLR02   |
|LLR02.2|All the LED's shall be off at the same time-Green-->off Orange-->off Red-->off Blue-->off|HLR02  |
|LLR03.1|When the button is pressed all the LED's shall be on| HLR03 |
|LLR03.2|When the button is pressed LED's shall be on in anti-clockwise direction| HLR03|
|LLR04.1|When the button is pressed all the LED's shall be on|HLR04 |
|LLR04.2|When the button is pressed LED's shall be on in anti-clockwise direction| HLR04 |

