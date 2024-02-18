# 4-to-1 Multiplexer (MUX4)
This repository contains VHDL code for a 4-to-1 multiplexer (MUX4) implemented as an entity and an architecture. The 4-to-1 multiplexer selects one of four input signals based on the values of select lines (s1 and s0). The selected signal is then directed to the output signal (y).

## Contents
### mux4:
- Entity: mux4
- Architecture: Behavioral
- Description: Implements a 4-to-1 multiplexer. The entity has input ports (a, b, c, d, s1, s0) representing the four data inputs and select lines. It also has an output port (y) for the multiplexer output.


## How the MUX4 Works
- The 4-to-1 multiplexer has four data inputs (a, b, c, d) and two select lines (s1, s0).
- The output signal (y) is determined based on the select lines as follows:
- If s1 and s0 are both '0', the output is the value of input a.
- If s1 is '0' and s0 is '1', the output is the value of input b.
- If s1 is '1' and s0 is '0', the output is the value of input c.
- If s1 and s0 are both '1', the output is the value of input d.



## Block Diagram
![image](https://github.com/ShishirRijal/vhdl/assets/63596895/5b34aff2-727e-47d6-9816-4f01d391a122)

## Output Waveform
<img width="753" alt="Screenshot 2024-02-19 at 1 39 46 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/31f7daef-415b-41d5-be8f-cec73e98e16e">
<img width="743" alt="Screenshot 2024-02-19 at 1 40 12 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/78ee5219-1920-4674-acff-58e655a73da0">
