# Two Digit Up/Down Counter Circuit

Counters are used in many different applications. Some count up from zero and provide a change in state of output upon reaching a predetermined value; others count down from a preset value to zero to provide an output state change.



## Table of Contents
1. About the Two Digit Up/Down Counter Circuit:
2. Description:
3. Identifying features
4. State of art
5. 5W's & 1H and S.W.O.T analysis
6. Requirements
  i)High level requirements
  ii)Low level requirements
7. Block Diagram and Blocks explination
i)Block Diagram
8. Micro controller and memory
9. Sub-system and others
10. Application


#### 1. About the Two Digit Up/Down Counter Circuit:

Generally, one can see the digital displays which display the score when buttons are pressed on score boards. The main heart of this score board is 2 digits up/down counter circuit. The 2 digits are displayed on two 7 segment displays. This article describes 2 digit up/down counter circuit.

#### 2. Description:

The main principle of this circuit is to increment the values on seven segment displays by pressing the button. When button 1 is pressed value on the display is incremented by one value and when other button is pressed value on the display is decremented by one value. The value on the display can be incremented and decremented from 0-99 as it uses only 2 displays. If one wants to display 3 digits, three displays should be used .

#### 3.Identifying features:
There are many circuits available for 2 digit up/down counter but using a microcontroller reduces components and space on the board but simple programming is required.

#### 4.Requirements:

  1. ATmega8 Microcontroller
  2. 2 X 7-Segment Displays (Common Anode)
  3. 2 X 10KΩ Resistors
  4. 2 X 330Ω Resistors
  5. 2 X Push Buttons

##### i)High level requirements:
|  ID   |                                              DESCRIPTION            |
|-------|                                                      -------------  |
| HR01  | It shall need Power supply as input                                 |
| HR02  | It shall need efficiency code & circuit to increment the values     |
| HR03  | It shall use 7 segment Display for displaying number of increments  |
| HR04  | It shall count in both directions, increasing as well as decreasing |

##### ii)Low level requirements:
|  ID   |   DESCRIPTION                                              |                  STATUS                            |
|-------| -------------                                              |                                            --------|
| LR01  | Input voltage is given                                     | Displays a two digit number                        |
| LR02  | Reading the output word from right to left                 | Output is a binary value.                           |      
| LR03  | Outputs represent a binary number                          | Equalling the number of input pulses received.      |

#### 10.Application:
Alarm Clock, Set AC Timer, Set time in camera to take the picture, flashing light indicator in automobiles, car parking control etc.
Counting the time allotted for special process or event by the scheduler.
The UP/DOWN counter can be used as a self-reversing counter.
It is also used as clock divider circuit.
The parallel load feature can be used to preset the counter for some initial count.
Commons used in home appliances like washing machine, microwave own, Time schedule led indicator, key board controller etc.
They are also used in machine moving control.
Mostly used in digital clocks and multiplexing circuits.
They are used to generate saw-tooth waveform (Stair case voltage)
It is also used in digital to analog converters.
