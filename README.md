### NAME:YESWANTH PEDDEPI
### REG NO:24010970
### EXP NO 3: IMPLEMENTATION OF HALF ADDER AND HALF SUBTRACTOR CIRCUIT

### AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### HALF ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### HALF SUBSTRACTOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


### PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM:
![Program exp 3](https://github.com/user-attachments/assets/c20a1151-65ce-449f-baa3-dfb684d13d1c)

### TRUTHTABLE:
### HALF ADDER:
![HAlf adder truth table exp 3](https://github.com/user-attachments/assets/83220dc6-d56f-495a-bccb-de433ee6711b)

### HALF SUBSTRACTOR:
![Half substractor truth table exp 3](https://github.com/user-attachments/assets/ed9ddb8f-3dca-4e1b-81f2-0473b4e09db7)
### RTL REALIZATION OUTPUT:
![Logic diagram exp 3](https://github.com/user-attachments/assets/ed497654-560b-45da-87c8-d2f4cf172779)

### TIMING DIAGRAM:
### HALF ADDER:
![Screenshot_20250106-135028 Chrome](https://github.com/user-attachments/assets/a07545d9-d778-4e48-bf12-121b691dd9eb)
### HALF SUBSTRACTOR:
![Screenshot_20250106-135116 Chrome](https://github.com/user-attachments/assets/90a95703-cf9c-4c1c-906a-280b3142eec7)


### RESULT:
Designed and verified the half adder & half substractor circuit and its truth table in Quartus II using verilog programming sucessfully  
  
