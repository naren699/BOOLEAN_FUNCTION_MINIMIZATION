# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![Theory](https://github.com/user-attachments/assets/bfa7dc56-7fe2-458b-a5b9-e2d5bb6d0bf2)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:NARENDHIRAN P

RegisterNumber:24003040

module exp2(a,b,c,d,f1,f2,w,x,y,z);

input a,b,c,d,w,x,y,z;

output f1;

output f2;

assign f1 =((~b & ~d)|(~a&b&d)|(a&b&~c));

assign f2 =((~y&z)|(x&y)|(w&y));

endmodule


**RTL realization Output:**

![RTE](https://github.com/user-attachments/assets/c01f6636-19d8-489f-bf14-a0608a71c3a0)


**Timing Diagram**

![Timing exp 2](https://github.com/user-attachments/assets/d914583d-48ca-493f-9cc3-7d1067ef4124)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

