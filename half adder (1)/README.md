# Half Adder using Verilog

## Project Overview

This project implements a Half Adder using Verilog HDL. A Half Adder is a combinational logic circuit that adds two single-bit binary numbers and produces two outputs:

- Sum
- Carry

---

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|--------|
|0|0|0|0|
|0|1|1|0|
|1|0|1|0|
|1|1|0|1|

---

## Boolean Equations

Sum = A XOR B

Carry = A AND B

---

## Files

```
src/
    half_adder.v

testbench/
    half_adder_tb.v

simulation/
    waveform.png
    simulation_output.txt
```

---

## Simulation

The testbench verifies all four input combinations.

Expected Output:

```
A B | Sum Carry
----------------
0 0 | 0 0
0 1 | 1 0
1 0 | 1 0
1 1 | 0 1
```

---

## Tools Used

- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

---

## Applications

- Arithmetic Logic Unit (ALU)
- Binary Adders
- Digital Electronics
- Computer Architecture

---

## Author

P. Sai Pallavi
B.Tech (ECE)
