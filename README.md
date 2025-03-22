# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools
## Aadhithya SV
## 212223060001

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

### 1. Schematic of Full Custom 2:1 MUX
![WhatsApp Image 2025-03-22 at 16 53 46_69cc8465](https://github.com/user-attachments/assets/1434e547-79b0-461d-b751-63d632638f51)


### 2. Transient Response Setup

*![image](https://github.com/user-attachments/assets/47f7be45-4763-4d32-9eae-c417d1b7d501)*

![WhatsApp Image 2025-03-22 at 16 53 02_7edfdd9b](https://github.com/user-attachments/assets/844d113c-1807-4bcd-b295-da8e0d22ce75)



## Output

### 1. Transient Analysis Output
![WhatsApp Image 2025-03-22 at 16 52 19_64bfd42a](https://github.com/user-attachments/assets/b2c18bec-039f-46b3-a1de-25070ace2d5c)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
