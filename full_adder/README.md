# FullAdder
This repository consists of VHDL code for FullAdder circuit realized using half adders. 
The circuits include an OR gate, a half adder, and a full adder constructed using two half adders and an OR gate.

## Entities

### Entity: or_gate
- Architecture: behaviour
- Description: Implements a basic OR gate, where the output (z) is the logical OR of input signals (x and y).

### Entity: half_adder
- Architecture: behaviour
- Description: Implements a half adder, where the sum (s) is the XOR of input signals (a and b), and the carry (c) is the AND of the same input signals.

### Entity: full_adder
- Architecture: behaviour
- Components Used: or_gate, half_adder
- Description: Constructs a full adder using two half adders and an OR gate. The sum (S) is the result of the addition, and the carry-out (C) represents the carry to the next bit.

## Circuit Diagram
![full-adder-using-half-adder-1024x322](https://github.com/ShishirRijal/vhdl/assets/63596895/395bf581-56f3-4091-8c16-25feef11b896)

## Output Waveform
<img width="595" alt="Screenshot 2024-02-19 at 12 06 56 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/c2a86116-3a83-4be2-96e8-89b57fd9722e">
