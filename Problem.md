# Lab 03 — Pseudocode Problems

## Problem 1: Display student information using different data types
```text
START
    // Declare and initialize student details with appropriate data types
    CREATE integer variable student_id = 1234
    CREATE character variable student_char = 'J'
    CREATE float variable student_gpa = 3.8
    CREATE integer variable student_age = 18
    
    // Display the stored values
    PRINT "ID of the student: ", student_id
    PRINT "Character value: ", student_char
    PRINT "GPA of student: ", student_gpa
    PRINT "Age of student: ", student_age
    
    // Read new values from the user
    PRINT "Enter new ID: "
    READ student_id
    
    PRINT "Enter new GPA: "
    READ student_gpa
    
    PRINT "Enter new Age: "
    READ student_age
END
```

## Problem 2: Read and display a character using getchar() and putchar()
```text
START
    // Declare a variable to hold a single character
    CREATE character variable user_input
    
    // Prompt the user for input
    PRINT "Enter any single character: "
    
    // Read the character using getchar()
    user_input = CALL getchar()
    
    // Display the message and output the character using putchar()
    PRINT "You entered: "
    CALL putchar(user_input)
END
```

## Problem 3: Display a floating-point value using different precision settings
```text
START
    // Declare and initialize a floating-point number
    CREATE float variable precise_value = 3.14159265
    
    // Display the float value using various precision configurations
    PRINT precise_value formatted with 2 decimal places (%.2f)
    PRINT precise_value formatted with 4 decimal places (%.4f)
    PRINT precise_value formatted with default decimal places (%f)
END
```
