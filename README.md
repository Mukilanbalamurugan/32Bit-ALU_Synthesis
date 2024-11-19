# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :![4th OP](https://github.com/user-attachments/assets/34ac75ef-5ac7-4eaf-b1ce-ec5c9bf08a37)


#### Area report:![4th area](https://github.com/user-attachments/assets/253a3851-b8c4-4dfe-b37b-e8883a7db84e)


#### Power Report:![4th power](https://github.com/user-attachments/assets/61dc7d3a-4d92-4e27-99d9-e027078eb86a)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
