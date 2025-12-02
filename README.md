Robot Vacuum 🧹🤖
Overview

<img width="1118" height="568" alt="Screenshot 2025-12-01 4 07 03 PM" src="https://github.com/user-attachments/assets/08570733-62fd-467f-a776-6d05fb4a2761" />


Features

3D-printed chassis/enclosure — optimized for standard printer beds or split across multiple parts.

Dual-purpose cleaning: mechanical sweeping in front + vacuum suction with impeller-driven motors.

Dust and debris collection chamber, with a filter and sealed container to hold debris.

Two-wheel drive using standard hobby motors for locomotion.

Vacuum function powered by two high-RPM hobby motors with custom impellers.

Obstacle/wall detection using distance sensors arranged ~45° apart for more reliable detection and navigation.

Compact form factor — aiming for a robot roughly 10 in (~25 cm) in diameter.

Status & Work Completed

✅ CAD design has been completed: enclosure, dust chamber, sweeper compartment, wheel placement, and parts layout.

✅ Sweeper + dust-chamber layout done; filter and container selected.

✅ Initial prototype printed, though size constraints prompted reevaluation (target diameter increased).

🛠️ Vacuum chamber designed (using airtight container + air filter).

🔧 Prototyping in progress; early prints show structural layout and part alignment.

How It Works

Movement — Two standard hobby motors drive the wheels, allowing the robot to move around.

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

Build Requirements
Component Type	Example / Notes
3D Printer & Filament	For enclosure, chassis, mounts
Hobby Motors (for wheels)	2-wheel drive motors
High-RPM Motors + Impellers	For vacuum suction
Dust Container + Air Filter	Airtight container + standard air filter
Microcontroller (e.g. Arduino Nano)	Control motors, sensors, logic
Distance / Proximity Sensors	for obstacle detection/navigation
Power Source / Battery Pack	Sufficient to run motors + controller
Screws / Fasteners / Wiring	Assembly and connections
(Optional) Motor Drivers / MOSFETs	For motor control/power switching
Why This Project / Motivation
