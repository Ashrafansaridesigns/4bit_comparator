# 4bit_comparator
Verilog implementation of a 4-bit comparator with combinational logic.
4-Bit Comparator
Description
This repository contains the Verilog implementation of a 4-bit comparator. The design compares two 4-bit binary inputs (A and B) and determines their relationship. It outputs three signals to indicate whether:

A is equal to B (A_eq_B).
A is greater than B (A_gt_B).
A is less than B (A_lt_B).
Features
Fully combinational logic design.
Outputs three status signals:
A_eq_B: High when A == B.
A_gt_B: High when A > B.
A_lt_B: High when A < B.
Modular and reusable Verilog code.
Files in the Repository
4_bit_comparator.v: Verilog module for the 4-bit comparator logic.
tb_4_bit_comparator.v: Testbench to verify the design functionality.
README.md: Documentation for the project.
Inputs and Outputs
Inputs:
A[3:0]: 4-bit binary input.
B[3:0]: 4-bit binary input.
Outputs:
A_eq_B: High when A equals B.
A_gt_B: High when A is greater than B.
A_lt_B: High when A is less than B.
Truth Table
A	B	A_eq_B	A_gt_B	A_lt_B
0000	0000	1	0	0
0110	0010	0	1	0
0101	1000	0	0	1
1111	1111	1	0	0
Simulation
Tools Used:
Simulator: (Specify the simulator, e.g., ModelSim, Vivado, etc.)
Steps to Simulate:
Add the Verilog module (4_bit_comparator.v) and testbench (tb_4_bit_comparator.v) to your simulation environment.
Compile the files.
Run the testbench to observe the results.
Verify the outputs for different combinations of A and B.
How to Use
Clone this repository:
bash
Add the Verilog files to your simulation tool.
Run the testbench file (tb_4_bit_comparator.v) to test the design.
Use the module in your digital designs as needed.
Example Simulation Waveform
You can include a waveform screenshot or describe the expected outputs for different inputs. Example:

A = 4'b0011, B = 4'b0100: A_lt_B = 1
A = 4'b1100, B = 4'b1010: A_gt_B = 1
Future Enhancements
Extend the comparator to N-bit inputs.
Add functionality for signed comparison.
Optimize for FPGA synthesis.
License
This project is open-source under the MIT License. Feel free to use, modify, and distribute it.







