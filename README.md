## 2to1_mux
Verilog implementation and functional verification of 2to1 Multiplexer using a testbench and simulation waveform.
## Design Description
A 2:1 Multiplexer is a combinational circuit that selects one of two inputs (`a` or `b`) depending on the value of the select signal (`sel`).

- If sel = 0, Output y = a
- If sel = 1, Output y = b

## Boolean Expression

y = (~sel & a) | (sel & b)

## Inputs

| Signal | Direction | Description |
|---------|-----------|-------------|
| a | Input | Data Input A |
| b | Input | Data Input B |
| sel | Input | Select Signal |

## Output
| Signal | Direction | Description |
|---------|-----------|-------------|
| y | Output | Multiplexer Output |

## Truth Table

| sel | a | b | y |
|-----|---|---|---|
| 0 | 0 | X | 0 |
| 0 | 1 | X | 1 |
| 1 | X | 0 | 0 |
| 1 | X | 1 | 1 |

X represents the don't care terms

##Author 
-Apoorva B A
- ECE Student
