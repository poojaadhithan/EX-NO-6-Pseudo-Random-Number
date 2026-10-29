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
    int i, n = 5;

    srand(time(0));

    printf("Random numbers are:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```

# OUTPUT:
<img width="1600" height="874" alt="crypto_EXP6_output png" src="https://github.com/user-attachments/assets/45a8f9a7-d833-41c6-9bab-a40f8cfc4772" />



# RESULT:
