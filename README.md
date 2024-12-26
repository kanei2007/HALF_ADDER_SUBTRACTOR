### NAME : S KANEIMOZHI
### REGISTER NUMBER : 24005925
### EXPERIMENT 3: IMPLEMENTATION OF HALF ADDER AND SUBTRACTOR

## AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

## EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

## HALF ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

## HALF SUBTRACTOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

## PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM:
![Screenshot 2024-11-14 135839](https://github.com/user-attachments/assets/9294bcd5-6626-4914-b3eb-664c4a034f0b)

## TRUTHTABLE:
![TRUTHTABLE 3](https://github.com/user-attachments/assets/72d7e150-2a6e-4e3e-a90e-ed4b9e5c96ea)

## RTL OUTPUT:
![RTL OUTPUT 2](https://github.com/user-attachments/assets/65735c59-956e-4755-ba25-4417c3e9ab0b)

## WAVEFORM OUTPUT:
![WAVEFORM3](https://github.com/user-attachments/assets/ae80f65a-6ec0-425a-81d9-c49268a8ffcc)

## RESULT:
 Thus the given Half adder and subtractor is studied and verified in Quartus using verilog program.
