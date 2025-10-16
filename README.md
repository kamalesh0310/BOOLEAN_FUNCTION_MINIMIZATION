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


**Program:**: input a,b,c,d,w,x,y,z; output f1,f2; assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d; assign
 fmodule bln1 (a,b,c,d,w,x,y,z,f1,f2); 2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y; endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:kamalesh.E RegisterNumber:25018201


**RTL realization**<img width="884" height="710" alt="Screenshot 2025-10-16 204821" src="https://github.com/user-attachments/assets/4cc75763-1adb-4178-b7e0-99f1f2cda92f" />


**Output:**

**RTL**<img width="533" height="747" alt="image" src="https://github.com/user-attachments/assets/cc970b4c-f7ac-4785-89cf-f55d088ede4d" />


**Timing Diagram**<img width="892" height="211" alt="image" src="https://github.com/user-attachments/assets/91f5cca2-eb7c-46ed-8973-1fe6a3455934" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

