# Simple Calculator

A basic calculator program written in C++ that supports arithmetic operations such as addition, subtraction, multiplication, division, and exponentiation.

## Features

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Exponentiation (`^`)

## How to Use

1. **Clone the Repository**: Clone the repository to your local machine using the following command:
   `git clone https://github.com/Ayon-SSP/Calcky`
2. **Compile the Program**: Navigate to the directory containing the program and compile it using a C++ compiler.
    `g++ -o calculator calculator.cpp`
3. **Run the Program**: Execute the compiled program.
    `./calculator`
4. **Input Operations**:
    -When prompted, input the first number, the operator, and the second number.
    -The program will output the result of the operation.
5. ## Example Uasge
    ``` css
    5 * 3
    ```
**Output**: 15

#  Code Explanation

## variable declarations
- n1, n2: Operands for the calculations.
- div: Stores the result of the division operation.
- pro: Stores the result of the exponentiation operation.
- signe: Stores the operator input by the user.

## Functionality

**1.User Input**: The user is prompted to input two numbers and an operator.
**2.Operation Handling**:
- The program uses a switch statement to determine the operation to perform based on the operator (signe).
- It handles the following operations:
    - Addition: n1 + n2
    - Subtraction: n1 - n2
    - Multiplication: n1 * n2
    - Division: n1 / n2
    - Exponentiation: n1 raised to the power of n2
**3.Output**: The result of the operation is displayed.

## Limitations

- Division by Zero: The program does not handle division by zero.
- Exponentiation: The program currently handles only positive integer exponents.

## Future Improvements
- Add input validation to handle invalid inputs and provide user-friendly error messages.
- Implement division by zero handling to prevent runtime errors.
- Extend the exponentiation feature to support negative and non-integer exponents.

## License
This project is licensed under the MIT License - see the  [MIT License](https://github.com/Ayon-SSP/Calcky/tree/main) file for details.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to suggest improvements or report bugs.