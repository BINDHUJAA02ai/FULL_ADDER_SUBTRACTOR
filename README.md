Name:Bindhujaa.S

Register No: 249011119


**Experiment4:IMPLEMENTATION OF  FULL_ADDER_SUBTRACTOR**

Implementation-of-Full-Adder-and-Full-subtractor-circuit

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

full adder


![Screenshot 2024-12-05 170301](https://github.com/user-attachments/assets/cc8ed30c-eaaa-4cf6-85e8-7f307df09ccf)

full subtractor


![Screenshot 2024-12-05 170315](https://github.com/user-attachments/assets/4f017a46-ee7c-4713-bae1-2f180d90bc04)


**Procedure**


1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram

**Program:**

full adder

![Screenshot 2024-12-19 112133](https://github.com/user-attachments/assets/b935176b-63e0-4d83-bbe5-7f465be50dda)



full subtractor

![Screenshot 2024-12-19 112332](https://github.com/user-attachments/assets/ccb7f2d9-3c08-4640-8f5c-9700422c96a6)



**RTL Schematic**



full adder

![Screenshot 2024-12-05 163832](https://github.com/user-attachments/assets/ac6d9903-4b33-4dfc-9b9e-59f2a4b3f1e4)



full subtractor

![Screenshot 2024-12-05 165149](https://github.com/user-attachments/assets/1b937702-e0e7-4468-a3a1-7e7e74bb0cfd)



**Output Timing Waveform**


full adder

![Screenshot 2024-12-19 203359](https://github.com/user-attachments/assets/1943bf48-585a-4787-b3d9-4ce72d0bae43)




full subtrator

![Screenshot 2024-12-19 203432](https://github.com/user-attachments/assets/fbd33ceb-cb5b-4057-82c9-378d88257ad2)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



