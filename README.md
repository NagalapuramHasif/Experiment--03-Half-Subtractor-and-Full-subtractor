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

![Screenshot 2023-11-26 143908](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/8353da47-16e7-468b-bab0-e8a91c8ab4ff)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![Screenshot 2023-11-26 164129](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/e22941e6-eb61-4b2f-8fae-34e79bf76b71)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
![Screenshot 2023-11-26 144204](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/cb33dc0e-dd7e-4f11-9cd8-b1a42d49fe4f)


![Screenshot 2023-11-26 150019](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/0a908d54-a4c5-4e8e-b49e-8f0e94c161fc)

Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![Uploading WhatsApp Image 2023-11-30 at 22.23.30_1455e81e.jpg…]()

![WhatsApp Image 2023-11-30 at 22 23 30_b6d1ef8f](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/b59f7854-2f05-4c4c-8476-4c5ed985b875)


##  RTL realization


## Timing diagram 
![Screenshot 2023-11-26 164108](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/2e7549c5-b827-40d8-b07d-23e48a3755bd)

![Screenshot 2023-11-26 143851](https://github.com/NagalapuramHasif/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365567/231f83ff-df05-4f43-ab46-d9a4d505ee4f)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
