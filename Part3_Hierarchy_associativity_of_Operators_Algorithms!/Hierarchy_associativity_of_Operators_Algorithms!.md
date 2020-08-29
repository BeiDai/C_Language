# 18. Operators in C
## Arithmatic Operators
|Operator|Meaning|
|-----|-----|
|+|Addition or Unary Plus|
|-|Substration or Unary Minus|
|*|Multiplication|
|/|Division|
|%|Modulus|

## Relational Operators
|Operator|Meaning|
|-----|-----|
|==|Is equal to Operator|
|>|Greater than|
|<|Less than|
|!=|Not equal to|
|>=|Greater than or Equal to|
|<=|Less than or Equal to|

## Logical Operators
|Operator|Meaning|
|-----|-----|
|&&|Logical and|
|\|\||Logical|
|!|Logical not|

## Assignment Operators
|Operator|Meaning|
|-----|-----|
|=|Assignment|
|+=|Plus equal to|
|-=|Minus equal to|
|*=|Multiply by equal to|
|/=|Divide by equal to|
|%=|Modulus by equal to|

## Increment & Decrement Operators
|Operator|Meaning|
|-----|-----|
|++|Increament|
|--|Decreament|

## Conditional Operators
|Operator|Meaning|
|-----|-----|
|?:|Conditional Operator|

## Bitwise Operators
|Operator|Meaning|
|-----|-----|
|&|Bitwise AND|
|\||Bitwise OR|
|^|Bitwise Exclusive OR|
|~|One's Complement Operator|
|<<|Left shift operator|
|>>|Right shift operator|

## Special Operators
|Operator|Meaning|
|-----|-----|
|Sizeof()|Sizeof() operator|
|&|Ampersand Operator|
|*|Pointer Operator|

# 19. Hierarchy & Associativity of Operators
While executing an Arithmatic statement,which has two or more operators,then
they are executed in the following order.

|Priority|Operators|Description|
|------|-----|-------|
|Ist|*/%|Multiplication,division,modular dicision|
|IInd|+-|Addition,Substration|
|IIIrd|=|Assignment|

# 20. Exercise
SOLVE THE FOLLOWING PROBLEM WITH THE HELP OF HIERARCHY AND ASSOCIATIVITY OF
OPERATOR.

X = 2*12 + 3/4 - 123 + 1234
# 21. Let's Convert an Algebric expression into C expression
# 22. Exercise
# 23. understanding printf() & scanf()
# 24. Lab code used to demonstrate printf() and scanf()
````c
#include<stdio.h>
#include<conio.h>
void main()
{
  int a,b,c;
  clrscr();
  printf("Enter two value");
  scanf("%d %d",&a,&b);
  c=a+b;
  printf("%d,c");
  getch();
}
````
# 25. Calculate Square
````c
#include<stdio.h>
#include<conio.h>
void main()
{
  int square,value;
  clrscr();
  printf("\n Enter a value !");
  scanf("%d",&value);
  square=value*value;
  printf("\nThe square of %d is %d",value,square);
  getch();
}
````
# 26. Exercise
Wtite a C Program to find cube of a number entered through keyboard?
# 27. Calculate Simple interest
Principal amount * time * rate/100
```c
#include<stdio.h>
#include<conio.h>
void main()
{
  float amount,rate,time,interest;
  clrscr();
  printf("\n Enter the Pricipal amount");
  scanf("%f",&amount);
  printf("\n Enter interest rate ");
  scanf("%f",&time);
  interest=amount*time*rate/100;
  printf("\n Simple interest is %f ",interest);
  getch();
}
```
# 28. Exercise
Write a C Program to calculate area of rectangle ?
# 29. Escape sequence characters in C
|Character|Use|
| --- | --------------------------- |
| \n  | get the cursor to next line |
| \b  | Back slash                  |
| \t  | Tab                         |
| \r  | Carriage return             |
| \a  | Alert                       |
| \'  | To print single quote       |
| \"  | To print double quote       |
| \\  | To print back slash         |

```c
#include<stdio.h>
#include<conio.h>
void main()
{
  clrscr();
  printf("\a \t \t Prashant shinde");
  printf("\a \t \t Profession :-");
  printf(" \"Online Instructor\"");
  getch();
}
```

# 30. Algorithms & Flowcharts in C
- Start/Stop
- Input/Output
- Decision Making
- Process
- Predefined Process
- Looping
- Connector
- Flow Direction
```c
#include<stdio.h>
#include<conio.h>
void main()
{
  int a,b,addition;
  clrscr();
  printf("Input a,b");
  scanf("%d %d",&a,&b);
  addition=a+b;
  printf("addition is %d",addition);
  getch();
}
```
Problem for Addition of two Numbers.
1. Step1: Start
2. Step2: output "Addition of two numbers"
3. Step3: output "Input two value"
4. Step4: output "Input a,b"
5. Step5: output "addition is",addition
6. Step6: Stop

```flow
st=>start: start
e=>end: stop
io1=>inputoutput: Addition of two numbers Input Two values
io2=>inputoutput: Input a,b
op=>operation: addition a+b
io3=>inputoutput: addition is , Addition
st->io1->io2->op->io3->e
```

# 31. Lab code used in Algorithm
# 32. Learn to Hand Run a Program !
