# Smart-Parking-System


**Aim**: 
To design the infrastructure of parking system with the help of 
various iot sensors and devices in order to solve the traffic 
congestion problem and to enhance the parking facility to all the 
users.


**Methodology**: 
In this project we will be using IR (infrared) sensors to detect 
whether a vehicle is there in its range or not. If the vehicle is 
detected then a red LED will glow indicating that the slot is full 
and if there is no obstacle(vehicle) then green led will glow 
indicating the slot is free(available).This availability of slots i.e. 
the output of the IR sensors, will be displayed in the Thingspeak 
application.
Further we will be using two more IR sensors and servo motor to 
let the vehicles in and out of the parking area. One IR sensor will 
be placed just after the servo motor to detect the vehicles 
coming inside the parking area and the other IR sensor will be 
placed just before the servo motor to detect the vehicles going 
outside the parking area. When a vehicle is detected by first 
IR/second IR, then servo motor will rotate up to 90 degrees thus 
opening the barrier to let the vehicles in/out. However when the 
vehicles are detected by both the IR sensors at the same time, 
the servo motor will not rotate thus ensuring that both the 
vehicles might not collide.

**Requirements**:
**Hardware requirements**:
1. ARDUINO UNO
2. LED
3. USB CABLE
4. IR SENSOR
5. SERVO MOTOR
6. B-TYPE CABLE
7. BREADBOARD
8. JUMPER WIRES
    a. MALE TO MALE JUMPER WIRES
    b. MALE TO FEMALE JUMPER WIRES

**Software requirements**:
1. ARDUINO IDE
2. THINGSPEAK APPLICATION

**Pin Diagram:**
1. CONNECTION OF IR SENSORS WITH ESP MODULE
![circuit1](https://user-images.githubusercontent.com/100076307/227828850-a04f6c2f-7b0e-4cf4-8a2b-20c45360c65e.png)

