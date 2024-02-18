# Greatest Common Divisor
This repository contains VHDL code for a GCD (Greatest Common Divisor) calculator implemented as an entity and an architecture. The GCD calculation is performed using a Finite State Machine (FSM) design.

## Contents
### fsmgcd:
- Entity: fsmgcd
- Architecture: behavior
- Description: Implements a GCD calculator using a Finite State Machine. The entity has input ports (clk, reset, A, B) and an output port (GCD). The GCD is calculated based on the values of A and B using a state machine.


## Finite State Machine (FSM) Description
The FSM has the following states:

- start: Initializes the FSM.
- input: Accepts input values A and B.
- check: Compares A and B to determine the next state.
- updatex: Updates the value of x (subtracting y from x).
- updatey: Updates the value of y (subtracting x from y).
- output: Outputs the calculated GCD.
- others: Default state, returns to the start state.

## FSM Diagram
![image](https://github.com/ShishirRijal/vhdl/assets/63596895/1abdbf12-378a-4113-85fb-a4ec9238a8a9)


## Output Waveform
<img width="753" alt="Screenshot 2024-02-19 at 12 33 38 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/56e77822-fbcf-4c67-820f-c1f80ebbdde4">
<img width="749" alt="Screenshot 2024-02-19 at 12 34 07 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/3569e893-5f24-439e-afd3-646c724c6df0">
