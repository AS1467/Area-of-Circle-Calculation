## README

### Area of Circle Calculation

This project contains a simple C program that calculates the area of a circle based on the radius provided by the user. The program demonstrates the use of functions, input/output operations, and mathematical calculations in C.

### Description

The program prompts the user to enter the radius of a circle, then calculates and prints the area of the circle. The calculation is performed by a function that takes the radius as input and returns the area.


### Compilation and Execution

To compile and run the program, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where the source code file (`circle_area.c`) is located.
3. Compile the program using a C compiler, such as `gcc`:
   ```sh
   gcc -o circle_area circle_area.c
   ```
4. Run the compiled executable:
   ```sh
   ./circle_area
   ```

### Usage

1. When prompted, enter the radius of the circle.
2. The program will output the area of the circle based on the entered radius.

### Example

```sh
Enter the radius of circle: 5
Area of circle: 78.50
```

### Notes

- The program uses a constant value for pi defined as `#define pi 3.1415`. However, the function `areaOfcircle` uses `3.14` for calculation, which can be improved for better accuracy.
- The `conio.h` header is included, but it is not used in this program. You can remove it if not needed.
