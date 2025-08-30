# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
![image](https://github.com/user-attachments/assets/6fe3965a-47de-47d4-9dd1-0d52054de81b)


### 2. Schematic of Full Custom 2:1 MUX
![WhatsApp Image 2025-08-30 at 14 20 41_03f60bac](https://github.com/user-attachments/assets/17fcf68a-9d3e-4119-9dc9-09eb3dc65799)


### 3. Transient Response Setup

![WhatsApp Image 2025-08-30 at 14 20 26_6473abe8](https://github.com/user-attachments/assets/b99da87b-ab3d-438c-aac6-aa9d037dadc4)


![WhatsApp Image 2025-08-30 at 14 20 34_58135892](https://github.com/user-attachments/assets/901a6180-81cc-4d53-951c-ad1364d38b81)



## Output

### 1. Transient Analysis Output
![WhatsApp Image 2025-08-30 at 14 20 22_c2b2c449](https://github.com/user-attachments/assets/d8d676b3-7944-4f2d-b24b-94f11cfd432a)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
