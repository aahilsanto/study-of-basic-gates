Name: A Ahil Santo

Register Number: 24900087

### EXP1: Study of Basic Digital IC’s and Verification of Truth Tables for Different Logic Gates, Realization Using Verilog

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

    
**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming
```
module exp_1(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and g1(y1,a,b);
or g2(y2,a,b);
not g3(y3,a);
nand g4(y4,a,b);
nor g5(y5,a,b);
xor g6(y6,a,b);
xnor g7(y7,a,b);
endmodule 
```
 
**Logic symbol & Truthtable**

**AND gate**

![and](https://github.com/user-attachments/assets/60d1f83b-3f30-4b72-b787-497c863be8b9)


**OR gate**

![or](https://github.com/user-attachments/assets/ab7d5d06-efd5-4ccd-8d83-850eba120731)


**NOT gate**

![not](https://github.com/user-attachments/assets/ccce7026-c7c3-4074-a4c6-6a9af784b1a3)


**NAND gate**

![nand](https://github.com/user-attachments/assets/84abf508-83e1-46a9-952f-6e8d091a5a02)


**NOR gate**

![nor](https://github.com/user-attachments/assets/2e8842ce-f37c-46ba-996d-151d9e0cf2cd)



**Ex-OR gate**

![xor](https://github.com/user-attachments/assets/18f27040-430a-4f3e-b022-cf2449930396)


**Ex-NOR gate**

![xnor](https://github.com/user-attachments/assets/7a1d704f-6846-4104-a128-a91f9bf734fa)


**RTL realization Output:** 

![RTL realization Output](https://github.com/user-attachments/assets/5178594f-5e51-4e93-8c8c-71b05c1c4c46)


**RTL**

![waveform](https://github.com/user-attachments/assets/49a471f4-9460-4cbb-bd95-a0ec55fe9a03)


**Result:**

Thus the Basic digital ICs and the verification of truth tables for different logic gates were studied and successfully realized using Verilog.

