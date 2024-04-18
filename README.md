# DE1-project
## Team members
Member 1: Piškula Petr <br>
Member 2: Sadílek Petr <br>


## Theoretical description and explanation
Parking sensors are used to determine distance of a driven vehicle from an obstacle. It helps the driver to safely park the vehicle in a constraint spaces. The implementations vary depending on the manufacturer. Some just use beeping as a hint of approaching of an obstacle, other use graphical visualisation, the most modern use cameras to visualize space around the vehicle.

The solution we use to measure distance is using an ultrasonic sensor HC-SR04, processing the signal and hinting the distance on Nexys A7 50T. <br>
### Board - Nexys A7 50T <br>
Main computing unit
![71AqT8JnX8L _SL1200_](https://github.com/404Sada/DE1-project/assets/165081418/67521a6f-28e0-482c-bca0-f23695782674)

### Ultrasonic sensor HC-SR04 <br>
Distance measuring unit - the "echo" HIGH level duration corresponds to time it takes sound to travel the path from the sensor to the obstaclea
and back.
![image](https://github.com/404Sada/DE1-project/assets/165081418/ecc7565a-74bc-4a62-b3e5-02c0126ec0f5)

### Arduino Uno <br>
Module used to supply 5V voltage
![uno](https://github.com/404Sada/DE1-project/assets/165081418/145b6cf9-d443-4fd2-a091-32dee3a8dc93)



## Hardware description of demo application
![image](https://github.com/404Sada/DE1-project/assets/165081418/bc8e02c2-bf69-4fb2-ab2c-92fd278ee579)

The principle of the desing is to count the duration of echo signal from the ultrasonic sensor. 


## Software description
![IMG_20240418_143652](https://github.com/404Sada/DE1-project/assets/165081418/44da01de-93dd-475b-be8c-467f9b368a25)

https://www.edaplayground.com/x/mxDD

## Component(s) simulation

Write descriptive text and put simulation screenshots of your components.

## Instructions
![IMG_20240418_133337](https://github.com/404Sada/DE1-project/assets/165081418/ba82e8d2-199a-4d60-abba-9fb0b2f06111)

[![Demonstration video](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=Bn0FmMMkb_M)

All that is needed to run the desing is just to properly plug everything in. The implementation is plug-n-play, with only interaction possible being the BTNC reset button for a case of failure.

## References
Put here all references to sources and tools you used.
...
