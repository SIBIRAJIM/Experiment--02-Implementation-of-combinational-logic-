# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Procedure

1. Create a New Project:

Open Quartus and create a new project by selecting "File" > "New Project Wizard."
Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
2. Create a New Design File:

Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.
3. Write the Combinational Logic Code:

Open the newly created Verilog or VHDL file and write the code for your combinational logic.
4. Compile the Project:

To compile the project, click on "Processing" > "Start Compilation" in the menu.
Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.
5. Analyze and Fix Errors:

If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
Review and fix any issues in your code if necessary.
View the RTL diagram.
6. Verification:

Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform



## Program:

![Screenshot 2023-12-23 104223](https://github.com/SIBIRAJIM/Experiment--02-Implementation-of-combinational-logic-/assets/154588445/1f58c984-57ae-40b8-8a30-dfba10ee6e72)



/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: SIBIRAJIM
RegisterNumber: 212223050048
*/

## RTL realization

![Screenshot 2023-12-15 144054](https://github.com/SIBIRAJIM/Experiment--02-Implementation-of-combinational-logic-/assets/154588445/33eb3ad9-fde7-4fcb-a681-81b070c22e8f)


## Output:
##Truth Table 

![Screenshot 2023-12-23 103918](https://github.com/SIBIRAJIM/Experiment--02-Implementation-of-combinational-logic-/assets/154588445/b8f0b1d5-1658-4db9-9368-bf768a6c4d04)

## Timing Diagram

![Screenshot 2023-12-15 144235](https://github.com/SIBIRAJIM/Experiment--02-Implementation-of-combinational-logic-/assets/154588445/bd83da56-cb82-45d6-97ad-39a4fc27957f)

 


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
