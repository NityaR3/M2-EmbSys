# Ultrasonic Blind Walking Stick

The main objective of this project is to help blind people to walk with ease and to be warned whenever their walking path is obstructed with other objects, people or other similar odds. As a warning signal, a buzzer is connected in the circuit, whose frequency of beep changes according to the distance of object. The closer the distance of obstruction, the more will be the buzzer beep frequency. We can say that the beep frequency is inversely proportional to the distance

#### 1. About 

The main objective of this project is to help blind people to walk with ease and to be warned whenever their walking path is obstructed with other objects, people or other similar odds. As a warning signal, a buzzer is connected in the circuit, whose frequency of beep changes according to the distance of object. The closer the distance of obstruction, the more will be the buzzer beep frequency. We can say that the beep frequency is inversely proportional to the distance.

#### 2. Description:

A smart stick concept is devised to provide a smart electronic aid for blind people . Blind and visually impaired find difficulties in detecting obstacles during walking in the street.The system is intended to provide artificial vision and object detection, real time assistance via  making use of Arduino NANO. 

#### 3.Identifying features:
The main component used for this device is the ultrasonic sensor.  The ultrasonic sensor transmits a high frequency sound pulse and then calculates the time to receive the signal of the sound echo to reflect back. The sensor has 2 circles. One of them acts as the transmitter and transmits the ultrasonic waves. The other one acts as a receiver (mostly a small microphone) and receives the echoed sound signal. The sensor is calibrated according to the speed of the sound in air. With this calibrated input, the time difference between the transmission and reception of sound pulse is determined to calculate the distance of the object. This circuit is powered by a 9-volt battery through a switch.
#### 4.Requirements:

  1. Arduino	Nano	
  2. Ultrasonic Sensor	HC-SR04	
  3. Buzzer	5 Volt	
  4. Switch	DPDT	
  5. Battery	9Volt	


#### Circuit Explanation:
1. Vcc pin of HC-SR04 is connected to 5 volt pin of Arduino
2. Trigger pin of HC-SR04 is connected to D12 pin of Arduino
3. Echo pin of HC-SR04 is connected to D11 pin of Arduino
4. The ground of HC-SR04 is connected to the GND pin of Arduino.
5. The positive terminal of the 9-volt battery is connected to the Vin pin of Arduino and the negative terminal is connected to the GND pin of Arduino.
6. A buzzer is connected between the D9 pin of Arduino and the GND pin.

The main component used for this device is the Ultrasonic Sensor HC-SR04. The ultrasonic sensor transmits a high frequency sound pulse and then calculates the time to receive the signal of the sound echo to reflect back. HC-SR04 has a transmitter & receiver surface. One of them acts as the transmitter and transmits the ultrasonic waves. The other one acts as a receiver and receives the echoed sound signal. The sensor is calibrated according to the speed of the sound in air. The speed of sound is 341 meters per second in the air, and the distance between the sensor and object is equal to time multiplied by the speed of sound divided by two.

Distance = (Time * Speed Of Sound) ÷ 2

#### Block diagram:
![WhatsApp Image 2022-03-08 at 3 44 06 PM](https://user-images.githubusercontent.com/98872154/157216011-8396e3b1-dafb-4919-b22e-2de64e98cb1f.jpeg)
#### Circuit diagram:
![WhatsApp Image 2022-03-08 at 3 47 10 PM](https://user-images.githubusercontent.com/98872154/157216510-b980ca60-6de4-4dc0-ab41-cc1341592f94.jpeg)
#### Application:
1. It works as a navigation device for the blind people by alerting them about dangers
2. The sytem is applied in automotive parking sensors and obstacles warning system. 
3. It is applied during the measurement of object distance. 
4. Robotics barriers. 
5. Auto detection. 
6. With little software and sensor up gradation, can extensible to any other application and specification. 