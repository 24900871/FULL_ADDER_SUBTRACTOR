# EX 4 : IMPLEMENTATION OF FULL ADDER SUBTRACTOR

NAME:JOTHIMANI P

REG NO:24900871


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

FULL ADDER 

![image](https://github.com/user-attachments/assets/d3ad18b5-75dd-41dc-849d-7e8fd8be7d91)


FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/bd47d2e7-a110-4a84-a19c-ebbe09d883d2)



**Procedure**

Full Adder :
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit.
3.The circuit consists of XOR, AND, and OR gates.
4.Compile the design, verify its functionality through simulation.
5.Implement the design on the target device and program it.

Full Subtractor :
1.Follow the same steps as for the full adder.
2.Draw the full subtractor circuit using schematic design.
3.The circuit includes XOR, AND, OR gates to perform subtraction.
4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**


![image](https://github.com/user-attachments/assets/0c215bcb-a933-4142-aeda-829d316dad4c)


**RTL Schematic**


![image](https://github.com/user-attachments/assets/bac5f3d1-6507-4a3a-bc8f-482f6e38be3e)


**Output Timing Waveform**


![image](https://github.com/user-attachments/assets/4f32305c-fb3c-4a5e-a3a5-586802258706)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



