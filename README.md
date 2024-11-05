# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 50 40_7a1a2356](https://github.com/user-attachments/assets/fecf8f23-ad81-494b-a01e-91d950d3bd36)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: RegisterNumber:24900901



**RTL realization Output:**
![exp 2 form](https://github.com/user-attachments/assets/5828e1f4-023c-4b82-af8f-fb2c6e863497)




**Timing Diagram**
![wave form exp 2](https://github.com/user-attachments/assets/0a08b99c-98e4-4723-933f-85bf9bc6f41c)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

