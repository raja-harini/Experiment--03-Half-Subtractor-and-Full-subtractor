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



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: HARINI R
RegisterNumber:  23000779
*/

## Output:
![TIMING DIAGRAM HS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/a938e0aa-db48-40b2-9ea3-52fc07e79edf)
![TIMING DIAGRAM FS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/aed4f089-7434-4453-a787-8936709a4bca)

## Truthtable
![CODE HS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/334b7584-4de3-48b1-b601-020bd9d6da10)
![WAVE FORM HS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/55384cb8-79bf-4bac-bd2e-dcb125cfdb54)
![CODE FS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/f63922ca-d8c2-4ff0-a39a-66222f55071b)
![WAVE FORM FS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/c6d73e6a-55a5-491a-a752-2afa4dcac7a7)

##  RTL realization
![LOGIC DIAGRAM HS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/98446bb2-87de-4b4f-957f-a0b84f348922)
![LOGIC DIAGRAM FS](https://github.com/raja-harini/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037372/8830eca2-ccca-46b8-a6cd-ac762270c081)

## Timing diagram 

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
