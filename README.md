# Car-Automation-Using-Industrial-Robotic-Arms
Overview

This project showcases a mini car manufacturing process using industrial robotic arms, specifically Dobot 4-axis robotic arms. Designed for the Thrissur Motor Show 2024, this demonstration illustrates how car manufacturing companies use collaborative robotic arms for various stages of car assembly. The project employs four Dobot robotic arms and a linear rail system to automate the assembly and disassembly of a car model.


Project Description

Objective: 
To create a miniaturized, automated car assembly line that demonstrates the capabilities of industrial robotic arms in car manufacturing processes.

Features:
Robotic Arms: Four Dobot 4-axis robotic arms equipped with suction cups to handle car body parts.
Linear Rail System: A rail system that moves the car base to specific points, triggering the robotic arms to perform assembly operations.
Proximity Sensors: Sensors positioned along the rail to detect the car base and activate the robotic arms at the correct positions.
Automated Assembly: The robotic arms pick up and attach car parts to form a complete car body.
Automated Disassembly: After a delay, the robotic arms disassemble the car parts, and the rail system returns to the initial position to repeat the process.

Components:
Dobot 4-Axis Robotic Arms: Robotic arms capable of precise movements, each equipped with a suction cup to handle car parts.
Linear Rail System: A motorized rail that moves the car base along a predefined path.
Proximity Sensors: Sensors to detect the position of the car base and trigger robotic arm actions.
Microcontroller: An Arduino or similar microcontroller to control the rail system.
Dobot Studio Software: Used to program and control the Dobot robotic arms with Blockly block code.
Power Supply: Adequate power supply to ensure smooth operation of the robotic arms and rail system.

Software and Control:
Programming Language: The Dobot robotic arms are programmed using Blockly block code in the Dobot Studio software.
Control Logic: The microcontroller receives input from the proximity sensors and controls the movement of the linear rail, while the Dobot arms are controlled through Dobot Studio.
Automation Sequence: A predefined sequence for assembly and disassembly is programmed to demonstrate continuous operation.

How It Works

Initialization: The system initializes, setting the robotic arms and linear rail to their starting positions.
Movement: The linear rail system moves the car base to the first assembly point.
Detection: A proximity sensor detects the car base's position, triggering the robotic arms.
Assembly: Each Dobot robotic arm picks up a car part and attaches it to the car base, forming a complete car body.
Pause: The system pauses briefly to allow viewers to observe the assembled car.
Disassembly: The robotic arms disassemble the car parts and return them to their initial positions.
Reset: The linear rail returns to the starting position, and the process repeats.

Applications:
This project serves as an educational demonstration of automation in car manufacturing. It highlights the precision, efficiency, and capabilities of robotic arms in industrial applications.

Future Improvements:
Enhanced Automation: Integrate more complex robotic movements and additional sensors for a more detailed assembly process.
Real-Time Monitoring: Add a monitoring system to provide real-time feedback on the assembly process.
Advanced Control Systems: Implement advanced control algorithms for smoother and more efficient operation.


