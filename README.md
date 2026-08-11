Full Subtractor using Verilog HDL

Overview

A Full Subtractor is a combinational logic circuit that subtracts two binary bits along with a borrow input and produces a Difference output and a Borrow output.

Objective

To design and simulate a Full Subtractor using Verilog HDL and verify its functionality through a testbench.

Theory

A Full Subtractor performs subtraction between three input bits: Minuend (A), Subtrahend (B), and Borrow-In (Bin).

Inputs

- A : Minuend
- B : Subtrahend
- Bin : Borrow Input

Outputs

- Difference : Result of subtraction
- Bout : Borrow Output

Truth Table

A| B| Bin| Difference| Bout
0| 0| 0| 0| 0
0| 0| 1| 1| 1
0| 1| 0| 1| 1
0| 1| 1| 0| 1
1| 0| 0| 1| 0
1| 0| 1| 0| 0
1| 1| 0| 0| 0
1| 1| 1| 1| 1

Files Included

- "full_subtractor.v" – Full Subtractor design module
- "tb_full_subtractor.v" – Testbench for verification
- "simulation_output.png" – Simulation waveform

Applications

- Arithmetic Logic Units (ALUs)
- Digital Computers
- Binary Arithmetic Operations
- Processor Design

Expected Result

The Full Subtractor correctly generates the Difference and Borrow outputs for all possible combinations of inputs A, B, and Bin.

Conclusion

The Full Subtractor was successfully designed and simulated using Verilog HDL. The simulation results verified the correct operation of the circuit according to the truth table.anthor Sunitha 
