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
 input a,b,c,d,w,x,y,z;
 output f1,f2; 
 assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;
 assignfmodule bln1 (a,b,c,d,w,x,y,z,f1,f2);
 2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y; 
 endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:kamalesh.E RegisterNumber:25018201


**RTL realization**<img width="762" height="613" alt="image" src="https://github.com/user-attachments/assets/28b1ded1-7733-4bf1-a28d-720a128a55d4" />


**Output:**<img width="571" height="772" alt="image" src="https://github.com/user-attachments/assets/bdb5a4d1-6bc7-4124-852b-e87c95bb29d9" />

**Timing Diagram**<img width="992" height="245" alt="image" src="https://github.com/user-attachments/assets/7958bfc3-f9c9-46b0-a54e-cdaf186620db" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

