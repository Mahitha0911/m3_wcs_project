# Requriments

#  About the project WCS
 * This Project is an __Wiper control (WCS) system__,a wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times. When the button is pressed once the car will start Ignition key postion at ACC. When the button is pressed again the wiper will start Wiper On .When the button is pressed again the wiper will off Wiper Off .When the button is pressed thrice the car will stop Ignition key position at Lock
---
## 5W's & 1H and S.W.O.T analysis 

| 5W's & 1H | 
*__What__  -- wiper control system (WCS)
*__Where__ --Inside and out side the car
*__When__  --When the weather condition is bad (like in rain and snow) the wiper is activate and clean the car window
*__Who__   --Who is driving or controlling the car
*__How__   --By using STM like by multiple pushes on a button

| S.W.O.T ANALYSIS |
__Strengths__ 
*No human interaction with car
*Manages all commands with one key automatically
*encryption in data
__Weaknesses__
*Unable to monitor status of car
*Range is limited
*Wait for certain time after every command to press new command 
__Opportunities__
*The Scope of this sytem is huge in car control
*can be used where  the car need thesed command
*Less cost
__Threats__
*When new command is given without completing the current command it will not take current command 
---

## Requirements


### High Level Requirements

| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | It will start the car|
| HLR2 | It will start the wiper |
| HLR3 | It shall seen speed of the wiper work |
| HLR4 | It will stop the wiper |
| HLR5 | It will stop the car |


### Low Level Requirements

| ID | Low Level Requirements for HLR1|     
| ----- | ----- | 
| LLR1.1 | If the User button is pressed Once, the red LED will be on |      

| ID | Low Level Requirements for HLR2|
| ----- | ----- |
| LLR2.1 | If the User Button is pressed TWICE, Blue,Green,Orange LED's come ON at a time with set of frequency |

| ID | Low Level Requirements for HLR3| 
| -------- | -------------- |
| LLR3.1 |  If the User Button is pressed THIRD time, ON All LED's in CLOCKWISE manner an speeed will increase |  

| ID | Low Level Requirements for HLR4|
| -------- | -------------- |
| LLR4.1 | If the User Button is pressed FOURTH time ,all LED's on anticlock manner |

| ID | Low Level Requirements for HLR5|
| -------- | -------------- |
| LLR5.1 | If the User Button is pressed FIVTH times, the red LED will be off |
