# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: D.VINITHA NAIDU
RegisterNumber:  212222230175
```
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

module exp2f1(A,B,C,D,f1);
input A,B,C,D;
output f1;
assign f1=(~B&~D)|(A&B&~C)|(~A&B&D);
endmodule

F2=xy’z+x’y’z+w’xy+wx’y+wxy

module exp2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=(~y&z)|(x&y)|(w&y);
endmodule
```
*/
## RTL realization


## Output:
## RTL
### F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![image](https://github.com/VinithaNaidu/Experiment--02-Implementation-of-combinational-logic-/assets/121166004/60e5509d-c11c-4404-9971-42302fe7519e)
### F2=xy’z+x’y’z+w’xy+wx’y+wxy
![image](https://github.com/VinithaNaidu/Experiment--02-Implementation-of-combinational-logic-/assets/121166004/34db7e4b-15f6-497e-aef2-41390261fbdf)

## Timing Diagram
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![image](https://github.com/VinithaNaidu/Experiment--02-Implementation-of-combinational-logic-/assets/121166004/227048aa-3f50-4150-b3fb-44978ba029ba)
F2=xy’z+x’y’z+w’xy+wx’y+wxy
![image](https://github.com/VinithaNaidu/Experiment--02-Implementation-of-combinational-logic-/assets/121166004/5771aa10-e871-452f-a1fc-1e54a79c387e)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
