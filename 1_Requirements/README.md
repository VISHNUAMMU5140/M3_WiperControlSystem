# Wiper Control System
### WORKING PROCESS


# SWOT Analysis 
## Strength

* The wiper comes back to default position even if stooped in the middle
* Safety for the driver as well as the passengers in the vehicle
* Clear Visibility to the Driver for neat ride.

## Weakness 
* The total cost of the wiper system is high if implemented in real-time.
* The major disadvantage is that STM32 contains only one button for all the operation
* User has to undergo a sequence to acquire desired result and can't attain his result directly with the press of the button.

## Threats 
* Replacing the board is not possible if it malfunctions.
* Can't have more functions as the functionality of the board is very basic.

# Requirements
## High level requirements
| ID | Description | Status |
| --- | --- | --- | 
| HR_01 | ACC Mode Operation |	Implemented |
| HR_02 |	Wiper ON |	Implemented |
| HR_03 |	Wiper Speed Change |	Implemented |
| HR_04 |	Wiper OFF |	Implemented |
## Low level requirements
| ID |	Description | Operation |	Status |
| --- | --- | --- | --- |
| LR_01 |	Button pressed once for 2 secs | Red LED ON |	Implemented |
| LR_02 |	Button pressed second time | 1 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_03	|Button pressed third time | 4 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_04	|Button pressed fourth time | 8 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_05 |	Button pressed again for two seconds |Turn Off all LEDs |	Implemented |
