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
