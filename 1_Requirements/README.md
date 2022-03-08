# Ultrasonic Blind Walking Stick

The main objective of this project is to help blind people to walk with ease and to be warned whenever their walking path is obstructed with other objects, people or other similar odds. As a warning signal, a buzzer is connected in the circuit, whose frequency of beep changes according to the distance of object. The closer the distance of obstruction, the more will be the buzzer beep frequency. We can say that the beep frequency is inversely proportional to the distance.

## S.W.O.T analysis and  5W's & 1H 

### S.W.O.T analysis:
1. Strength:
Helping blind people without any sticks or physicaly large instruments.
2. Weakness:
The accuracy of holes/wetlands cant be determined.
3. Opportunity:
Safety and enhanced user experience.
4. Threats:
Environment and surroundings dependent, battery dependent.

### 5W's & 1H:
#### What: 
Hand device wich acts as blind people's guide stick. 
#### Why: 
It helps with user friendly experience,making it easier than using a physical stick.
#### Where:
Everywhere normal a blind person's day to day activity.
#### When:
Whenever the visualy challenged person is mobile.
#### Who:
visually challenged people.
#### How:
Wear it on the fingers/hands and walk normally.
## Requirements:

  1. Arduino	Nano	
  2. Ultrasonic Sensor	HC-SR04	
  3. Buzzer	5 Volt	
  4. Switch	DPDT	
  5. Battery	9Volt	 

### i)High level requirements:
|  ID   |                                              DESCRIPTION            |
|-------|                                                      -------------  |
| HR01  | It shall need Power supply as input                                 |
| HR02  | It shall need to detect objects                                     |
| HR03  | It shall use buzzer as output for indicating obstacles              |
| HR04  | It shall beep with frequency,inversely proportional to the distance |

### ii)Low level requirements:
|  ID   |   DESCRIPTION                                          |                  STATUS                                  |
|-------| -------------                                          |                                            --------      |
| LR01  | Input voltage is given                                 | Switch is used to control the voltagesupply              |  
| LR02  | Sensor is detectig obstacles on the path               | Output is a buzzing sound        .                      |      
| LR03  | Obstacles are near                                     | Equalling the frequency of buzzing is increased received.|
