```
Name : kamsa safi H
Ref no : 23013651
```

# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
   Hardware – PCs, Cyclone II , USB flasher
   Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
module logicgates(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a) ;
xor(y4,a,b);
nand(y5,a,b);
nor(y6,a,b);
xnor(y7,a,b);
endmodule



Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
## RTL realization
![image](https://github.com/safi068/Experiment--02-Implementation-of-combinational-logic-/assets/152167833/6ec1a6a5-576c-4d55-84d5-0d34875ca0e3)

## Output:
## RTL
## Timing Diagram:
![image](https://github.com/safi068/Experiment--02-Implementation-of-combinational-logic-/assets/152167833/b4b59422-5a76-429e-bd15-abe4bf04b97b)
##Truth tabel:
![image](https://github.com/safi068/Experiment--02-Implementation-of-combinational-logic-/assets/152167833/38db416a-3eb8-4135-96d0-778807992ac4)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
