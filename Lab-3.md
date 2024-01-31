Welcome to the BAE305-SP24-Lab3 wiki!

# Lab 3 – Let’s Switch: Transistors as Switches 

# By: Noah Lane and Lily Schlaug
# Summary
Lab goal; summary of work performed; summary of outcome
Lab 1 will be somewhat different since this is an introduction to the equipment.
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
1. Connect the 270Ω, LED, and switch in series on a solderless breadboard
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
How did you test the system to get your results
# Test Results
What are your results?
# Discussion
Did you make any design decisions that had an impact on the results? How did they impact the results? What do the results mean?
# Conclusion