### NAME : CHANDRU V
### REG NO : 212224230043
# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB
![image](https://github.com/user-attachments/assets/b7e9fb81-1111-4a97-821f-79a20c057128)



Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B
![image](https://github.com/user-attachments/assets/f815a739-6b05-4dcd-9e89-c238774dddf1)

Figure -02 HALF Subtractor

**Truthtable**

HALF-ADDER :
![IMG-20250415-WA0004 1 (1)(1)](https://github.com/user-attachments/assets/382921fb-a726-45d1-bb9c-eae236702d66)

HALF-SUBRACTOS :
![IMG-20250415-WA0009 1 (1)(1)](https://github.com/user-attachments/assets/c22195c1-b45f-4046-9f19-1d354d73610e)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

HALF-ADDER PROGRAM :

![image](https://github.com/user-attachments/assets/e1b9d18b-6aa0-44bc-a814-dbcc544d9e49)

HALF-SUBRACTOR PROGRAM :

![image](https://github.com/user-attachments/assets/05a77dae-4cf8-41d6-9d7d-1a24e1e4ecd1)


**RTL Schematic**



**Output/TIMING Waveform**

HALF-ADDER :
![image](https://github.com/user-attachments/assets/ed1a258e-613a-4642-b7d2-066bd14ef3ff)

HALF-SUBRACTOR :
![image](https://github.com/user-attachments/assets/8bb40cd9-278c-4649-b561-de8d5ab92dea)


**Result:**
To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming is verified successfully
