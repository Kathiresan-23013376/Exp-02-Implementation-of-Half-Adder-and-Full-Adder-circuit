# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### Program:

###Half adder

![Screenshot 2023-12-14 221103](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/d5b2a3d3-0f1c-4b9f-8ac8-53ba526ad977)

###Full adder

![Screenshot 2023-12-14 221113](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/38269653-253b-4617-917f-8b825bbccf71)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:KATHIRESAN-K 
RegisterNumber:  23013376
*/
Logic symbol & Truthtable
###RTL realization

###Half adder

![Screenshot 2023-12-14 221123](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/782a7613-99ca-4614-b3b2-24e6b1d97d2a)

###Full adder

![Screenshot 2023-12-14 221131](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/ebbd5540-71c8-420e-af7b-b216b16ae35a)


### Output:
### TRUTH TABLE 

###Half adder

![Screenshot 2023-12-14 221141](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/6d104e0a-8ca6-42d4-91f1-4ead34dd3515)


###Full adder

![Screenshot 2023-12-14 221147](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/afe924fc-0992-419b-ae20-81da252640cb)

### TIMING DIAGRAM

###Half adder

![Screenshot 2023-12-14 221211](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/bbab4b3b-37bd-4485-a3b0-05bcfcc94a6a)


###Full adder

![Screenshot 2023-12-14 221219](https://github.com/Kathiresan-23013376/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150008375/74aa63a2-3386-4a7d-9451-9d0415d7b1d6)

### Result:
Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus using
Verilog programming.
