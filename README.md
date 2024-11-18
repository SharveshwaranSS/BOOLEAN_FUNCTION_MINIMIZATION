# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![image](https://github.com/user-attachments/assets/bb365ea1-b9c8-4b7a-a753-ba51ea4817eb)



**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or (f_or,a,b);
not (f_not,a);
nor (f_nor,a,b);
nand (f_nand,a,b);
xor (f_xor,a,b);
xnor (f_xnor,a,b);
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900901


**RTL realization**
![image](https://github.com/user-attachments/assets/e34b64f6-1e1b-45f3-8607-e19cf6230284)





**Timing Diagram**
![Screenshot 2024-11-18 180545](https://github.com/user-attachments/assets/7513ccec-1771-4dcc-b69b-eb8a91738cd7)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

