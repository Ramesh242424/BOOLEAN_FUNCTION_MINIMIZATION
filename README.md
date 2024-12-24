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
*Program:*
i)
module DE2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module DE2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Ramesh krishnan s
RegisterNumber:24001852
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: ramesh krihsnan s
Register number: 24001852


**RTL realization**
![WhatsApp Image 2024-12-24 at 08 54 56_0fa251fe](https://github.com/user-attachments/assets/2fd919f2-4b00-40a7-a27d-2e8c22dd32d6)

**Output:**
![WhatsApp Image 2024-12-24 at 08 55 07_f3d3e74a](https://github.com/user-attachments/assets/cc9f2e21-8762-4da3-a962-025bf97d14ff)

**RTL**
![WhatsApp Image 2024-12-24 at 08 55 17_2d7b9d0a](https://github.com/user-attachments/assets/ba0e35cf-2c8b-434a-ad55-14b13838dd6b)

**Timing Diagram**
![WhatsApp Image 2024-12-24 at 08 55 29_2b8d55d0](https://github.com/user-attachments/assets/2d31cf5b-88db-4f2a-a034-34c45493c689)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

