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

![Screenshot 2024-12-02 182728](https://github.com/user-attachments/assets/4fd4cdf6-178d-4ad9-b03b-31a3a37c28ba)


**Timing Diagram**

![Screenshot 2024-12-02 183157](https://github.com/user-attachments/assets/0a9528a3-5947-4006-a731-33cc1d68fb65)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

