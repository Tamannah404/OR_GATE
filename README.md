# OR Gate using VHDL (Vivado)

##  Project Description

This project implements a basic OR Gate using VHDL in Vivado Design Suite.
The OR gate performs a logical OR operation on two inputs and produces one output.

##  Tools Used

* Vivado Design Suite
* VHDL (Hardware Description Language)

##  Working Principle

The OR gate gives output HIGH (1) if any one of the inputs is HIGH.

### Truth Table:

| A | B | Y |
| - | - | - |
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

##  Code

```vhdl
Y <= A OR B;
```

##  Simulation

The design was simulated using Vivado simulator, and the output waveform matches the expected truth table.

##  Files Included

* OR_GATE.vhd (Design file)
* OR_GATE_tb.vhd (Testbench file)

##  Conclusion

This project demonstrates the basic implementation of digital logic using VHDL and helps in understanding simulation in Vivado.
