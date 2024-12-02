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

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
full adder

![Screenshot 2024-12-02 094120](https://github.com/user-attachments/assets/48eb05d0-ebae-4cd9-ba7b-7710e765baa5)

full sub

![Screenshot 2024-12-02 094130](https://github.com/user-attachments/assets/7611a5bb-f2f9-4a68-82e3-1173ba8a85ac)

**Procedure**

Write the detailed procedure here

**Program:**

![Screenshot 2024-12-02 094108](https://github.com/user-attachments/assets/b81016ee-7d57-4d81-afe6-9419553ad8c8)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

![Screenshot 2024-12-02 094139](https://github.com/user-attachments/assets/722fe25f-0ddc-41b3-b278-f13a50dcb289)

**Output Timing Waveform**

![Screenshot 2024-12-02 094149](https://github.com/user-attachments/assets/c7633cb8-0627-424c-a39f-384a8c7d274e)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



