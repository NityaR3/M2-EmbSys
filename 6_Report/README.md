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
8. Sensors
9. Actuators.
10. Micro controller and memory
11. Sub-system and others
12. Application


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

#### 7. Block diagram:
##### Circuit diagram:
![WhatsApp Image 2022-02-25 at 11 30 17 PM](https://user-images.githubusercontent.com/98872154/155764656-1f4a7877-077d-4cfb-88cc-508fbcecabe6.jpeg)

#### 8. Sensors:
##### Push Button: 
A push-button is a simple switch mechanism to control some aspect of a machine or a process. Buttons are typically made out of hard material, usually plastic or metal.The surface is usually flat or shaped to accommodate the human finger or hand, so as to be easily depressed or pushed. Buttons are most often biased switches, although many un-biased buttons (due to their physical nature) still require a spring to return to their un-pushed state. 

#### 9. Actuators:
##### Seven segment Display:
Seven segment displays are the output display device that provide a way to display information in the form of image or text or decimal numbers which is an alternative to the more complex dot matrix displays. It is widely used in digital clocks, basic calculators, electronic meters, and other electronic devices that display numerical information. It consists of seven segments of light emitting diodes (LEDs) which is assembled like numerical 8.

#### 10. Micro controller:
The ATmega8 is a low-power CMOS 8-bit microcontroller based on the AVR RISC architecture. By executing powerful instructions in a single clock cycle, the ATmega8 achieves throughputs approaching 1 MIPS per MHz, allowing the system designer to optimize power consumption ver- sus processing speed.

#### 10.Application:
###### . Alarm Clock, Set AC Timer, Set time in camera to take the picture, flashing light indicator in automobiles, car parking  control etc.
###### . Counting the time allotted for special process or event by the scheduler.
###### . The UP/DOWN counter can be used as a self-reversing counter.
###### . It is also used as clock divider circuit.
###### . The parallel load feature can be used to preset the counter for some initial count.
###### . Commons used in home appliances like washing machine, microwave own, Time schedule led indicator, key board controller etc.
###### . They are also used in machine moving control.
###### . Mostly used in digital clocks and multiplexing circuits.
###### . They are used to generate saw-tooth waveform (Stair case voltage)
###### . It is also used in digital to analog converters.
