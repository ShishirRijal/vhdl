# VHDL
Repository for **VHDL** labs from **Embedded System**. 



## Requirements
1. ghdl
2. gtkwave
3. make

## Installation 
**Note:** This installation procedure works only for linux (ubuntu distribution).
```bash
# Install ghdl and gtkwave
$ sudo apt install ghdl gtkwave
# Install make
$ sudo apt install make
```

## Execution process
- Go to the problem directory whose make file you want to create.
For eg: If you want to create make file for mux
```bash
$ cd mux
```

- Run the Makefile by running make command as
```bash
$ make
```
- This creates result.vcd and 
- You can view content of result.vcd as
```bash
$ cat Makefile
```
- Finally, to observe output in graphical representation, run following command
```bash
$ gtkwave result.vcd
```

This launches the gtkwave and you can now visualize the output waveform by selecting signals. 

## Project Structure

```
VHDL LAB/
|-- Lab1/
|   |-- code.vhdl
|   |-- code_tb.vhdl
|   |-- result.vcd
|   |-- Makefile
|   |-- readme.md
|-- Lab2/
|   |-- ...
|-- Lab3/
|   |-- ...
|-- Lab4/
|   |-- ...
|-- Lab5/
|   |-- ...
|-- Lab6/
|   |-- ...
|-- Lab7/
|   |-- ...
|-- Lab8/
|   |-- ...
|-- readme.md
```


## LAB Directory Detail
### Lab1
- **code.vhdl**: Main VHDL code for Lab1.
- **code_tb.vhdl**: Testbench code for Lab1.
- **result.vcd**: Simulation result file.
- **Makefile**: Automation script for simulation and compilation.
- **README.md**: Lab-specific documentation.
