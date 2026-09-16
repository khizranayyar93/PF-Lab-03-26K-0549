# Lab 03 — C Language Basics Documentation

## 1. Data Types
The table below describes the fundamental data types used in the C programming language:

| Data Type | Description | Size (Typical) |
| :--- | :--- | :--- |
| `int` | Stores whole numbers (integers) without decimals. | 4 bytes |
| `float` | Stores single-precision fractional numbers (floating-point). | 4 bytes |
| `double` | Stores double-precision fractional numbers with higher accuracy. | 8 bytes |
| `char` | Stores a single character or byte of data. | 1 byte |
| `bool` | Stores a boolean value representing true or false. | 1 byte |
| `void` | Represents the absence of a value or type. | 0 bytes |

---

## 2. Format Specifiers
Format specifiers tell the compiler how to interpret and format data during input and output operations:

| Specifier | Description |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Unsigned octal integer |
| `%x` | Unsigned hexadecimal integer (lowercase letters) |
| `%X` | Unsigned hexadecimal integer (uppercase letters) |
| `%f` | Decimal floating-point number |
| `%e` | Scientific notation (lowercase 'e') |
| `%c` | Single character |
| `%s` | String of characters (text) |
| `%ld` | Long signed decimal integer |

---

## 3. Input/Output Functions
C provides several built-in functions to handle reading inputs and printing outputs:

* **`scanf()`**: A standard input function that reads formatted data from the keyboard based on matching format specifiers. It requires variable addresses using the ampersand (`&`) operator.
* **`printf()`**: A standard output function used to send formatted strings and variable data straight to the console window.
* **`getchar()`**: A specialized input function that reads exactly one single character from the input buffer. It does not require any parameters.
* **`putchar()`**: A specialized output function that takes a single character variable as an argument and prints it out to the screen.
* **`fgets()`**: A safer input function used to read a full line of text or string safely from the console up to a specified maximum length, preventing buffer overflows.
* **`puts()`**: A clean output function that prints an entire string to the screen and automatically appends a newline character (`\n`) at the end.

---

## 4. Escape Sequences
Escape sequences are special characters preceded by a backslash (`\`) used to format console layout text:

* **`\n`** (Newline): Moves the cursor down to the beginning of the next line.
* **`\t`** (Horizontal Tab): Inserts a standard tab space spacing in the text.
* **`\\`** (Backslash): Displays a single backslash character on the screen.
* **`\"`** (Double Quote): Prints a literal double quote inside a printf statement.
* **`\a`** (Alert/Bell): Triggers a system beep sound or visual alert notification.

---

## 5. Precision
In C, floating-point precision can be precisely configured within a format specifier by placing a **dot (`.`)** followed by the **number of desired decimal places** between the percentage sign (`%`) and the `f` or `e` specifier character.

### Code Examples:
* `%.2f` limits the output layout to exactly **2 decimal places** (e.g., `3.14`).
* `%.4f` prints the float value restricted to exactly **4 decimal places** (e.g., `3.1416`).
* If no precision override is provided, the default standard `%f` format automatically prints **6 decimal places**.
