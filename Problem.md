# Lab 03 — Pseudocode Problems

## Problem 1: Display student information using different data types
```text
START
    DECLARE integer variable student_id = 1234
    DECLARE character variable student_char = 'J'
    DECLARE float variable student_gpa = 3.8
    DECLARE integer variable student_age = 18
    
    OUTPUT "ID of the student: ", student_id
    OUTPUT "Character value: ", student_char
    OUTPUT "GPA of student: ", student_gpa
    OUTPUT "Age of student: ", student_age
    
    OUTPUT "Enter new ID: "
    INPUT student_id
    
    OUTPUT "Enter new GPA: "
    INPUT student_gpa
    
    OUTPUT "Enter new Age: "
    INPUT student_age
END
```

## Problem 2: Read and display a character using getchar() and putchar()
```text
START
    DECLARE character variable user_input
    
    OUTPUT "Enter any single character: "
    user_input = CALL FUNCTION getchar()
    
    OUTPUT "You entered: "
    CALL FUNCTION putchar(user_input)
END
```

## Problem 3: Display a floating-point value using different precision settings
```text
START
    DECLARE float variable precise_value = 3.14159265
    
    OUTPUT precise_value with 2 decimal places precision
    OUTPUT precise_value with 4 decimal places precision
    OUTPUT precise_value with default decimal places precision
END
```
