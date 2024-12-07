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
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: KUSHMA.S RegisterNumber: 24013666


**RTL realization**


**Output:**


**RTL**

![exp2 diagram](https://github.com/user-attachments/assets/98fcb30c-d52c-4198-a5e5-b7b4150e3503)

**Timing Diagram**

![exp2 timing diagram](https://github.com/user-attachments/assets/8a190537-bb9e-4365-b0c6-ed0e945335c4)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

