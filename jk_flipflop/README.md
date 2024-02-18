# JK FlipFlop
This repository contains VHDL code for a JK flip-flop implemented as an entity and an architecture. The JK flip-flop has input ports for J (j), K (k), clock (clk), and reset (reset). It produces two output ports (q and qo). The flip-flop behavior is synchronous, responding to the rising edge of the clock.

## Contents
### jk:
- Entity: jk
- Architecture: behaviour
- Description: Implements a JK flip-flop. The entity has input ports (j, k, clk, reset) and output ports (q and qo). The flip-flop changes its state based on the input conditions and responds to the rising edge of the clock.

### How the JK Flip-Flop Works
- The JK flip-flop behavior is defined within a process sensitive to changes in inputs (j, k, clk, reset).
- The internal variable output represents the current state of the flip-flop.
- If the reset signal is asserted ('1'), the flip-flop is reset to the '0' state.
- On the rising edge of the clock (clk), the flip-flop updates its state based on the JK inputs.
  - If j and k are different (j /= k), the output (q) takes the value of j.
  - If both j and k are asserted ('1'), the output toggles (q becomes the complement of its current state).


## Block Diagram And Truth Table
![image](https://github.com/ShishirRijal/vhdl/assets/63596895/3ac7c864-350b-4d24-9f62-c1e969ded4f7)

## Output Waveform
<img width="746" alt="Screenshot 2024-02-19 at 1 11 23 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/f255f88f-aa6d-4c19-ad67-3ee2943dba1e">
<img width="743" alt="Screenshot 2024-02-19 at 1 12 37 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/3554479a-2bbc-4ae2-a885-a35d08a57c0e">
