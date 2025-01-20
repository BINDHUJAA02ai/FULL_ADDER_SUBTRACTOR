Name:Bindhujaa.S

Register No: 249011119


**Experiment4:IMPLEMENTATION OF  FULL_ADDER_SUBTRACTOR**

Implementation of Full Adder and Full subtractor circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![2](https://github.com/user-attachments/assets/8b4df042-7374-4cb1-9cea-e61d7512fdf9)

![3](https://github.com/user-attachments/assets/ead961b8-a35b-474f-9698-f00edb6c203e)



**Procedure**

FULL ADDER:
1. Open Quartus II and create a new project.
2. Use schematic design entry to draw the full adder circuit.
3. The circuit consists of XOR, AND, and OR gates.
4. Compile the design, and verify its functionality through simulation.
5. Implement the design on the target device and program it.

FULL SUBTRACTOR:
1. Follow the same steps as for the full adder.
2. Draw the full subtractor circuit using schematic design.
3. The circuit includes XOR, AND, OR gates to perform subtraction.
4. Compile, simulate, implement, and program the design similarly to the full adder.



**Program:**

![4](https://github.com/user-attachments/assets/698b2a69-7866-4c01-8859-29f1287e22c6)

![5](https://github.com/user-attachments/assets/a56449a0-373d-42cd-8ba8-7ba93334d2a4)




**RTL Schematic**

![6](https://github.com/user-attachments/assets/1aea4f65-9b54-4bf3-99d9-440869770156)

![7](https://github.com/user-attachments/assets/fb63e995-6c14-4869-bdd4-cd8e0fea7754)






**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/d194e35a-2f04-4c72-97f0-fd07fb81ffd9)

![1000062789](https://github.com/user-attachments/assets/23e490f6-323a-4f4a-8c1e-3bff0b0aae05)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



