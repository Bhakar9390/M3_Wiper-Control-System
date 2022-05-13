# INTRODUCTION:
* Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic wiping system, to improve the system by using sensor with actuator and to design a basic program that will fully operate with the system. The concept of this proposed wiper system is similar with other existing conventional wiper. In spite of removing water from windscreen, this system also will be upgraded to an automatic control system by using a Peripheral Interface Controller (PIC) 16F877A controller and water sensor. As the conclusion for the project, the results shows all the aim objectives are successfully achieved. The wiper system was well functionally according the water condition from the outside of a car. This project showed a contribution on the design of the automatic wiper system for the future research in this same field. It is recommended that the system to have a study on the wiper material that been used to make a wiper because the driver at hot and climate country are facing the problems regards to the wiper material.

# COMPONENTS AND SUPPLIES:

 1. STM32F407 Discovery Board
 2. LEDs
 3. Push Button
 4. Resistors
 5. Power Supply

 # Description
 
   1. STM32F407VG
 
 * The STM32F405xx and STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded

  2. LED
  
  * A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons

   3. Push Button
  
  * Push buttons can be explained as simple power controlling switches of a machine or appliance. These are generally metal or thermoplastic switches that are    intended to grant easy access to the user.
  
   4. Resistors
  
  * A resistor controls the flow of the electrical current within a circuit. Resistors are made from materials like copper or carbon, which make it difficult for the electrical charges to flow through a circuit.
  
   5. Power Supply
  
  * A power supply is an electronic circuit that converts the voltage of an alternating current (AC) into a direct current (DC) voltage. It is basically consisting of the following elements: transformer, rectifier, filter and regulator circuits.

# ADVANTAGES:
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* It is quite simple to use.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* Individual rain sensors are fairly inexpensive.
* Rain sensor-based systems are extremely simple to install.
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.

# DISADVANTAGES:
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.
* The entire system cost rises when more components, including a rain sensor, are required.
* When water falls squarely on the rain sensor, the mechanism activates.

# 4W & H (WHO,WHAT,WHEN,WHERE,HOW):

# WHAT:
* The functional speed of a vehicle wiper is constrained by a wiper speed control instrument in view of downpour conditions. To produce, the control framework consolidates a downpour sensor (30) that identifies downpour conditions. The adequacy of a simple sign relies upon the identified downpour conditions.

# WHY:
* To keep the windscreen clean enough to give adequate view at all times. 
* The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.

# WHO:
* A wiper speed control system for an automobile manages the wiper's functioning speed in response to weather conditions.

# HOW:
* You can adjust the speed of the car wiper system according to the rainfall.

# HIGH LEVEL REQUIREMENTS:

 | ID     | Description                   | Status      |
 | -----  | -----------                   | ----------- |
 | HL1    | car wiper using STM32F407VG   | Implemented |
 | HL2    | Led glowing in sequence       | Implemented |
 | HL3    | Car on and off                | Implemented |
 
# LOW LEVEL REQUIREMENTS:

  |ID	     |Description	        |Status     |
  | -----  | -----------        | ----------|
  |HL1-LL1	|Push Button	        |Implemented|
  |HL2-LL2	|Red,Green,Blue Leds |Implemented|
  
# SWOT ANALYSIS:
# STRENGTH:
* Good Reputation
* Big Influence on the Market
* High Bargaining Power Supliers
* Low Budget

# WEAKNESS:
* Week Focus on Process Innovations
* High Transaction Cost
* Structural Inertia
* No Focus on Private Sector

# OPPRONUTIES:
* Technological Lock in of Product
* Technological Development
* Demand for Saver Equipments
* Emerging New Markets

# THREATS:
* Highly REgulated Industry
* Ethical Pressure
* Low Bargaining Power Buyers
* Econimical Crisis

# Exploring STM32F407 Discovery Board:
![image](https://user-images.githubusercontent.com/101699116/168215005-061df6d3-4596-4639-8eea-13b069ee27cb.png)

This venture gives practically all the fundamental data expected to begin with STM32F407 Discovery Board and furthermore advancement of driver code.
* Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY
* Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE
* For installation of STM32CubeIDE refer Youtube
* Note : As this microcontroller has many advanced features and the main aim of this project is to get all basic insights, during the driver development only the required functionalities are added and other advanced functionality is not added. I may update the driver and other functionality in the future.
Please find the STM32F4 Discovery User Manual,STM32F4xxx Reference Manual (RM0090) and other related documents inside a folder called Documents. I will be referring to these documents for information such as block diagrams, register details ect.
