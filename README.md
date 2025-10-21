# EX-05 Program to Check Whether the Character 'Y' is a Vowel or Consonant Using Pointer

## AIM:
To write a C program that determines whether the character 'Y' is a vowel or consonant using a pointer variable.

## ALGORITHM:

1. Start
2. Declare a character variable ch and a pointer ptr.
3. Assign the address of ch to the pointer:
    * ptr = &ch;
4. Read a character from the user using:
    * scanf("%c", ptr);
5. Check the value pointed by the pointer *ptr:
    * If it is 'A', 'E', 'I', 'O', or 'U', print “vowel.”
    * Else, print “consonant.”
6. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    char ch;
    char *ptr;
    ptr = &ch;
    printf("Enter an alphabet: ");
    scanf("%c",ptr);
    if(*ptr == 'A'||*ptr == 'E'||*ptr == 'I'||*ptr == 'O'||*ptr == 'U')
    {
        printf("%c is vowel.",*ptr);
    }
    else
    {
        printf("%c is consonant.",*ptr);
    }
}
```

## OUTPUT:
<img width="662" height="126" alt="image" src="https://github.com/user-attachments/assets/d453e74e-3f90-4d26-bc64-d6f78896d248" />

## RESULT:
The program successfully checks and prints whether the character 'Y' is a vowel or consonant using a pointer.
