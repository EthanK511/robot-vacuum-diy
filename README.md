Robot Vacuum 🧹🤖
Overview

This is a custom robot vacuum cleaner — designed and built from scratch using mostly 3D-printed parts and components on hand. The vacuum will have both sweeping and vacuuming capabilities. The design is fully custom and aims to build a functional autonomous cleaning robot.

Features

3D-printed chassis/enclosure — optimized for standard printer beds or split across multiple parts.

Dual-purpose cleaning: mechanical sweeping in front + vacuum suction with impeller-driven motors.

Dust and debris collection chamber, with filter and sealed container to hold debris.

Two-wheel drive using standard hobby motors for locomotion.

Vacuum function powered by two high-RPM hobby motors with custom impellers.

Obstacle / wall detection using distance sensors arranged ~45° apart for more reliable detection and navigation.

Compact form factor — aiming for a robot roughly 10 in (~25 cm) diameter.

Status & Work Completed

✅ CAD design has been completed: enclosure, dust chamber, sweeper compartment, wheel placement, and parts layout.

✅ Sweeper + dust-chamber layout done; filter and container selected.

✅ Initial prototype printed, though size constraints prompted reevaluation (target diameter increased).

🛠️ Vacuum chamber designed (using airtight container + air filter).

🔧 Prototyping in progress; early prints show structural layout and part alignment.

How It Works

Movement — Two standard hobby motors drive the wheels to allow the robot to move around.

Cleaning

Sweeping: A brush/sweeper at the front sweeps loose dust/debris into a dust-chamber.

Vacuum suction: Two high-RPM motors with custom impellers will create suction, pulling debris into the dust chamber.

Dust collection — Debris is collected in an airtight container with a filter to prevent dust escape.

Navigation / Obstacle detection — Distance sensors detect walls/obstacles to avoid collisions and enable autonomous (or semi-autonomous) navigation.

Project Structure

CAD files — 3D enclosure, chassis, sweeper mount, wheel mounts, dust chamber layout.

Electronics — Arduino Nano (or equivalent microcontroller), motor driver(s), distance sensors, wiring harness, power supply.

Mechanical parts — Wheels & motors, sweeper/bristle or brush module, impeller motors for vacuum, airtight container + dust filter.

Firmware / Control Logic — code for motor control, sensor reading, navigation logic, vacuum operation on/off, safe stopping/obstacle avoidance.

What’s Next

Print final enclosure pieces (possibly in multiple parts and assemble).

Assemble mechanical components: wheels, motors, sweeper, vacuum motors, dust chamber.

Wire electronics: motor drivers, microcontroller, sensors, power.

Write control firmware / logic for basic autonomous movement + cleaning.

Test vacuum suction, sweeping efficiency, dust-chamber containment, obstacle avoidance.

Iterate design (CAD & mechanical) to improve reliability, battery power, cleaning effectiveness.

Build Requirements
Component Type	Example / Notes
3D Printer & Filament	For enclosure, chassis, mounts
Hobby Motors (for wheels)	2-wheel drive motors
High-RPM Motors + Impellers	For vacuum suction
Dust Container + Air Filter	Airtight container + standard air filter
Microcontroller (e.g. Arduino Nano)	Control motors, sensors, logic
Distance / Proximity Sensors	For obstacle detection/navigation
Power Source / Battery Pack	Sufficient to run motors + controller
Screws / Fasteners / Wiring	Assembly and connections
(Optional) Motor Drivers / MOSFETs	For motor control/power switching
Why This Project / Motivation

I wanted to build a home-made cleaning robot using parts I already own (or can 3D print), to explore robotics, mechanical design, 3D printing, embedded control, and real-world problem solving. The project gives experience in CAD, PCB/electronics (or wiring), firmware logic, and mechanical engineering — all in one.

It’s also a practical device: a functioning robot vacuum that could help automate floor cleaning.

License / Attribution

Feel free to use, modify, and build upon this work. If you share or publish your version, please credit the original creator.
