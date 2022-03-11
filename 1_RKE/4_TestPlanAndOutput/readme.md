# Test Plan And Output
## High Level Requirements
| ID | Description | Output|
|-----|------------|------|
| HLT1 | The system shall locks the car doors |✔|
| HLT2 | The system shall unlocks the car doors |✔|
| HLT3 | The system shall control the alarm |✔|
| HLT4 | The system shall approch the lights |✔|

## Low Level Requirements
| Category | ID | Description | Output|
|----------|----|--------------|------|
| HLT1 | LLT1 | The car doors should lock when the user press the button once|✔|
|     |  LLT2 | All the LED's should ON at the same time |✔|
| HLT2 | LLT1 | The car doors should unlock when the user press the button twice|✔|
|     |  LLT2 | All the LED's should OFF at the same time |✔|
| HLT3 | LLT1 | The system should control activation and deactivation of alarm when the user press the button three times|✔|
|     |  LLT2 | All the LED's should ON in clockwise manner |✔|
| HLT4 | LLT1 | The system should approch lights when the user press the button four times|✔|
|     |  LLT2 | All the LED's should ON in anti-clockwise manner|✔|

