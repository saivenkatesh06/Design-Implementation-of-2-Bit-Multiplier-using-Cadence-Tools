# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:
<img width="1919" height="1190" alt="553301136-8d466eac-01d1-4b7e-8713-f6a7f3c815a8" src="https://github.com/user-attachments/assets/4f082747-0f66-41a4-aba4-7d4c15c227b5" />
<img width="1916" height="1199" alt="553301180-7f292389-529a-4a47-ba55-cf60a5ae5a7e" src="https://github.com/user-attachments/assets/21f2772f-c7cd-4d2b-bc86-d3f0f65fe30c" />



### Schematicand Symbol of 2-Input EX-OR Gate:
<img width="1919" height="1199" alt="553301289-6fa05ad3-ff53-4b74-98dc-78c29e581455" src="https://github.com/user-attachments/assets/7385aeb0-aaa1-44a3-99c3-73818d554b12" />
<img width="1919" height="1199" alt="553301265-4a88d9dd-c65f-49a7-b9b6-c5832a4a32ca" src="https://github.com/user-attachments/assets/0095bfb3-36a8-4b86-974e-3d0e03f3ddbd" />


### Schematicand Symbol of Half Adder:
<img width="1918" height="1199" alt="555152280-d83a0f86-146d-4a5a-929f-a55997e9fab7" src="https://github.com/user-attachments/assets/a949f907-a2a7-4547-bac0-1d61117be788" />
<img width="1919" height="1199" alt="555152413-21c68bb2-7c2f-460b-a4e6-08c7aa267961" src="https://github.com/user-attachments/assets/9517f423-2922-4537-ac89-fd24c5404289" />


### Schematic of 2-Bit Multiplier:
<img width="1919" height="1199" alt="555152536-5fd78189-5dfe-4c26-9e74-08aaa3d7b618" src="https://github.com/user-attachments/assets/82bc864c-4c3f-4aae-bc42-f0bf09204ba6" />

## Output
### Transient Analysis Output:
<img width="866" height="698" alt="555152850-eccf0346-b605-4cef-90ef-639755e3eead" src="https://github.com/user-attachments/assets/111c0b9a-b4a4-4de5-b8a1-69dfdb42f5c8" />
<img width="966" height="236" alt="444249229-55864d90-af08-4836-bc90-4cbba80573f8" src="https://github.com/user-attachments/assets/c3473cba-ec64-4b14-8ade-ad1fa29a0c6d" />

<img width="1918" height="1199" alt="555153056-cad2be82-a611-41bc-9966-913f21b79c8f" src="https://github.com/user-attachments/assets/59b4e8d6-9e18-4afe-931b-2eee5215cfb0" />
Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
