# VHDL 2-to-4 Binary Decoder
This repository contains VHDL code for a 2-to-4 binary decoder implemented as an entity and an architecture. The decoder takes two binary input address lines (a1 and a0) and an enable signal (e). It produces four output signals (q3, q2, q1, q0), which represent the decoded signals based on the input conditions.

## Contents
### decoder:
- Entity: decoder
- Architecture: behaviour
- Description: Implements a 2-to-4 binary decoder. The entity has three input ports (a1, a0, e) and four output ports (q3, q2, q1, q0). The decoder logic is based on the input conditions, and each output is activated accordingly.

## Circuit Diagram
![image](https://github.com/ShishirRijal/vhdl/assets/63596895/98bde096-f1f5-4b7e-9d8c-854651108c2f)
![image](https://github.com/ShishirRijal/vhdl/assets/63596895/7eafad7f-70a6-48d0-8d37-4ed503dcf74e)

## Output Waveform
<img width="608" alt="Screenshot 2024-02-19 at 12 26 11 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/86f54ec9-ebeb-496f-95b0-2822ab51f774">
<img width="601" alt="Screenshot 2024-02-19 at 12 26 22 AM" src="https://github.com/ShishirRijal/vhdl/assets/63596895/3edc1ddd-8f85-4c3b-9e41-1e482d93c782">
