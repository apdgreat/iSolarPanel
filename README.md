# iSolarPanel
Deloitte technoutsav challenge
TEAM TECH_ISM
INTRODUCTION TO THE PROBLEM

Solar energy is the energy of the future. It is an important source of renewable energy and its technologies are broadly characterized as either passive solar or active solar depending on how they capture and distribute solar energy or convert it into solar power.
Solar power is anticipated to become the world's largest source of electricity by 2050. Commercial concentrated solar power plants were first developed in the 1980s.
However, the efficiency of these solar plants are not high due to several geographical reasons which we can’t control but there are other reasons too for the low efficiency of solar plants i.e
1.Non-alignment to the direct ray of the sun. To get maximum output out of the incoming sun rays the solar plates must be perpendicular to the incoming rays of the sun.
2. In large Solar plants due to daily pollution also plays a role in reducing the efficiency of solar plates by adding a layer of dust particles over the plates which ultimately reduces the energy tapping efficiency of the solar plates.
                 

SOLUTION
1. To maintain the alignment we use Robot Process Automation by deploying the whole solar plate on dual-axis stand attached to a industrial class servo motor with LDR(Light detecting Resistor) on all the four corners of the solar panel which will align the solar plate perpendicular to the incoming rays of sun as the resistance of LDR decreases with increasing intensity of light on it. So, All 4 LDR will be connected to Arduino UNO which will give the processed output to the Servo motors to maximize the output of the Solar plate through my algorithm.


2. For the cleaning process, we need to deploy a cleaning mechanism that cleans the whole plate neatly removing all the dust particles and covers the minimal surface of the plate. To do this we plan on using a driver-motor as used in CD drives with a wiper that will go hence and forth cleaning the whole plate. The most interesting part is that this feature will IoT enabled with the help of NodeMcu (wifi-based). All the cleaning mechanism will be activated through an ESP8266 Microcontroller which is a wifi-based micro-controller and will be connected to the Wifi or the local Server. We will create a response website on accessing the IP address of the NodeMcu where you can select the solar plate to be cleaned from any part of the world and it will be cleaned.   

MARKET VALUE
Solar energy is a valuable source of energy and the percentage of total solar energy used to produce electricity to the total energy produced in the world is increasing leaps and bounds by every year. As the energy consumption rate is increasing every day and due to depreciating resources of fossil fuels and the pollution caused by them which are leading to many climatic changes, Global Warming is one of them. There is an urgent need to shift our current focus to renewable energy sources and Solar energy is top among them.
Bigger players are trying to enter the energy domain nowadays but the current efficiency of solar plates is about 17 % to 19% which is a setback but after implementing the above two solutions, the efficiency is gonna increase and manual labours required to clean the solar plates then and now will reduce considerably. Thus making it a more profitable venture for the companies who set up solar fields in hundreds of acres. This will encourage more big players to enter in this field and ultimately fulfil our goal of Green Energy.

HARDWARE REQUIREMENTS
ESP8266(WiFi)
ARDUINO UNO
SERVO MOTOR
LDRs
SCREW STEPPER MOTOR
SOLAR PLATE
WIPER
TOTAL COST INCURRED-Rs.10000-Rs.15000
