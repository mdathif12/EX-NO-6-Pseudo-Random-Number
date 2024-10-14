# EX-NO-6-Pseudo-Random-Number

# AIM

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```




# OUTPUT
![Screenshot 2024-10-14 152738](https://github.com/user-attachments/assets/37eca304-e8a1-4fb9-bff1-04212b2a0773)

# RESULT
Thus Pseudorandom Number Generation Using Standard library has been executed successfully

