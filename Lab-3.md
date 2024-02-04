Welcome to the BAE305 SP24 Lab3 wiki!

# Lab 3 – Let’s Switch: Transistors as Switches 

# By: Noah Lane and Lily Schlaug
# Summary
The goal of this lab was to introduce diodes and transistors into a circuit. We began by building a circuit with a switch and measured a variety of elements within the circuit with the DMM. Then, the circuit was rebuilt to include a bipolar junction transistor to illustrate how this element also acts as a switch. Voltages at several test points were taken and compared to the previous circuit to show how the LED driven by a transistor arrangement operated. Diodes and LEDs were also used throughout the duration of the lab to allow a visual indication of when current was flowing. Then, a circuit was built to control the LED using a potentiometer. The voltages at a variety of points were measured when the LED was bright, dim, and at two midpoints. Finally, a circuit was built to include a motor from our SparkFun Inventor's kit. At the motor driving circuit portion of the lab, time ran out and we were not able to measure any values in the circuit. 

# Materials
2.2Ω, 270Ω, 1kΩ Resistors

1x LED

1x sliding switch (from the Sparkfun inventor’s kit) 

1x electric motor (from the Sparkfun inventor's kit) 

1x NTE 125 diode 

1x 1kΩ trimmer potentiometer 

1x TIP31C transistor 

1x Solderless Breadboard
# Assembly Procedures
**Part 1-LED Driving Circuits**
1. Connect the 270Ω resistor, LED, and switch in series on a solderless breadboard
2. Connect the positive terminal of the DC Power supply before the 270Ω resistor and the negative terminal after the switch

**Image of Part 1 Circuit**
![IMG_8435](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371043/256f2a44-f19f-4589-b9d7-6fcb897c9170)

**Part 1-Step 3**
1. Using the same series circuit described in Part 1 replace the switch with the TIP31C transistor with the LED connected to the collector connection 
2. Connect the following series circuit to the base connection of the transistor: switch and 1KΩ resistor
3. Connect the main DC output before the 270Ω resistor, a 5VDC output before the switch, and ground the emitter connection of the transistor

**Image of Part1-Step 3 Circuit**
![IMG_8434](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371043/0ff0e919-dca2-49db-bd58-b988442a5b48)

**Part 1-Step 4**
1. Beginning with the circuit from Part 1-Step 3, Remove the series branch from the transistor base connection
2. Attach the 1KΩ resistor to the base connection with the following parallel branch attached: 1KΩ resistor
3. Apply a 5V DC output on one end of the parallel branch resistor and a ground on the opposite end

**Image of Part 1-Step 4 Circuit**
![IMG_8433](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371043/73e9a485-0c0c-4d56-8847-8258504de169)

**Part 2-Motor Driving Circuit**
1.Begin with the circuit from Part 1-Step 3
2. Remove the LED and replace it with a parallel loop in series that includes a diode and the electric motor
3. Replace the preceding 270Ω resistor before the loop with a 2.2Ω resistor

**Image of Part 2 Circuit**
![IMG_8432](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371043/b2bb34a6-ac43-4cae-9638-0c84f1267150)

# Test Equipment
Global Specialties 1403 DC Power Supply

Fluke 87 Digital Multi-meter

# Test Procedures
The first step before building any circuits was to measure the actual value of all resistors. See values below in table 1. 
 
Then, the LED driving circuit was built. Voltage was measured at T1, T2, T3, T4 with respect to ground. Voltage across R1, LED1, & S1 should be measured by putting the DMM in parallel with the element of the circuit at the point of interest. Values at each of these points were taken with the switch both closed and open. Next, current was measured with the switch both on and off through LED1. This should be done by placing the DMM in series with the LED. See table 2 for the measurements from this portion of the lab.
 
Next, the LED driven by a transistor with a fixed current was built. Voltage was measured at T1, T2, T3, T4, T5, T6, & T7 with respect to ground. Voltage across R1, LED1, S1, & R2 should be measured by putting the DMM in parallel with the element of the circuit at the point of interest. Values at each of these points were meant to be taken with the switch both closed and open. Current was meant to be measured with the switch both on and off through LED1 & R2. This should be done by placing the DMM in series with the LED. See table 3 for the measurements from this portion of the lab.



# Test Results
The table of actual values of resistors for this lab are shown below in table 1.

![image](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371115/8a82792c-3236-4779-9c5d-35d66bbba159)

LED Driving Circuit measurements: 

Note: For this portion of the lab, the switch off was not enough current to turn on light but enough to generate a voltage drop 1.5V. The voltage across the led: 2.046 V, Resistor: 267 ohm, V/R=I, I = 7.7 mA. 

![image](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371115/59667659-5a70-4772-85d3-d72df5dc6d30)

LED driven by a transistor with a fixed current: 

Note: For this portion of the lab, we did not have enough time to complete all the switch on measurements. 

![image](https://github.com/npla225/BAE305-SP24-Lab3/assets/156371115/aefbb6e6-93a8-42f1-868a-88258c633d7e)

# Discussion
Discussion Question 1: How does the current through the LED compare between circuits 1 and 2?

The current through the LED between circuits 1 and 2 are the same. 

Discussion Question 2: The datasheet mentions a maximum voltage drop (VCE) of 1.2V at saturation. We would like a much smaller value, such as the fraction of a volt that you measured in the first circuit across the switch, S1, when it is on. How does your measured VCE compare to the one listed in the datasheet? Do you think we are operating this transistor in the saturation region?

The Vce measured was 0.024 V, so it is much lower than the 1.2 V that is reported in the datasheet. This means that we are not in the saturation region because the transistor is not working at or near its maximum potential. 

# Conclusion