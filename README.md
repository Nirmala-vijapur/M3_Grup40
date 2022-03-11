# RKE (Remote Keyless Entry)

# Description 
RKE (remote keyless entry) is an electronic access control system that may be operated from a distance. RKEs, which are commonly used to remotely lock or unlock doors, need the end user to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock. The action is usually performed by pressing a button on a physical fob. The RKE systems for cars can also be used to control the vehicle's ignition system, security alarm, horn, and lights, in addition to locking and unlocking the doors. RKEs can also be used to control access to specific areas of a building, such as garages. While RKE is not commonly used in buildings other than enterprises, it is used in some home automation and security systems.

# Requirements 
## High Level Requirement

|ID  |DESCRIPTION                          | 
|:---|:------------------------------------|
|HLR1|It shall lock the Door               |
|HLR2|It shall unlock the Door             |
|HLR3|The alarm can activation/deactivation|
|HLR4|It shall approach light              |

## Low  Level requirements 
|ID  |DESCRIPTION                                                                                      | 
|:---|:------------------------------------------------------------------------------------------------|
|LLR1|For doing lock operation the user needs to press the blue switch on                              |
|LLR2|For doing unlock operation the user needs to press the blue switch 2 times                       |
|LLR3|For doing alarm activation/deactivation operation the user needs to press the blue switch 3 times|
|LLR4|For doing approach light operation the user needs to press the blue switch 4 times               |


# SWOT Analysis
## Strengths
* low power consumption 

* Better Security

* Better accesss control

* Ease and convenience

## Weakness
* The cost of this technology is high

* Thieves can hack the program

# 4W'S & 1H
## WHO 
The RKE (remote keyless entry) is an electronic access control system that can be operated from a distance.

## WHAT 
RKE (Remote Keyless Entry) which are commonly used to remotely lock or unlock doors.

## WHEN
end user needs to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock.

## Where
RKE systems for cars can also be used to control the vehicle's ignition system.

## How
The action is usually performed by pressing a button on a physical fob.

# Block Diagrams 
## Structural Diagram 

![Screenshot (213)](https://user-images.githubusercontent.com/98865009/157795863-a1a36bb1-7ffc-4adb-92e0-691b0b2f5533.png)


## Behavioral Diagram

![Screenshot (217)](https://user-images.githubusercontent.com/98865009/157803936-650de818-f6e3-490b-af48-d713a87c073c.png)

# TestPlanAndOutput

|NO|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:-|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|1-|TC-1     |For Car lock Function                     |User needs to press the button 1 time |car is locked              |car is locked              |PASS  |
|2-|TC-2     |For Car unlock Function                   |User needs to press the button 2 times|car is unlocked            |car is unlocked            |PASS  |
|3-|TC-3     |For alarm activation/deactivation Function|User needs to press the button 3 times|alarm activated/deactivated|alarm activated/deactivated|PASS  |
|4-|TC-4     |For approach light Function               |User needs to press the button 4 times|approach light ON          |approach light ON          |PASS  |




