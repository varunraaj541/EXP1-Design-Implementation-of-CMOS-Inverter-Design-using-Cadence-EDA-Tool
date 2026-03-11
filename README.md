# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image](https://github.com/user-attachments/assets/e3e06487-52b2-4b56-9dcd-03c5c9394a4c)


#### 2. Schematic of CMOS Inverter:

   ![WhatsApp Image 2026-02-02 at 3 10 56 PM](https://github.com/user-attachments/assets/94cca60c-696d-4029-853a-6fb2e7f5a1d1)


#### 3. Transient Response Setup:

![WhatsApp Image 2026-02-02 at 3 12 33 PM](https://github.com/user-attachments/assets/ebab82b8-0113-4307-9062-fe32195199e2)


![WhatsApp Image 2026-02-02 at 3 12 07 PM](https://github.com/user-attachments/assets/1c9def52-0179-4783-a47e-f5ffa93965de)


![WhatsApp Image 2026-02-02 at 3 11 27 PM](https://github.com/user-attachments/assets/dc07d66a-05f1-4633-9f43-60a7817d253e)





## Output
#### 1.Transient Analysis Output

 ![WhatsApp Image 2026-02-02 at 3 10 24 PM](https://github.com/user-attachments/assets/95bc7dac-76fc-4228-a14c-4f07627c4871)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











