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
module exp2(a,b,c,d,f1, f2,w,x,y,z);

input a,b,c,d,w,x,y,z;

output f1;

output f2;

assign f1 =((~b & ~d)|(~a&b&d)|(a&b&~c));

assign f2 =((~y&z)|(x&y)|(w&y));

endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:S S SHARVESHWARAN RegisterNumber:24900901


**RTL realization**
![Screenshot 2024-12-20 101555](https://github.com/user-attachments/assets/6d3a1ae2-c28c-40a2-bdc0-a7bd0ddcaff9)







**Timing Diagram**
![image](https://github.com/user-attachments/assets/4b4755fd-1d0c-496f-af29-da8bba491c18)




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

