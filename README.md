## EXPREIMENT-1-Simple Addition Program


## Aim: 
The aim of this program is to take two integer inputs from the user, calculate their sum, and then display the result.

## Algorithm:
1. Start
2. Declare integer variables `a`, `b`, and `c`.
3. Prompt the user to enter two integers.
4. Read the two integers entered by the user and store them in variables `a` and `b`.
5. Calculate the sum of `a` and `b` and store the result in variable `c`.
6. Display the message "Sum of [a] and [b] = [c]" where `[a]`, `[b]`, and `[c]` are replaced with the values of variables `a`, `b`, and `c` respectively.
7. End.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    int c;
    c=a+b;
    printf("Sum of %d and %d=%d",a,b,c);
    
}
```
## SAMPLE OUTPUT:
![Screenshot 2024-05-06 141208](https://github.com/DurgaV240106/c-program-/assets/144870878/815cb94d-e43d-40ab-a397-2fe6aa099a87)

## OUTPUT:
![Screenshot 2024-05-06 141310](https://github.com/DurgaV240106/c-program-/assets/144870878/fd9554ab-2ce6-4a56-8b4d-dce7331e7c0d)

## RESULT:
Thus, the required program is written and executed successfully.


## EXPREIMENT-1-ASCII Value Printer

## Aim: 
The aim of this program is to take a character input from the user, determine its ASCII value, and then display the character along with its ASCII value.

## Algorithm:
1. Start
2. Declare a character variable `a`.
3. Prompt the user to enter a character.
4. Read the character entered by the user and store it in variable `a`.
5. Determine the ASCII value of the character stored in `a`.
6. Display the message "ASCII value of [character] is [ASCII_value]" where `[character]` is replaced with the character entered by the user and `[ASCII_value]` is replaced with its ASCII value.
7. End.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    char a;
    scanf("%c",&a);
    printf("ASCII value of %c is %d",a,a);
    return 0;
}
```
## SAMPLE OUTPUT:

![Screenshot 2024-05-06 142522](https://github.com/DurgaV240106/c-program-/assets/144870878/bf573ce3-7dd2-4296-a371-c0e69c6f99fb)

## OUTPUT:
![Screenshot 2024-05-06 142602](https://github.com/DurgaV240106/c-program-/assets/144870878/2b6be6da-efde-4e11-abb5-81d45b769bd6)

## RESULT:
Thus, the required program is written and executed successfully.
