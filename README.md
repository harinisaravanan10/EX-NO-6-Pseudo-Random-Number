# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}
```
# OUTPUT:
![Screenshot 2025-04-07 083541](https://github.com/user-attachments/assets/1dbf4e8c-0688-4bbb-9831-f633dc354b76)


# RESULT:
Thus the code is executed successfully.
