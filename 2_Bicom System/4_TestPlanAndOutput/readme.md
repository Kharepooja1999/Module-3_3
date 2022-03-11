# TEST PLAN AND OUTPUT
## HIGH LEVEL TEST PLAN
|TEST ID |DESCRIPTION|INPUT|EXPECTED OUTPUT|ACTUAL OUTPUT|
|:-----|:----|:---|:----|:----|
|HLT1|The system shall print window status|User press button|Car locked|Car locked|
|HLT2|The system shall unlock the car doors|User press button|Car unlocked|Car unlocked|
|HLT3|The system shall control the alaram| User press buttom|Car alaram activate/deactivate|Car alaram activate/deactivate|
|HLT4|The system shall approach the lights|User press button|Car approach light|Car approach light|
## LOW LEVEL TEST PLAN
|ID|	DESCRIPTION|	INPUT|	EXPECTED OUTPUT|	ACTUAL OUTPUT|
|:-----|:----|:-----|:-----|:-----|
|HLT1|	All the LED's should ON at the same time	User press button once|	All LED's ON|	All LED's ON|	✔|
|HLT2|	All the LED's should OFF at the same time	User press button twice|	All LED's OFF|	All LED's OFF|	✔|
|HLT3	|All the LED's should ON in clockwise manner	User press button thrice|	All LED's ON in clockwise manner|	All LED's ON in clockwise manner|	✔|
|HLT4|	All the LED's should ON in anti-clockwise manner	User press button four times|	All LED's ON in anti-clockwise manner|	All LED's ON in anti-clockwise manner|	✔|


