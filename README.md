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


  FUNCTION 1 K-MAP


![Screenshot 2024-12-09 094037](https://github.com/user-attachments/assets/da998af2-a2dd-4ffa-82b4-913a630c629e)


  FUNCTION 2 K-MAP


![Screenshot 2024-12-09 094052](https://github.com/user-attachments/assets/e7e01572-3655-4ab9-b097-5436277d6475)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
FUNCTION 1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
FUNCTION 2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```


   FUNCTION 1


![Screenshot 2024-12-09 194454](https://github.com/user-attachments/assets/4a237f5e-f34c-461f-b8d4-5efd581c0ed8)


   FUNCTION 2


![Screenshot 2024-12-09 194506](https://github.com/user-attachments/assets/5f43c8a2-2611-4c67-acaa-6458b552b618)



Developed by: VISHAL.V

RegisterNumber:24900179



**RTL realization**

**Output:**

**RTL**



FUNCTION 1


![Screenshot 2024-12-09 194731](https://github.com/user-attachments/assets/de6faaa5-0ed6-46b4-8075-5c566cbd92b2)



FUNCTION 2


![Screenshot 2024-12-09 194738](https://github.com/user-attachments/assets/f2c8ef25-aa45-4d58-ba30-2dc9f5accf1e)


**Timing Diagram**



FUNCTION 1


![Screenshot 2024-12-09 194752](https://github.com/user-attachments/assets/efb0a97c-9f1f-4c8d-b9f5-32796a96e8ef)



FUNCTION 2


![Screenshot 2024-12-09 194800](https://github.com/user-attachments/assets/0da304f1-9d6d-4b3b-b566-aadfd32df825)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

