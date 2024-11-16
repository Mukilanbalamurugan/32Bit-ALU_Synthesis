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

#### Synthesis RTL Schematic :![5th OP](https://github.com/user-attachments/assets/e05dc858-0757-43f6-9d46-5e77c75d74d3)


#### Area report:![5th area](https://github.com/user-attachments/assets/808ff0c4-c204-45b4-a31f-faa05bc5c69c)
### Time Report:![5th time](https://github.com/user-attachments/assets/2d16e1d2-034e-4af2-8477-f1a44eab03dc)


#### Power Report:![5th power](https://github.com/user-attachments/assets/643dc793-9e3d-48f1-a676-4464396c64b2)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
