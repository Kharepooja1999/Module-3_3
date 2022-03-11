# RKE(Remote Keyless Entry) system 

## Tabel of Content
  1. [Abstract](#abstract)
  
  2. [Introduction](#introduction)
   
  3. [Functions](#functions)
   
  4. [Requirements](#requirements)
   
     * [High Level Requirements](#high-level-requirements)
   
     * [Low Level Requirements](#low-level-requirements)

     * [SWOT Analysis](#swot-analysis)
     
     * [5W's & 1H](#5w's-&-1h)
    
  5. [Block Diagram](#block-diagram)
     
     * [Behavioral Diagram](#behavioral-diagram)
     
     * [Structural Diagram](#structural-diagram)
   
  6. [Testplan](#testplan)
      
      * [High Level Testplan](#high-level-testplan)

      * [Low Level Testplan](#low-level-testplan)
   
   7. [Application and Advantages](#application-and-advantages)

# Abstract
In our modern society comfort became a standard. This comfort, especially in cars can only be achieved by equipping the car with more electronic devices. Some of the electronic devices must cooperate with each other and thus they require a communication channel, which can be wired or wireless. In these days, it would be hard to sell a new car operating with traditional keys. Almost all modern cars can be locked or unlocked with a Remote Keyless System. A Remote Keyless System consists of a key fob that communicates wirelessly with the car transceiver that is responsible for locking and unlocking the car. However there are several threats for wireless communication channels. 
# Introduction
A Remote Keyless Entry System consists of a key fob and a car transceiver that is responsible for locking and unlocking the car. Instead of locking or unlocking the car with a traditional key the user presses a button on the key fob to lock or unlock the car doors,start or stop engines, or turn on and off anti-theft alarms. Unfortunately the keyless cars are increasingly targeted by thieves. Criminals steal vehicles through the re-programming of remote-entry keys. Thus,some insurance companies have denied the insurance for this issue. In addition a Remote Keyless System is vulnerable against a Scan Attack, Playback Attack, Two-Thief Attack,Challenge Forward Prediction Attack and a Dictionary Attack.Another threat for Remote Keyless Entry Systems are On-Board-Diagnose (OBD) key programmers
# Functions 
Main function of this RKE system are
* It locks the car doors when the button is pressed once.
* It unlocks the car doors when the button is pressed twice.
* It activates or deactivates alarm when the button is pressed three times.
* It approaches the lights when the button is pressed four times.

# Requirements
## High Level Requirements
| ID | Description |
|-----|------------|
| HLR1 | The system shall locks the car doors |
| HLR2 | The system shall unlocks the car doors |
| HLR3 | The system shall control the alarm |
| HLR4 | The system shall approch the lights |

## Low Level Requirements
| Category | ID | Description |
|----------|----|--------------|
| HLR1 | LLR1 | The car doors should lock when the user press the button once|
|     |  LLR2 | All the LED's should ON at the same time |
| HLR2 | LLR1 | The car doors should unlock when the user press the button twice|
|     |  LLR2 | All the LED's should OFF at the same time |
| HLR3 | LLR1 | The system should control activation and deactivation of alarm when the user press the button three times|
|     |  LLR2 | All the LED's should ON in clockwise manner |
| HLR4 | LLR1 | The system should approch lights when the user press the button four times|
|     |  LLR2 | All the LED's should ON in anti-clockwise manner|

# SWOT Analysis
![swot](https://user-images.githubusercontent.com/47153476/157834202-808aac63-9bf8-4516-9dbf-be780dc00499.PNG)

# 5W's & 1H
![5Ws1H](https://user-images.githubusercontent.com/47153476/157845479-103a1929-7ba7-4baa-b4fc-44159e48d930.PNG)

# Block Diagram
## Behavioral Diagram
### High level behavioral diagram
![1](https://user-images.githubusercontent.com/47153476/157861947-e4abd80c-759f-450c-b54f-9b2524245eae.PNG)

### Low level behavioral diagram
![2](https://user-images.githubusercontent.com/47153476/157861969-56ad4eb1-0d95-443a-9492-92e298bda306.PNG)


## Structural diagram
### High level structural diagram
![3](https://user-images.githubusercontent.com/47153476/157861976-147e0bbc-572d-401d-a150-33b72c0a8abc.PNG)

### Low level structural diagram
![4](https://user-images.githubusercontent.com/47153476/157861986-1f62e2ca-9673-419c-8e84-673a49eadb37.PNG)

# Testplan
## High Level TestPlan
| ID | Description |Input| Expected Output|Actual Output|Status|
|-----|------------|------|-------|------------|-----------|
| HLT1 | The system shall locks the car doors |User press button |Car locked|Car locked|✔|
| HLT2 | The system shall unlocks the car doors |User press button |Car unlocked|Car unlocked|✔|
| HLT3 | The system shall control the alarm |User press button |Car alarm activate/deactivate|Car alarm activate/deactivate|✔|
| HLT4 | The system shall approch the lights |User press button |Car approach light|Car approach light|✔|

## Low Level TestPlan
| Category | ID | Description |Input| Expected Output|Actual Output|Status|
|----------|----|--------------|------|-----------|---------------|--------|
| HLT1 | LLT1 | All the LED's should ON at the same time |User press button once|All LED's ON|All LED's ON|✔|
| HLT2 | LLT1 | All the LED's should OFF at the same time |User press button twice|All LED's OFF|All LED's OFF|✔|
| HLT3 | LLT1 | All the LED's should ON in clockwise manner |User press button thrice|All LED's ON in clockwise manner|All LED's ON in clockwise manner|✔|
| HLT4 | LLT1 | All the LED's should ON in anti-clockwise manner |User press button four times|All LED's ON in anti-clockwise manner|All LED's ON in anti-clockwise manner|✔|
