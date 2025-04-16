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

## Developed by: SHRIRAM VR
## Register number: 212224040314

```
module logic_function(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logic_function(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```



**RTL realization**
![428277522-d813e0f3-5f62-4249-9bdf-fdaa16f94298](https://github.com/user-attachments/assets/e97513d5-d6e3-4f81-a0a3-0b6bb460420b)
![Screenshot 2025-04-16 094507](https://github.com/user-attachments/assets/e454e885-1281-4c01-8f53-e9aab083d99b)


**Output:**
![Screenshot 2025-04-16 093114](https://github.com/user-attachments/assets/a3133189-2bc5-4002-af16-3a6c24f1ee39)
![Screenshot 2025-04-16 094821](https://github.com/user-attachments/assets/df66c4b6-03a3-4a3b-80d0-315a819ac837)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

