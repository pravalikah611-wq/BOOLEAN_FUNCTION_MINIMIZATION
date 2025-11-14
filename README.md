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

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

**RTL realization output:**

<img width="1920" height="1080" alt="Screenshot 2025-11-14 200605" src="https://github.com/user-attachments/assets/207e1912-5d45-4b06-8c8c-73fb2948f346" />

**Timing Diagram**

<img width="1920" height="1080" alt="Screenshot 2025-11-14 200009" src="https://github.com/user-attachments/assets/0346544b-b54f-46ec-a795-39004e607647" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

