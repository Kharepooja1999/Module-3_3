# Test Plan And Output
## High Level Requirements
| ID | Description | Output|
|-----|------------|------|
| HLR1 | The system shall locks the car doors |✔|
| HLR2 | The system shall unlocks the car doors |✔|
| HLR3 | The system shall control the alarm |✔|
| HLR4 | The system shall approch the lights |✔|

## Low Level Requirements
| Category | ID | Description | Output|
|----------|----|--------------|------|
| HLR1 | LLR1 | The car doors should lock when the user press the button once|✔|
|     |  LLR2 | All the LED's should ON at the same time |✔|
| HLR2 | LLR1 | The car doors should unlock when the user press the button twice|✔|
|     |  LLR2 | All the LED's should OFF at the same time |✔|
| HLR3 | LLR1 | The system should control activation and deactivation of alarm when the user press the button three times|✔|
|     |  LLR2 | All the LED's should ON in clockwise manner |✔|
| HLR4 | LLR1 | The system should approch lights when the user press the button four times|✔|
|     |  LLR2 | All the LED's should ON in anti-clockwise manner|✔|

