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
```
First program:
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

Second program:
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Sujiith

RegisterNumber: 24012036


**RTL realization**

**Output:**

**RTL**
![rtl01](https://github.com/user-attachments/assets/e8b5f6aa-63ec-442c-9653-7ef0a9c28d3b)

![rtl002](https://github.com/user-attachments/assets/812f5cb3-2377-47d7-8e9a-9a8976ac003d)

**Timing Diagram**
![td01](https://github.com/user-attachments/assets/64ffbb20-23f9-4f88-bf7c-1a559471d5a1)
![td02](https://github.com/user-attachments/assets/763bf9f5-0339-4514-9a8f-4e613530e23d)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

