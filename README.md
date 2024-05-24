# C program to find Minimum of two given integer values(For ex: a=-1000 b=1000) using conditional operator or ternary operator.
## AIM:
To Write a C program to find Minimum of two given integer values(For ex: a=-1000 b=1000) using conditional operator or ternary operator.
## ALGORITM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the two integer values.
4. Prompt the user to enter the first integer value and read the input.
5. Prompt the user to enter the second integer value and read the input.
6. Use the ternary operator to compare the two values:
   a. If the first value is less than the second value, assign the first value to a variable 
     named min.
   b. Otherwise, assign the second value to the min variable.
7. Print the minimum value using printf.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    (a<b)?
    printf("Minimum between %d and %d is %d",a,b,a):
    printf("Minimum between %d and %d is %d",a,b,b);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-12/assets/136251012/8bc817ee-6d12-49c1-8601-4a7b75e8ddd0)

## RESULT:
Thus, C program to find Minimum of two given integer values(For ex: a=-1000 b=1000) using conditional operator or ternary operator was executed successfully.
