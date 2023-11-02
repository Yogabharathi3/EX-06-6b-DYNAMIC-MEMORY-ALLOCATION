# EX-06-6b-DYNAMIC-MEMORY-ALLOCATION
## AIM 
To write a C Program to print 'WELCOME' using malloc() and free(). 
## ALGORITHM 
1. Start the program. 
2. Read a string variable. 
3. Allocate memory using malloc(). 
4. Display the string. 
5. Remove the allocated memory using free(). 
6. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
#include<stdlib.h> 
#include<string.h> 
int main() 
{ 
 char *s; 
 s=(char *)malloc(1*sizeof(char)); 
 scanf("%[^\n]",s); 
 printf("WELCOME"); 
 free(s); 
}
``` 
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-06-6b-DYNAMIC-MEMORY-ALLOCATION/assets/118899387/f9561d4f-6926-42e2-ac28-15ea85c9d021)
## RESULT 
Thus the program to print 'WELCOME' using malloc() and free() has been executed successfully
