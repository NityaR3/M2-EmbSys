# Fitness tracker 
This wearable is a wrist-based monitor with sensors that tell you if you’ve been walking enough, sleeping and eating enough, jogging or sprinting, staying out too long in the sun, and it tracks a whole lot of other stuff to keep you as healthy as you can be.
### High level recquirments
#### Sensing layer: 
This layer has sensors embedded in the device; these sensors collect data like number of footsteps, heart rate, body temperature, etc. The data collected by sensors are sent to servers using Wide Area Network such as GSM, GPRS, and LTE.
#### MAC Layer: 
This layer is responsible for device monitoring and control, quality-of-service management, and power management.
#### Network layer: 
This layer takes care of transmission, routing, and addressing using IPV6. With IPV6, address allocation and management can be done more efficiently, hence it is chosen over other Internet protocols.
#### Processing and storage layer: 
In this layer, the data received from the sensing layer is analyzed and stored in databases. This layer is also responsible for security control.
#### Service layer: 
This layer provides the analyzed and processed data to other services like mobile application on Android or iOS.
![WhatsApp Image 2022-02-21 at 8 29 23 AM](https://user-images.githubusercontent.com/98872154/154883986-2f3431a2-12da-4916-9f18-ac8b7efc17ad.jpeg)
### Low level recquirments
## Sensors:
#### Accelerometers:
These are electro-mechanical devices capable of measuring acceleration forces, which are intensity and direction of motion. In put it in simpler terms, these devices monitor your movement
#### GPS:
Global positioning system (GPS) is so much a part of our everyday lives, I doubt it needs any sort of explanation. This technology tracks people, objects, and finds locations, directions.
#### Galvanic Skin Response Sensor
Galvanic Skin Response Sensor is another sensor that makes the activity tracker tick.
#### Optical heart rate monitor (OHRM)
Wearables that have the optical heart rate sensor use a method called photoplethysmography (PPG) to measure the heart rate.
#### Bioimpedance sensors
Bioimpedance measures how well the body resists the flow of electric current. In principle, impedance is measured by applying a small electric current via a pair of electrodes; the resulting voltage is picked up using another pair of electrodes.
#### Temperature sensors
Measuring your core body temperature while engaging in some physical activity is a feature most fitness trackers provide.
### Block diagram:
![WhatsApp Image 2022-02-21 at 8 50 56 AM](https://user-images.githubusercontent.com/98872154/154883962-38cece95-16f8-4427-8b0e-c130f9863a84.jpeg)

###### reference:https://www.hackerearth.com/blog/developers/fitness-tracker-work/
