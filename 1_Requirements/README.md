# Two Digit Up/Down Counter Circuit

Counters are used in many different applications. Some count up from zero and provide a change in state of output upon reaching a predetermined value; others count down from a preset value to zero to provide an output state change.

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
