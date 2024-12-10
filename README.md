# FULL_ADDER_SUBTRACTOR

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


![Screenshot 2024-12-10 140806](https://github.com/user-attachments/assets/9bb18a90-4adc-44c3-a6e6-bb84744efb03)


**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.


![Screenshot 2024-12-10 140823](https://github.com/user-attachments/assets/e73dea4f-94f4-445d-86c0-d708aa407664)


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**


![Screenshot 2024-12-10 140839](https://github.com/user-attachments/assets/3b639305-bfa9-4374-a567-8d96493ae989)


**Procedure**
Write the detailed procedure here
1 Type the program in Quartus software. 2 Compile
and run the program. 3 Generate the RTL schematic and save the logic diagram. 4
Create nodes for inputs and outputs to generate the timing diagram. 5 For different
input combinations generate the timing diagram.

**Program:**


![Screenshot 2024-12-10 140854](https://github.com/user-attachments/assets/37ad4c24-14e6-460f-953a-1b6aa370fd1e)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:jeyapriya.j  RegisterNumber:24004150
*/



**RTL Schematic**


![Screenshot 2024-12-10 140901](https://github.com/user-attachments/assets/b5eaf150-6954-4b52-8e1a-ee36f5a11b42)


**Output Timing Waveform**


![Screenshot 2024-12-10 140913](https://github.com/user-attachments/assets/761fd117-baef-45b0-911f-09b813d9a5a0)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



