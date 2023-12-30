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


HALF SUBSTRACTOR:



![Exp4 hs code](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/d3f27db4-d8ca-4550-b053-fdc1cd2817a1)






FULL SUBSTRACTOR:





![Exp4 fs code](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/24703ad0-beb0-402d-ab4f-5c39b66ce422)




OUTPUT:

/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: DEVESH.S
RegisterNumber:  23004345
*/



## Truthtable



HALF SUBSTRACTOR:



![Exp4 truthtable hs](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/a754ed5f-4c70-4d37-b1d2-1b5b3db81a2d)





FULL SUBSTRACTOR:




![Exp4 truthtable fs](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/f5b6a9ad-a414-4e5d-8035-905c73326503)


RTL:


HALF SUBSTRACTOR:





![Exp4 hs RTL diagram](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/0f8bf771-c273-4eff-a438-9840a12b3f80)





FULL SUBSTRACTOR:






![Exp4 fs RTL diagram](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/9eef5bf4-a969-4fff-97d9-c672c7994edc)



## Timing diagram 



HALF SUBSTRACTOR:



![hs wave](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/fccc5299-d91b-433d-bd63-fd84fafbefcc)





FULL SUBSTRACTOR:




![fs wave](https://github.com/23004345/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/138849203/28d7404c-5553-48e0-b4fc-ff760675296b)







## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
