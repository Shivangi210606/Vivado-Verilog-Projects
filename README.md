# Half Adder using Verilog

## Overview
A Half Adder designed using Verilog HDL and simulated in Xilinx Vivado.

## Inputs
- a
- b

## Outputs
- sum
- carry

## Logic
```verilog
sum = a ^ b;
carry = a & b;
```

## Truth Table
| a | b | sum | carry |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Simulation Waveform
![Waveform](waveform.png)

## Tools Used
- Verilog HDL
- Xilinx Vivado

## Author
Shivangi Panigrahy
