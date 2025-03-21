
#### *Concept Overview*  
The *XOR (Exclusive OR)* and *XNOR (Exclusive NOR)* gates are widely used in arithmetic circuits, error detection, and data processing.  

---

## *1️⃣ XOR Gate*  
- *Definition:* The XOR gate outputs 1 only when the inputs are different. If both inputs are the same, the output is 0.  
- *Boolean Expression:*  
  \[
  Y = A \oplus B = (A \cdot \overline{B}) + (\overline{A} \cdot B)
  \]
- *Applications:*  
  - Used in half adders and full adders.  
  - Used in parity generators for error detection.  

### *Truth Table*  

| A | B | Y (A XOR B) |
|---|---|------------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## *2️⃣ XNOR Gate*  
- *Definition:* The XNOR gate is the complement of XOR. It outputs 1 when both inputs are the same and 0 when they are different.  
- *Boolean Expression:*  
  \[
  Y = A \odot B = \overline{A \oplus B} = (A \cdot B) + (\overline{A} \cdot \overline{B})
  \]
- *Applications:*  
  - Used in equality comparison circuits.  
  - Used in error detection and correction mechanisms.  

### *Truth Table*  

| A | B | Y (A XNOR B) |
|---|---|-------------|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |



### *Execution Steps*  
1. Copy the Verilog code into a simulator (ModelSim, Xilinx Vivado, etc.).  
2. Compile and run the testbench.  
3. Verify that the outputs match the truth tables.  

Would you like to proceed with *Day 4: Multiplexers (MUX) - Theory, Design & Implementation* next?
