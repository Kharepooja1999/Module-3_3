# RKE BI-DIRECTIONAL COMMUNICATION SYSTEM
# Description:
This project focus on the BI-Directional ways.A BiCom system is a extension of undirectional RKE to bidirectional RKE ststem .which is a capable of two way communication system and it is from uni -directional system

The term bi-com, is also called keyless entry or remote central locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity. Widely used in automobiles, an RKS performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions
# Research:
* BiCom system ,is a system that is designed to remotely lock or unlock the automobiles, RKE(Remote Keyless entry)system operates by broadcasting radio waves on a particular frequency unidirectionally,RKE systems implement encryption algorithms to prevent car thieves from intercepting and spoofing the telegrams..
 * BiCom system, which is nothing but the simple extension of the unidirectional RKE system into bidirectional RKE system.
 * BiCom system works in both the ways, as like RKE it sends the data but also recieve the data from the vehicle in which it is being implimented.
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
# SWOT Analysis:
|STRENGTHS|WEAKNESS|OPPORTUNITIES|THREATS|
|:----|:----|:---|:----|
|Transmission between the car and key are encrypted to prevent theft|The system works on a certain limited range |Scope of the system is huge in our automobile |if our remote lost then automobile security is in more trouble|
|No human interaction required|Water and dust can affect the system |User friendly system|Cannot multitask in same time|
|High security|limited user range|Cost effective|Battery replacement required frequently|
# 5W's & 1H
|WHO|WHAT|WHEN|WHERE|WHY|HOW|
|:---|:---|:----|:----|:---|:---|
|Car owner or the person wants to control the functionality wirelessly|Wireless remote key security system for car|The user wants to do locking/unlocking alaram and other functionalities|Near the car inside a given frquency range|For security of the car and various other functionalities|By pressing down the blue button in the key remote|  


