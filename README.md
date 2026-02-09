# RVM Evidence

### Contents

1. [FR1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR01) - The software shall create a map of the environment.
    1. [PR1.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR01/PR01.1) - The map shall cover the operational area (≈ 3750 mm x 6500 mm).
2. [FR2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR02) - The software shall determine the robot’s position within the environment.
    1. [PR2.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR02/PR02.1) - The system shall record and recall the starting position.
3. [FR3](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR03) - The software shall detect and classify objects in the environment.
    1. [PR3.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR03/PR03.1) - The vision system shall detect colours in the hue ranges (red/yellow/purple).
    2. [PR3.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR03/PR03.2) - The vision system shall detect blocks of the specified size and shape.
    3. [PR3.3](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR03/PR03.3) - The software shall detect and classify objects in the environment.
4. [FR4](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR04) - The robot’s manipulator shall be able to grip a coloured block and lift it.
    1. [PR4.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR04/PR04.1) - The manipulator’s end-effector shall grasp blocks with 6 flat sides.
    2. [PR4.4](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR04/PR04.4) - The manipulator shall lift a payload of up to 125 g.
5. [FR5](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR05) - The robot shall remain within an operational footprint usable for navigation.
    1. [PR5.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR05/PR05.1) - Added components shall remain within ≤ 475 mm width (excluding extended manipulator).
6. [FR6](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR06) - The robot and its manipulator shall not tip over.
    1. [PR6.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR06/PR06.1) - At 280 mm reach carrying payload, no wheel lifts.
    2. [PR6.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR06/PR06.2) - Manipulator mounting remains mechanically connected.
7. [FR7](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR07) - The software shall navigate between locations.
    1. [PR7.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR07/PR07.1) - The robot shall autonomously navigate to unknown areas.
    2. [PR7.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR07/PR07.2) - The software shall plan collision-free paths.
8. [FR8](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR08) - Power consumption shall allow full task duration.
    1. [PR8.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR08/PR08.1) - The rover battery shall support ≥ 20 minutes of operation.
    2. [PR8.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR08/PR08.2) - High-power hardware shall use separate power source.
9. [FR9](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR09) - The robot shall accept user inputs.
    1. [PR9.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR09/PR09.1) - The robot shall accept Start and Stop commands.
    2. [PR9.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR09/PR09.2) - The robot shall provide an emergency-stop function.
    3. [PR9.3](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR09/PR09.3) - Manual override shall be available via dedicated channel.
    4. [PR9.4](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR09/PR09.4) - Emergency-stop shall be physically accessible and functional at all times.
10. [FR10](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR10) - The Intel NUC shall communicate with the Leo Rover and myCobot.
11. [FR11](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR11) - Ethernet shall be used for primary links.
    1. [PR11.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR11/PR11.1) - Ethernet cable lengths shall not exceed 3 m.
13. [FR13](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR13) - The system shall allow rapid setup, teardown, and removal of subsystems.
    1. [PR13.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR13/PR13.1) - Setting up or tearing down the system shall take ≤ 15 min.
14. [FR14](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR14) The system shall provide safe and manageable cabling and connectors.
    1. [PR14.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR14/PR14.1) - External cables shall be routed to avoid obstructing subsystems.
    2. [PR14.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR14/PR14.2) - No exposed high voltage (≥ 24 V) wiring shall be present.
15. [FR15](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR15) - Removable and labelled connectors shall be used to allow fast setup and teardown.
    1. [PR15.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR15/PR15.1) - Connect/disconnect time for each cable shall be ≤ 2 minutes.
    2. [PR15.2](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR15/PR15.2) - Connectors shall be labelled.
16. [FR16](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR16) - The system shall provide accessible inspection and maintenance points.
    1. [PR16.1](https://github.com/Team4-UoM-RSDP/rvm_evidence/tree/main/FR16/PR16.1) - Routine inspection points shall be reachable without disassembling the whole system.



###### Team 4 – AERO62520 Robotic System Design Project 
