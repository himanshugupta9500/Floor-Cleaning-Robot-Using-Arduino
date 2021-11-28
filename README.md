# Floor-Cleaning-Robot-Using-Arduino
In a present-day scenario, we all are so busy with our work that we don't have the time for cleaning our house properly. The solution to the problem is very simple, you just need to buy a domestic vacuum cleaner robot which will clean your house with the press of a button. But such commercial products share one common issue, which is cost. So today, I decided to make a simple Floor cleaner robot, which is not only simple to make but costs very less compared to commercial products available in the market.

***Components-Required***

1. HARDBOARD SHEET
2. ARDUINO UNO R3
3. MOTOR DRIVER L298
4. SERVO MOTOR 
5. ULTRASONIC SENSOR HD-SR04
6. ULTRAFIRE BATTER 18650 3.7V (2x)
7. DC MOTOR(x5)
8. WHEELS 65*26mm(x4)
9. JUMPER WIRES

***Steps Involved***

1. Fixing the motors : Fixing the motors on the hardboard along with wheels and solder 
them in pair of 2 so that they can synchronize properly. Here we had used 4 DC motors 
and 4 65*25mm wheels.
 Another motor is also fixed at the top of the hardboard which will be used in near future to 
rotate the scrub for cleaning purpose.
2. Then we did the connection of all the motor wires with motor driver L2
3. Now we had installed the arduino ide and uploaded the code of our module in arduino 
with the help of a USB.
4. Then we had connected a ULTRASONIC SENSOR HC-SR04 on the top of a servo 
motor which helps in rotating the sensor clockwise and anticlockwise.
5. Then we had connected all the componets with the arduino board as per the pins given in 
previous slide .
6. At last the motor driver and arduino are connected to the ULTRAFIRE BATTERY 
18650 3.7V to power all the components.

***_Working:_***

• HCSR04 module generates a sound vibration in ultrasonic range when we make the 
‘Trigger’ pin high for about 10us which will send a 8 cycle sonic burst at the speed of 
sound and after striking the object, it will be received by the Echo pin. Depending on 
time taken by sound vibration to get back, it provides appropriate pulse output. If the 
object is far away then it takes more time for ECHO to be heard and the output pulse 
width will be big. And if the obstacle is near, then the ECHO will be heard faster and 
output pulse width will be smaller.
 Distance= (Time x Speed of Sound in Air (343 m/s))/2.
• Since a scrubber is connected the motor and hence as the robot moves the scrubber 
rotates and dust is adsorbed on the surface of the scrubber.

***Conclusion:***

• This research facilitates efficient floor cleaning with sweeping and mopping operations. 
This robot works in two modes automatic and manual for user convenience. The model 
we proposed is working in automatic mode once instantiated. This proposed work 
provides the hurdle detection in case of any obstacle that comes in its way. The obstacle 
detection range is 1ft.
• A mechanical setup is designed with the synergies of pneumatics and electronics to 
provide efficient cleaning system both at ground and as well as window levels.
• This contemporary design helps to overcome the limitations of the existing technologies 
and surpass them in terms of robot capability, modularity and payload.

***_Future Work:_***

• We can control it through mobile via bluetooth sensor through which a user can 
command the movement of the robot.
• We can also add a dust collector along with the cleaner and hence it will create suction 
and acts like a automatic vaccum cleaner.
• Image processing technique can be implied to analyses the surface cleaning efficiency 
using a high quality on board camera.
• Germ less cleaning using UV exposure installed on the vehicle

***_References:_***

• Jens-Steffen Gutmann , Kristen Culp , Mario E. Munich and Paolo Pirjanian. The Social 
Impact of a Systematic Floor Cleaner . In IEEE international workshop on advance robotics an 
its social impacts , Technische University munchen, Germany May 21- 23,2012
• Evolution Robotics Inc. Introducing Mint-the evolution of floor care, 
www.mintcleaner.com,2011.