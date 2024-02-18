# LCM (Least Common Multiple) Calculator
This repository contains VHDL code for an LCM (Least Common Multiple) calculator implemented as an entity and an architecture. The LCM calculation is performed using a Finite State Machine (FSM) design.

## Contents
### lcm:
- Entity: lcm
- Architecture: behavior
- Description: Implements an LCM calculator using a Finite State Machine. The entity has input ports (RESET, CLK, a, b) and an output port (lcm_result). The LCM is calculated based on the input values a and b using a state machine.


## Finite State Machine (FSM) Description
The FSM has the following states:

- start: Initializes the FSM.
- input: Accepts input values a and b.
- check: Checks the values of a and b to determine the next state.
- check1: Continues to check conditions on a and b.
- updatex: Updates the values of x and y.
- updatey: Updates the values of x and y.
- output: Outputs the calculated LCM.
- others: Default state, returns to the start state.

## Output WaveForm
<img width="735" alt="Screenshot 2024-02-19 at 1 24 08 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/4b0ea7af-ccf7-4dde-8526-be5f43dd8422">
