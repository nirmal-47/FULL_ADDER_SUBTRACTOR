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

<img width="459" height="558" alt="{9C7E5D9C-CDC6-4379-9884-4CBB58AB987F}" src="https://github.com/user-attachments/assets/569bb6b0-df0b-48ef-b92d-d88f23c24ca0" />

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: NIRMAL.M
RegisterNumber: 25014734


**RTL Schematic**

<img width="1068" height="646" alt="{3C23DB79-0FE9-4F70-8A25-9A5E75D4C038}" src="https://github.com/user-attachments/assets/c07d3e1b-a2e5-444d-aabc-cda8ab2be2c6" />
<img width="1076" height="636" alt="{27574026-E919-4639-9E9E-2D8364029849}" src="https://github.com/user-attachments/assets/243e910e-d11b-4344-a83d-448e3d4ff0b5" />

**Output Timing Waveform**

<img width="1056" height="625" alt="{0F82E565-1E8C-4DE8-B7CD-FB1C432ABC7F}" src="https://github.com/user-attachments/assets/334e3f94-7c93-4b62-825c-60fecc443025" />
<img width="1086" height="642" alt="{BC0FC6A2-4311-4CEE-A1FF-13A59290A033}" src="https://github.com/user-attachments/assets/77da276e-e978-46be-9d86-63296aad9397" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



