# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: JAYA ABIRAMI S
RegisterNumber:  23004968

## CODE:
### HALF SUBRACTOR:
![Exp4 hs code](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/4493fcd5-cfa8-49c3-919e-7b25c2ef1f20)

### FULL SUBRACTOR:
![Exp4 fs code](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/8f717479-9fea-4188-8043-061a3c6b9980)


## TRUTHTABLE:

### HALF SUBRACTOR:
![Exp4 truthtable hs](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/0ea8090e-3042-4758-8f2f-8d5064413793)

### FULL SUBRACTOR:
![Exp4 truthtable fs](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/340bbe3a-f738-4e3a-98d1-08027f6ce477)


## RTL:

### HALF SUBRACTOR:
![Exp4 hs RTL diagram](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/0d6d4aa9-ffd4-4125-926b-c91a3cbd176a)

### FULL SUBRACTOR:
![Exp4 fs RTL diagram](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/a4076649-170c-413a-9f05-172463f00dc0)


## TIMING DIAGRAM:

### HALF SUBRACTOR:
![hs wave](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/5e0f1799-2b1c-4ce2-903c-61d8ae6f0871)

### FULL SUBRACTOR:
![fs wave](https://github.com/JayaAbirami/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151487010/20ccfd04-64f5-4dd4-b229-0ffd23defd51)


## RESULT:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified
using quartus software
