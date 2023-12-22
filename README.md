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
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: R.Monish
RegisterNumber:23008248
*/
Logic symbol & Truthtable
RTL realization

half wave code:
![Exp3 ha code](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/53f9ea0a-f286-4531-af55-dbf3384cf8eb)

full wave code:
![Exp3 fa code](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/9fb37525-6453-4382-8847-ca13a9f8d55d)

### Output:
### RTL
half adder:
![Exp3 ha RTL diagram](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/5f1fc687-f39c-43dc-9c7c-ce850588167b)

full adder:
![Exp3 fa RTL diagram](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/a27b0790-2e07-42c9-8d65-99a03a5e1761)

### TIMING DIAGRAM
half wave:
![exp3 ha wave](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/e269623f-aee4-465e-8bc3-deda73663c95)

full wave:
![exp 3 fa wave](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/98d2872e-aad0-45d6-98ff-de639d562b99)



### TRUTH TABLE 
half adder:
![Exp3 truthtable (ha)](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/be1eb224-31f5-47b4-8f62-d7b560ad0d8d)

full adder:
![Exp3 truthtable (fa)](https://github.com/monishr288/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474049/cedc795f-5973-435f-8aba-6cd6b68f37d9)


### Result:Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
