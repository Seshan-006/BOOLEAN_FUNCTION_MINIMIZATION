# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:SESHAN J RegisterNumber: 24003142*/
module exp2(a,b,c,d,f1, f2,w,x,y,z);      

input a,b,c,d,w,x,y,z;      

output f1;     

output f2;     

assign f1 =((~b & ~d)|(~a&b&d)|(a&b&~c));     

assign f2 =((~y&z)|(x&y)|(w&y));      

endmodule      

**RTL**
![image](https://github.com/user-attachments/assets/f2fa4245-06d0-45f9-9189-54f46b358379)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/de48964f-5faa-4986-8c21-513bd78d478b)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

