Integrated Situation:  Smart Water Management System 
The WASAC company aims to design a smart water management system that allows users to remotely 
monitor their daily water consumption and manage their balance efficiently. Through an online platform, users 
can track their water usage and set a maximum daily consumption limit. 
The system is designed to automatically close the water valve when: 
1. The user’s balance reaches zero. 
2. The daily preset consumption limit is exceeded. 
With edge processing, these decisions can be made locally, even when the system is offline. 
Prototype Simulation 
To develop the system, the research team plans to simulate a basic prototype using an ESP32 microcontroller 
in VS Code. The initial simulation will involve: 
• Three houses connected to a single ESP32. 
• Three buttons to decrease each user's balance (representing water usage in liters). 
• Three buttons to increase each user's balance (representing balance top-up in liters). 
• Two Led (red for balance zero and green balance greater that zero)  
• A monitoring platform that displays real-time water consumption and user balances. 
Tasks: As one of research team 
1. Simulate the prototype using Wokwi Simulator via VS code and use Google cloud as database. 
2. Deploy the project on GitHub page and provide the link (to monitor three users as illustrated). 
3. Enhance the simulation by replacing Wokwi with Proteus simulator: 
o Use one keypad for balance entry. 
o Integrate a flow sensor to track water usage and debit the balance accordingly. 
o Display real-time balance on an LCD. 
o Use LED indicators: 
▪ Red LED → Balance is zero (valve closed). 
▪ Green LED → Balance is greater than zero (valve open). 
4. Describe the system improvements requirements to make the solution more realistic for community 
deployment, both in terms of: Hardware, software and Platform in general. 
