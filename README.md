# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**
![Screenshot 2024-12-10 140806](https://github.com/user-attachments/assets/b2b6dd94-419c-4910-b743-51b2917cfd52)

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

**Figure -1 FULL ADDER**

**Full Subtractor**
![Screenshot 2024-12-10 140823](https://github.com/user-attachments/assets/a28b82e2-8373-4969-8436-0f238fdb5ae3)

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2024-12-10 140839](https://github.com/user-attachments/assets/dd1ff52c-7ceb-42a5-aac3-b50e351c890a)

**Procedure**

Write the detailed procedure here

**Program:**
![Screenshot 2024-12-10 140854](https://github.com/user-attachments/assets/15ddb9f5-de74-49fb-928e-d74d30226ac2)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: MAGENDRA SANJAY S
RegisterNumber:24900652
*/

**RTL Schematic**
![Screenshot 2024-12-10 140901](https://github.com/user-attachments/assets/05a7d512-07d7-4b6b-9831-885491fb58a3)

**Output Timing Waveform**
![Screenshot 2024-12-10 140913](https://github.com/user-attachments/assets/030eeccc-8dd3-4304-9d45-d578ad20da14)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



