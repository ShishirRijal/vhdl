# Sequence Detector (1011)
This repository contains VHDL code for a simple sequence detector implemented as an entity and an architecture. The sequence detector monitors a specific sequence of input signals and produces an output signal when the sequence is detected.

## Contents
### sequence:
- Entity: sequence
- Architecture: behavioral
- Description: Implements a sequence detector. The entity has input ports (clk, reset, input) and an output port (output). The sequence detector monitors the input signal and produces an output signal based on a specific sequence.


## How the Sequence Detector Works
- The sequence detector operates in a finite state machine (FSM) fashion, transitioning between different states based on the input signal (input).
- The FSM has four states (s0, s1, s2, s3) representing different stages of the sequence detection process.
- The sequence detector is clocked by the rising edge of the clock signal (clk).
- The reset signal (reset) initializes the FSM to the starting state (s0).


## State Transitions:
- s0:
  - If input is '1', transition to s1.
  - Otherwise, stay in s0.

- s1:
  - If input is '0', transition to s2.
  - Otherwise, stay in s1.

- s2:
  - If input is '1', transition to s3.
  - Otherwise, transition back to s0.

- s3:
  - If input is '1', stay in s3.
  - Otherwise, transition back to s2.


## Output Signal:
The output signal (output) is controlled based on the current state.
If the sequence is detected, the output is set to '1'; otherwise, it is '0'.






## FSM
![IMG_0278](https://github.com/ShishirRijal/vhdl/assets/63596895/e74e5303-f866-469f-8848-d85e45da36a4)



## Output Waveform
<img width="745" alt="Screenshot 2024-02-19 at 1 29 46 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/ab71bc41-535e-4a3e-abbc-e9b1bdffe90d">


