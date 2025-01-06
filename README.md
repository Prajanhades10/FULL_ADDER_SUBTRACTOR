### NAME : PRAJAN
### REG NO : 24009412
# EXPERIMENT 4:  IMPLEMENTATION OF FULL ADDER SUBTRACTOR


# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# Truthtable

![Screenshot 2024-12-13 034006](https://github.com/user-attachments/assets/e3fc3524-0664-4aaf-afbf-8c2b0120855c)



# Procedure

Implementing BOOLEAN functions in Verilog HDL (Hardware Description Language) involves
translating the simplified Boolean expressions into Verilog code to describe the behavior of digital
circuits. The basic building blocks in Verilog is module. The module represent a combinational
circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate
primitives for basic functions. Use University program VWF to verify the functionality of your Verilog
modules. Create waveform and check outputs against expected results.


# Program:

![Screenshot 2024-12-13 034023](https://github.com/user-attachments/assets/4c6b9db2-2d6a-445c-a0d1-edf19a620515)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

# RTL Schematic

![Screenshot 2024-12-13 034034](https://github.com/user-attachments/assets/17f1c118-d279-48c3-8ee2-915ab3300523)


# Output Timing Waveform

![Screenshot 2024-12-13 034048](https://github.com/user-attachments/assets/bbcb434f-34b8-4106-997e-75c68f55a079)


# Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using
Quartus software.




