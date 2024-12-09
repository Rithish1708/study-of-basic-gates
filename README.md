# NAME:Rithish.R
# REG NO:24900403
# EXPERIMENT 1:study of logic gates

# AIM 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

# EQUIPMENTS REQUIRED

Software – Quartus prime 

# THEORY

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM

Program for logic gates and verify its truth table in quartus using Verilog programming
module Logicgate(a,b,notgate, andgate, orgate, nandgate,norgate, xorgate, xnorgate);
input a,b;
output notgate, andgate, orgate, nandgate, norgate, xorgate, xnorgate;
not(notgate,a);
and(andgate,a,b);
or(orgate,a,b);
nand(nandgate,a,b);
nor(norgate,a,b);
xor(xorgate,a,b);
xnor(xnorgate,a,b);
endmodule


 Developed by: RegisterNumber: 
 
# LOGIC SYMBOL & TRUTH TABLE
![WhatsApp Image 2024-10-28 at 11 42 52_23d93d5e](https://github.com/user-attachments/assets/c92cf0c4-9dc0-439e-b99d-d659da73e458)


# RTL OUTPUT

![Screenshot 2024-10-28 111539](https://github.com/user-attachments/assets/f6443f51-8354-4fb4-928f-d8ba3cb105b2)


# OUTPUT WAVEFORM


![Screenshot 2024-10-28 112418](https://github.com/user-attachments/assets/266b5098-f12e-4446-9f64-87abe06a1e9a)

# RESULT
studied and verified the truth table of logic gates in Quartus II using Verilog programming,verified successfully.

