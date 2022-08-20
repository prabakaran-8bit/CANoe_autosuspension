# Requirements
## Introduction
Adaptive supension is a type of automotive suspension on a vehicle. It uses an onboard system to control the vertical movement of the vehicle's wheels relative to the chassis or vehicle body rather than the passive suspension provided by large springs where the movement is determined entirely by the road surface. Adaptive suspensions are divided into two classes: real active suspensions, and adaptive or semi-active suspensions. While semi-adaptive suspensions only vary shock absorber firmness to match changing road or dynamic conditions, active suspensions use some type of actuator to raise and lower the chassis independently at each wheel.

## Requriments

|R ID|DESCRIPTION|STATUS|
|------|-----------|------|
|R 1|  Engine should be turned on and powertrain ECU should give an output of 1   |IMPLEMENTED|
|R 2|  Output that should be given is Engine status =1 ,brake pressed=1,clutch pressed=1,accelerator pressed=1 | IMPLEMENTED|
|R 3|  Vehicle should be moving transmission ECU should give an output between 1 to 6 | IMPLEMENTED|
|R 4|  Output that should be given is transmission working =1,transmission status=1 or 2 or 3 or 4 or 5 or 6 or R | IMPLEMENTED|
|R 5|  Chasis ECU should be turned on an should give an output of 1  | IMPLEMENTED|
|R 6|  Output that should be given is Chasis health =1 ,Chasis working=1 | IMPLEMENTED|
|R 7|  Gyroscope should be turned on and give the deviation in each axis as input to Chasis ECU |IMPLEMENTED|
|R 8|  Output of gyroscope should be x=1 ,y=1,z=1 |IMPLEMENTED|
|R 9|  Gyroscope output in each axis should be of the range 0 to 30 |IMPLEMENTED|
|R 10|  The battery powering the the Suspension system should provide 48V  |IMPLEMENTED|
|R 11|  Electrosuspension drivers not working the suspension driver status should be sent to the Chasis ECU |IMPLEMENTED|

## SWOT

![swot2suspension](https://user-images.githubusercontent.com/73412166/164066184-5a1aa4e6-e1fc-4d1b-97c0-c49635b27951.png)

## 4W's & 1H:
| Sl.No | Questions | Description | 
| :-----: | :-----: | ----- |
| 1. | What | Adaptive Suspension System  |
| 2. | Who | Anyone with XUV 700 can use | 
| 3. | When | It is available when the vehicle is active(Running) |
| 4. | Where | It is available a featured vehicle| 
| 5. | How | It is constructed by mechanical and embedded systems |
