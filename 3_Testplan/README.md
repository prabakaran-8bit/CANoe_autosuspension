# Testplan
## HIGH LEVEL TEST PLAN  

| Test ID | Description | Input | Expected output |
| --- | --- | --- | --- |  
| 01 | If Engine status is 0| 0 | Adaptive suspension system will not turn on|
| 02 | If Engine status is 1| 1 | Adaptive suspension system will turn on | 
| 03 | If Engine status > 1| 1 | Adaptive suspension system will turn on |
| 04 | If Engine status < 0| 0 | Adaptive suspension system will not turn on |
| 05 | If Transmission working is 0| 0 | Adaptive suspension system will not turn on |
| 06 | If Transmission working is 1| 1 | Adaptive suspension system will turn on |
| 07 | If Transmission working > 1| 1 | Adaptive suspension system will turn on |
| 08 | If Transmission working < 0| 0 | Adaptive suspension system will not turn on |









## LOW LEVEL TEST PLAN

| Test ID | Description | Input | Expected output |
| --- | --- | --- | --- |
| 01 | Gyroscope not working| 0 | Gyroscope failure |
| 02 | Gyroscope working properly| 1 | Gyroscope Healthy |
| 03 | Shockabsorber damaged | 0 | Shockabsorber failure |
| 04 | Shockabsorber not damaged | 1 | Shockabsorber Healthy |
| 05 | Chasis damaged | 0 | Chasis failure|
| 06 | Chasis not damaged | 1 | Chasis Healthy|


