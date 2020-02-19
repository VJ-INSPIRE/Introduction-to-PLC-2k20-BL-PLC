ADISHANKARA INSTITUTE OF ENGINEERING AND TECHNOLOGY   
FIVE DAY STTP ON 
An Introductory course on Industrial Automation
In Association with 
ENTREPRENEURSHIP RESOURCE CELL, Dept of EEE, VJEC.




Part A
Construct a simple circuit that switches on motor when the temperature sensor supplies signal on rated temperature.

Suppose there are two engineers, a section engineer, and senior engineer. There is a switch on cabin room of each engineer. Whenever needed, the section engineer will switch on the motor on the section and once the section engineer switches on senior engineer will verify the requirement. Once the senior engineer also approves operation by switching on the switch on his room the motor will be switched ON. 
Hint : Two inputs – one at section engineer room and one at one at senior engineer room. 
One output for motor. 

Suppose there are two engineers, a section engineer, and senior engineer. There is a switch on cabin room of each engineer. The motor should be turned on whenever either section engineer turns on the motor or senior engineer turns on the motor.
Hint : Two inputs – one at section engineer room and one at one at senior engineer room. 
One output for motor. 

Make a DOL starter.

Suppose there are two engineers, a section engineer, and senior engineer. There is a switch on cabin room of each engineer. Whenever needed, the section engineer will switch on the motor on the section and once the section engineer switches on, a Led will be turned on at the senior engineer cabin indicating that he has switched ON the motor. Senior engineer will verify the requirement and approves operation by switching on the switch on his room the motor will be switched ON.
Hint : Two inputs - one at section engineer room and one at one at senior engineer room
Two outputs (Led alarm and Motor) 
Make output latch

Suppose there are two engineers, a section engineer, and senior engineer. 
There is a switch on cabin room of each engineer. 
The motor should be turned on whenever either section engineer turns on the motor or senior engineer turns on the motor.
But the motor should be turned OFFwhenever both engineers are switched ON the motor at the same time. 
The motor should be turned OFFwhen both engineers areout of station or absent. 
Hint : Two inputs – one at section engineer room and one at one at senior engineer room. 
Prefers combination of NO and NC Relays 
One output for motor. 

Suppose there are two engineers, a section engineer, and senior engineer. 
There is a switch on cabin room of each engineer. 
A yellow alarm should be turned on whenever, either section engineeror senior engineer is switch ON the motor.
But the red alarm should be turned onwhenever both engineers are switched ON the motor at the same time. 
The red alarm should be turned on when both engineers areout of station or absent. 
Hint : Two inputs – one at section engineer room and one at one at senior engineer room. 
Prefers combination of NO and NC Relays 
One output for motor. 

Look at the induction motor as shown. The direction of the motor is on clockwise direction when capacitor bank one is turned on and in anti-clockwise direction when capacitor bank two is turned OFF. 



Form a water level controlled motor using PLC
Hint: Two inputs, one high level sensor and one low level sensor.
One output: motor switch on.

 Consider an traffic island


The Signal L1-L3 is for north south direction and Signal L4-L6 is for east west direction. So as to meet the directional controls it should meat following criteria.
First Red one is switched ON.
Yellow two is switched ON.(Note that green two and red two should be turned OFF when yellow two is switched ON)
Green two is switched ON. (Note that yellow two and red two should be turned OFF when green two is switched ON).
The green one and yellow one should be at OFF state when green two and yellow two is turned on. 
Red two is switched ON.
Yellow one is switched ON.(Note that green one and red one should be turned OFF when yellow one is switched ON)
Green one is switched ON. (Note that yellow one and red one should be turned OFF when green one is switched ON).
The green two and yellow two should be at OFF state when green one and yellow one is turned on. 

In an industrial system, suppose the temperature is increased beyond a definite range. Temperature senor supplies a signal if the temperature exceeds. If the temperature is high for more than 5ms, an alarm should turn ON.

In an industrial system, suppose the temperature is increased beyond a definite range. Temperature senor supplies a signal if the temperature exceeds. If the temperature is high for more than 3ms, an alarm should turn ON. If the temperature should turn on for more than 5ms, the motor should be turned OFF.

Mostly industries, the starting of the machines needs some predetermined operation (like resources management, filling the furnaces, pretreatments of resurges etc). Design a system which switch ON a machine drive after five second after an input is given. This input should be high until an OFF button is pressed.

In many industries, there may occur some power failures. In such conditions, the motor cannot be shut of instant as the switch goes Logic LOW. It may need some time lag to switch OFF the motor. Once the input switched OFF, it should initiate an additional circuit system that may take necessary measures to switch off the motor and motor is switched OFF only afterseconds. 

Design a water treatment system which switches ON the motor for a definite time interval (5s) once the input switch is Set ON.

In many industries, there may occur some power failures. In such conditions, the motor cannot be shut OFF at the instant as the switch goes Logic LOW. It may need some time lag to switch OFF the motor. Once the input switched OFF, it should initiate an additional circuit system that may take necessary measures to switch OFFthe motor and motor is switched OFF only after some time period (say 7s).

Design a chemical plant where chamber 2 is filled with reagents in equal time intervals using actuating pumps V2.



Design a Push button mode conveyor system that brings some materials to and fro mode within definite time interval.   

Design astart – stop mode chemical plant where chamber 1 is filled with reagents H and N for a definite time interval by actuating V1. Once the chambers are filled for predetermined time interval, it is transferred to chamber 2 by actuating V2 for same time interval.

Design aPush button mode chemical plant where chamber 1 is filled with reagents H and N for a definite time interval by actuating V1. Once the chambers are filled for predetermined time interval, it is transferred to chamber 2 by actuating V2 for same time interval. 

Time multiplexing. Design a time multiplexed conveyer system between two conveyers. When one conveyer is working other should be closed and vice versa. It should reverse the directions once it reaches the end for a definite time period (5s). 

In many industries, the starting of machine system may be complex. It may require pressed starting and stopping conditions to be achieved which may require some time interval to start and stop the machines. In such conditions, the motor cannot be shut on or OFF instant as the switch goes Logic LOW or HIGH. It may need some time lag to switch ON/OFF the motor. Once the input switched ON/OFF as it should initiate an additional circuit system that may take necessary measures to switch ON/OFF the motor.


Design a PWM inverter for BLDC motor system.  

Design astart – stop mode PWM generator for a stepper motor system. 

Design apush button mode PWM generator for a stepper motor system. 

In a chemical reactor plant reactor , the operation is as follows …




There are two inputs Hydrogen and Nitrogen.
Once the reagent H and N are added through the inputs, corresponding sensors for H and N are switched ON.
When once H and N sensors are ON, valve to compressor section V1 should be ON for 5s .
During this operation compressor will compress and the fuels and then it should heat the gas for 2s.
After this operation compressor should be switched OFF.
Then a valve V2 is opened for 2s and reagents are allowed to react each other in the plant for 1000ms.
The resultant product is formed at catalyst chamber and they are transferred to cooling chamber. 
Then the valve V3 is switched ON, the resultant product is cooled for 5s and the valve V4 is turned ON.
Simultaneously the feedback loopV5 is arranged.  
Set up a car parking mechanism.

Design a chemical plan system as follows.

The reagents H2 and N2 is added to the chamber by actuating the V1. The system is switched on if and only if the both H2 and N2 is added. The amount of regent added is verified using a Load cell counter. Once If sufficient amount regent is added to the chamber (say greater than 5gms), the chamber should be thermally treated for 5 seconds. Then it is compressed and moved to second chamber using valve V2. The amount of regent added is verified using a Load cell counter. Once sufficient amount regent is added to the chamber (say greater than 4gms), the chamber should be thermally treated for 5 seconds and moved to chamber 3 using valve V3. Then the ammonia drain is thermally retreated by cooling for five second and heating for 3seconds again and again. 



Chemical Plant

