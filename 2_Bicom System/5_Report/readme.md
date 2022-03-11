# Bicom System 

## Tabel of Content
  1. [Introduction](#introduction)
  
  2. [Research](#research)
   
  3. [Functions](#functions)
   
  4. [Requirements](#requirements)
   
     * [High Level Requirements](#high-level-requirements)
   
     * [Low Level Requirements](#low-level-requirements)

     * [SWOT Analysis](#swot-analysis)
     
     * [5W 1H](#5w-1h)
    
  5. [Block Diagram](#block-diagram)
     
     * [Behavioral Diagram](#behavioral-diagram)
     
     * [Structural Diagram](#structural-diagram)
   
  6. [Testplan](#testplan)
      
      * [High Level Testplan](#high-level-testplan)

      * [Low Level Testplan](#low-level-testplan)

# Introduction
This project focus on the BI-Directional ways.A BiCom system is a extension of undirectional RKE to bidirectional RKE ststem which is a capable of two way communication system and it is from uni directional system.The term bi-com, is also called keyless entry or remote central locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity. Widely used in automobiles, an RKS performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions

# Research
* BiCom system ,is a system that is designed to remotely lock or unlock the automobiles, RKE(Remote Keyless entry)system operates by broadcasting radio waves on a particular     frequency unidirectionally,RKE systems implement encryption algorithms to prevent car thieves from intercepting and spoofing the telegrams..
 * BiCom system, which is nothing but the simple extension of the unidirectional RKE system into bidirectional RKE system.
 * BiCom system works in both the ways, as like RKE it sends the data but also recieve the data from the vehicle in which it is being implimented.
# Functions 
The fuction of this RKE Bi-directional system are
* to get alaram in the car ,then all LED should OFF at the same time
* to get window status of the car, then all LED should ON at the same time.
* to get battery information about the car ,then all LED should be in colckwise manner.
* to get Door status of the car ,then all LED should be in anti-clockwise manner.

Based on the press count of the switch (1-4)the above mentioned features are going to work accordingly. 
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
# 5W 1H
|WHO|WHAT|WHEN|WHERE|WHY|HOW|
|:---|:---|:----|:----|:---|:---|
|Car owner or the person wants to control the functionality wirelessly|Wireless remote key security system for car|The user wants to do locking/unlocking alaram and other functionalities|Near the car inside a given frquency range|For security of the car and various other functionalities|By pressing down the blue button in the key remote|  

# Block Diagram
## Behavioral Diagram
### High level behavioral diagram
![2 1](https://user-images.githubusercontent.com/47153476/157932562-f4449482-94cc-4fcf-9d15-41dbc584ca2c.PNG)

### Low level behavioral diagram
![2 2](https://user-images.githubusercontent.com/47153476/157932577-fb204735-420d-4834-9397-5f1f222726b1.PNG)

## Structural Diagram
### High level structural diagram
![2 3](https://user-images.githubusercontent.com/47153476/157932585-60a5d242-401a-4511-848f-d5e738745d25.PNG)

### Low level structural diagram
![2 4](https://user-images.githubusercontent.com/47153476/157932589-20c86e8d-732a-47b0-a189-f8faf5aaf42e.PNG)

# TestPlan 
## High Level Testplan
| Test Id | Description | Exp I/P | Exp O/P | Actual O/P | Status |
|---------|-------------|---------|---------|------------|---------------|
| HL01 | Status of Window | User 1 Button Press | Window Activated | Window Activated |  |
| HL02 | Status of Alarm | User 2 Button Press | Alarm Detected | Alarm Detected |  |
| HL03 | Status of Battery | User 3 Button Press | Battery Displayed | Battery Displayed |  |
| HL04 | Status of Door | User 4 Button Press | Door Detected | Door Detected |  |
## Low Level Testplan
| Test Id | Description | Exp I/P | Exp O/P | Actual O/P | Status |
|---------|-------------|---------|---------|------------|---------------|
| LL01 | Check for Window | User prsses the Button Once | All LED's turn On | All LED's turn On |   |
| LL02 | Check for Alarm | User prsses the Button Twice | All LED's turn Off | All LED's turn Off |  |
| LL03 | Check for Battery | User presses the Button Thrice | LED's On in clockwise direction | LED's On in clockwise direction |  |
| LL04 | Check for Door | User presses the Button Four times | LED's On in anticlockwise direction | LED's On in anticlockwise direction | | 
