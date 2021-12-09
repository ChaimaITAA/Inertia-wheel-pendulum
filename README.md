
# Inertia Wheel Inverted Pendulum Project 

The Inertia Wheel Pendulum is a benchmark for nonlinear control of under actuated mechanical systems consisting of a physical pendulum with a symmetric disk attached to the tip, which is free to spin about an axis parallel to the axis of rotation of the pendulum.   


This project is based on Arduino Mega 2560 R3 microcontroller. And the repo contains 
- LabView project 


 
The full gallery of the project<br>

![Picture1](https://user-images.githubusercontent.com/81086263/145449348-962f33fc-16b9-4635-807e-7153ca9dbfa2.png)

<br>


# Electronics hardware
For the Electrical aspect of the project we used:
- An Arduino MEGA2560 Ship
- A Motor Driver
- A Potentiometer
- A 12V Rechargeable Battery
- A Toggle Switch
<br>![electric](https://user-images.githubusercontent.com/81086263/145450894-e02cadcf-2e8a-415b-82bf-997c9c612dde.PNG)

# 3D printed parts
-  Inetria wheel 
- We decided to use the 3D printing technology to obtain the main pieces
(Rod, Wheel, and Mount), since it allows us to freely monitor the shape
and dimensions of the pieces that we pre-designed using SolidWorks.
This design freedom advantage comes handy especially when working
on such systems that operate in high precision and stability.<br>

   ![printr](https://user-images.githubusercontent.com/81086263/145453000-0c4e3439-5431-446d-8820-3ccd8b758ec8.PNG)

# Control algorithm
 - PID (Simple)
 - LQR algorithm (Intermediate) - bIncluded in the software
 

# Connecting the hardware
![dimentions](https://user-images.githubusercontent.com/81086263/145453367-9ce5cd2c-0ce1-43b3-aa1b-7973a4b4e71d.PNG)
<br>
 - Monster motor shield is mounted on Arduino Mega 2560 R3 very simply, as on any Arduino
    - It provides the hardware connections needed and no need for additional jumpers
    - 12V - 5A power supply should be used to power the shield
    - Gyroscope pins connectoin to the arduino
<br>

   ![compon](https://user-images.githubusercontent.com/81086263/145453761-268ec900-bdc0-49ff-8ebc-5e79a5db9007.PNG)
<br>

 


# Running the code
![logigrame](https://user-images.githubusercontent.com/81086263/145452056-f35c552d-ec08-4999-91f0-cbe766e45f99.PNG)
<br>
 - run the LabView project into your Arduino
