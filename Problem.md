#the pseudocode for the following three C problems:
Problem 1: Display student information using different data types.
SOLUTION:
#include <stdio.h>

int main() 
{
    // Variable Declarations
    int id = 1234;
    char joey = 'J';     
    float gpa = 3.8;
    int age = 18;

   //student ID
    printf("ID of the student: %d\n", id); 
    printf("Enter new ID: ");
    scanf("%d", &id);                   

  //GPA
    printf("GPA of student: %.1f\n", gpa); 
    printf("Enter new GPA: ");
    scanf("%f", &gpa);                     

  //Age
    printf("Age of student: %d\n", age);  
    printf("Enter new Age: ");
    scanf("%d", &age);                    

    
}


# Problem 2: Read and display a character using getchar() and putchar()
```text
Solution :
START
    
    CREATE character variable user_input
    
   
    PRINT "Enter any single character: "
    
   
    user_input = CALL getchar()
    
   
 PRINT "You entered: "
    CALL putchar(user_input)
END

# Problem 3: Display a floating-point value using different precision settings
Solution
START
    
    CREATE float variable precise_value = 3.14159265
    PRINT precise_value formatted with 2 decimal places (%.2f)
    PRINT precise_value formatted with 4 decimal places (%.4f)
    PRINT precise_value formatted with default decimal places (%f)
END

