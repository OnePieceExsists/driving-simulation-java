Driving Simulation (Java)

A simple console-based driving simulator written in Java.
This project simulates basic car operations such as starting the engine, changing gears, accelerating, and braking using a menu-driven interface.

Features
Turn the engine on/off
Change gear (P, D, R)
Accelerate the car
Brake to reduce speed
Interactive dashboard menu
Input-based simulation through the console
Project Structure
DrivingSimulation
│
├── src
│   ├── Main.java
│   └── DrivingSimulationSolution.java
│
├── .gitignore
└── README.md
How It Works

The simulation continuously displays a car dashboard showing:

Current speed
Engine status (On / Off)
Current gear

Users interact with the simulator by selecting options from the menu.

Example menu:

------ Car Dashboard ------
Speed: 0
Engine: Off
Gear: P

Menu:
1. Turn on/off the engine
2. Change gear (P, D, R)
3. Accelerate
4. Brake
5. Exit
Program Logic
Engine Control

The engine state toggles between On and Off.

Gear System

The car supports three gears:

P – Park
D – Drive
R – Reverse
Acceleration

The car can accelerate only if:

The engine is on
The gear is not in Park

Speed increases by 10 units.

Braking

Braking is allowed only if:

The engine is on
The speed is greater than 5

Speed decreases by 5 units.

Exit

The simulation ends when the user selects option 5.

Example Run
------ Car Dashboard ------
Speed: 0
Engine: Off
Gear: P

Enter your choice: 1
Engine is now On

Enter your choice: 2
Enter gear (P, D, R): D
Gear changed to D

Enter your choice: 3
Car accelerated. Current speed: 10
