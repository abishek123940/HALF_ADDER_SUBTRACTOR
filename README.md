**NAME: ABISHEK S**

**REG NO: 24900833**

**EXP NO 3 : IMPLEMENTATION OF HALF ADDER AND HALF SUBTRACTOR**

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)



**PROCEDURE**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**


![image](https://github.com/user-attachments/assets/86fa317c-d317-4e8a-8b05-5d1db398a450)

**TRUTH TABLE:**

  **HALF ADDER**

  
   ![image](https://github.com/user-attachments/assets/44550a0b-1260-4df2-8f9f-e8f1513b6969)

   
  **HALF SUBTRACTOR**
  
  ![image](https://github.com/user-attachments/assets/f18592db-9e1e-4f90-9701-8ed2d0ebc5f3)

**RTL REALIZATION OUTPUT:**

![image](https://github.com/user-attachments/assets/de7e5514-b487-4c39-bf0c-4fd7778508e4)

![image](https://github.com/user-attachments/assets/dd29871a-2a1a-457a-8066-12ba82d31e7f)


**TIMING DIAGRAM:**

![image](https://github.com/user-attachments/assets/d1b14557-50d9-4d6d-b129-7cfbd253697b)

![image](https://github.com/user-attachments/assets/a8c72561-fd6f-4271-85b0-983517616754)


**RESULT**

Designed and verified the half adder & half subractor circuit and its truth table in quartus Il using Verilog programming successfully.
