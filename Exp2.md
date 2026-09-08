EXP NO:2 C PROGRAM FOR PASSING STRUCTURES AS FUNCTION ARGUMENTS AND RETURNING A STRUCTURE FROM A FUNCTION
Aim:
To write a C program for passing structure as function and returning a structure from a function

Algorithm:
1.	Define structure numbers with members a and b.
2.	Declare variable n of type numbers.
3.	Prompt the user to enter values for a and b.
4.	Input values for a and b into n using scanf.
5.	Call the add function with n as an argument.
6.	Print the result returned by the add function.
7.	Return 0
 
Program:

``` #include <stdio.h>
#include <string.h>

struct Person {
    char name[50];
    int age;
};

int main() {
    struct Person p;
    scanf("%d", &p.age);
    scanf("%s", p.name);
    printf("Age:%d\n", p.age);
    printf("Name:%svaccine:%d\n",p.name,p.age);
    
   
    if(p.age>6)
    printf("eligibility:yes");
    else
    printf("eligibility:no");
    return 0;
}
```




Output:
<img width="750" height="441" alt="image" src="https://github.com/user-attachments/assets/85e338b0-f15e-43b2-8e0a-939bd86085c6" />







Result:
Thus, the program is verified successfully
