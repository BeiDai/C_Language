# 33. Decision Making & Branshing
- [x] If statement
- [x] Multiple if statement
- [x] If else statement
- [x] Conditional Operator !
- [x] Switch statement
# 34. IF statement
**Syntax :-**
```c
if(expression)
{
  Block of statement to be executed.
}
```
```flow
st=>start: start
e=>end: stop
cond=>condition: IF
op1=>operation: statement inside if block
op2=>operation: statement outside of if block
st->cond
cond(yes)->op1->e
cond(no)->op2->e
```
|Operator|Meaning|
| ---  | ------------------------ |
| ---- | ------------------------ |
| ==   | Is equal to Operator     |
| >    | Greater than             |
| <    | Less than                |
| !=   | Not equal to             |
| >=   | Greater than or Equal to |
| <=   | Less than ot Equal to    |
| &&   | Logical and              |
| \|\| | Logical or               |
| !    | Logical Not              |
```c
#include<stdio.h>
#include<conio.h>
void main()
{
  int x;
  clrscr();
  gotoxy(10,10);
  printf("\n Enter a value !");
  scanf("%d",&x);
  if(x>10)
  {
    printf("\n x=%d",x);
  }
  getch();
}
```
# 35. IF statement Lab code
# 36. Exercise
Write a C Program to receive the value which is less than 50 with the help of
if statement?
# 37. Multiple if statement
## Write a C Program to find the grade of the student wheen the marks are Entered via Keyboard?
- When the student is having the marks less than 40 than means he is failed.
- When the student is having the marks greater than 40 and less than 50 that means he is eligible for C grade.
- When the student is having the marks greater than 50 and less than 60 that means he is eligible for B grade.
- When the student is having the marks greater than 60 and less than 75 that means he is wligible for A grade.
- When the student is having the marks greater than 75 and less than 100 that means he is eligible for A+ grade.
- When the user inserts the value less than 0 or greater than 100 then the computer should display a message invalid input.
```c
#include<stdio.h>
#include<conio.h>
void main()
{
  float p;
  clrscr();
  gotoxy(10,10);
  printf("\n Enter percentage of student ");
  scanf("%f",&p);
  if(p<40)
  printf("The student is failed");
  if(p>=40&&p<50)
  printf("The student is passed with C grade");
  if(p>=50&&p<60)
  printf("The student is passed with B grade");
  if(p>=60&&p<75)
  printf("The student is passed with A grade");
  if(p>=75&&p<100)
  printf("The student is passed with A+ grade");
  if(p<0||p>100)
  printf("\a \a In Valid input !");
  getch();
}
```
# 38. Multiple if statement Lab code
# 39. Exercise
Write a C Program to find the Class of an Employee when the salary of the employee is entered via keyboard with the help of multiple if statement?
Following are the condition:-
- when the employee is having salary in between $500 to $1000 that means he is eligible for class 3.
- when the employee is having salary in between $1000 to $5000 that means he is eligible for class 2.
- when the employee is having salary in between $5000 to $7000 that means hs is eligible for class 1.
# 40. IF else statement
# 41. IF else statement Lab code
# 42. Exercise
# 43. Else if ladder
# 44. Else if ladder Lab code
# 45. Exercise
# 46. Nested if else
# 47. Nested if else Lab code
# 48. Exercise
# 49. Conditional Operator !
# 50. Conditional Operator Lab code
# 51. Exercise
# 52. Switch statement in C
# 53. Switch statement Lab code
# 54. Exercise
