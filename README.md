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

``` module boolean (f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
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
```

Developed by: VISHAL.V
RegisterNumber:24900179



**RTL realization**

**Output:**
![output for ex no  02 (de)](https://github.com/user-attachments/assets/367ecf4c-d7b3-48f2-aab2-52953fdb9ac3).

**RTL**

**Timing Diagram**
![output2 for ex no  02 (de)](https://github.com/user-attachments/assets/d32ba71c-0277-4a8b-ab86-cc5da20fbe4f).

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

