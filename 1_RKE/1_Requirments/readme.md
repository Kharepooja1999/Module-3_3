# Description
Remote Keyless Entry (RKE) systems are the successors to the traditional method of opening car doors by inserting physical keys. Keys with RKE-capabilities allow key-holders to remotely lock and unlock car doors, start or stop engines, or turn on and off anti-theft alarms.
* This RKE transmission has Transmitter and Receiver.
* RKE operates by broadcasting radio waves on a particular frequency unidirectionally. 
* RKE systems implement encryption and rolling code algorithms to prevent car thieves from intercepting and spoofing the telegrams

# Functions of RKE system
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
