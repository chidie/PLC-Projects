# 🧪 Hydrogen Tank Filling PLC Project

![Filling Hydrogen Tank](images/filling-hydrogen-tank.png)

## Project Overview
This project showcases a complete automation solution for filling a hydrogen tank using a PLC system. It integrates simulation, control, and visualization tools to demonstrate a real-world industrial process.

## 🛠 Tools & Technologies
- **Connected Component Workbench (CCW)**: Used to design the ladder logic for the PLC controlling the tank filling sequence.
- **Factory I/O**: Simulates the physical hydrogen tank setup and interacts with the PLC logic in real time.
- **Cogent DataHub**: Facilitates OPC DA/UA communication between Factory I/O and other systems.
- **Ignition Gateway & Designer**: Builds the SCADA interface for monitoring and controlling the process.

## Workflow Summary
1. **PLC Programming**  
   Ladder logic is developed in CCW to manage valve operations, level sensors, and safety interlocks.

2. **Simulation**  
   Factory I/O provides a 3D simulation of the hydrogen tank filling station, connected to the PLC via OPC.

3. **OPC Integration**  
   Cogent DataHub bridges the OPC DA/UA protocols, enabling seamless data exchange between Factory I/O and Ignition.

4. **SCADA Design**  
   Ignition Designer creates a dynamic SCADA dashboard for real-time monitoring and control.

## Features
- Real-time tank level visualization
- Start/Stop control for filling process
- Alarm handling and safety interlocks
- OPC-based data communication
- Interactive SCADA dashboard



## 📌 Notes
- Ensure OPC connections are correctly configured in Cogent DataHub.
- Factory I/O must be set to external OPC mode.
- Start Ignition Gateway before launching the Designer.
