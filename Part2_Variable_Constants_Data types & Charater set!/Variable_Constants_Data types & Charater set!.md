# 13. Charater Set & Keywords in C
## Character set in "C"
**Alphabets :** ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz<br>
**Digits :** 0123456789<br>
**Special symbol :** !#$^&*()_-+=|\?/<>,:;[]{}.`~<br>
## Keywords In "C"
| line_1 | line_2 | line_3 | line_4 |
|----|----|----|----|
|auto|double|int|struct|
|break|else|long|switch|
|cas|enum|register|typedef|
|char|extern|return|union|
|const|float|short|unsigned|
|continue|for|signed|void|
|default|goto|sizeof|volatile|
|do|if|static|while|

# 14. Variables & Constants in C
- A Variable is a data name which is used to store data Value
- There are many types of variables available in C
- Such as Integer,Character,Float etc
## Declaring a Variable
**Syntax:** Data_type Variable_name
**Ex:** int a ; float employee_salary ; char studen_rollno ;
## Rules to Declare a Variable
- It must start with letter or Underscore.
- It should not be a keyword.
- Blank spaces are not allowed within a variable name.
- No Special Symbol is Allowed inside a variable name.
# 15. Data Types in C
## InC There are Three types of Data types
1. Primary Data Type
  i.e.int,char,float etc.
2. Secondary Data Type
  array,function,structure & pointer.
3. user defined data type
## Primry Data Types in C
|Data_Type|Size(in bit)|Range of values|
|-----|-----|-----|
|char|8|-128 to +127|
|int|16|-32768 to +32767|
|float|32|3.4e-38 to +3.4e38|
|double|64|1.7e-308 to +1.7e+308|
|unsigned char|8|0 to 255|
# 16. Format Specifiers in C
|Data Type|Format Specifier|
|------|------|
int|%d
float|%f
char|%c
double|%f
unsigned int|%u
short int|%hi
unsigned short int|%hu
long double|%lf
long int|%ld
unsigned long int|%lu
# 17. Instruction Types in C
## Type Declaration Instruction:
This Instruction is used to Declare the type of variable being used in
the program.Every variable used it the program must be declared before
using it in any statement.

Ex: int a; float b;
## Arithmatic Instruction:
The Arithmatic Instructions are used to perform an Arithmatic operation.
Following is the format to declare the Arithmatic Instructions.

a=b+c;a=b*c;

## Control Instruction:
The control instructions allows us to specify in what order the Instructions
in a program should be executed.
There are Four Types of Control instructions in c.
1. Sequence control Instruction.
2. Decision Control Instruction.
3. Loop Control Instruction.
4. Case Control Instruction.
