# Credit Card Number Validation using Luhn Algorithm

This program validates credit card numbers using the Luhn Algorithm. The Luhn Algorithm is a simple checksum formula used to validate a variety of identification numbers, such as credit card numbers.

## Features

- **Input:** Users can input a credit card number to be validated.
- **Validation:** The program checks if the entered credit card number is valid according to the Luhn Algorithm.
- **Exit Option:** Users can exit the program by entering 'exit'.

## Usage

1. **Compilation:** Compile the source code using a C++ compiler. For example:
   ```
   g++ -o cc_validation cc_validation.cpp
   ```

2. **Execution:** Run the compiled executable file. For example:
   ```
   ./cc_validation
   ```

3. **Input:** Enter a credit card number when prompted. You can also enter 'exit' to quit the program.

4. **Output:** The program will display whether the entered credit card number is valid or not according to the Luhn Algorithm.

## Luhn Algorithm

The Luhn Algorithm works as follows:

1. Double every second digit from right to left. If the doubled value is greater than 9, add the digits of the result.
2. Sum all the digits, including both the original digits and the doubled digits.
3. If the total sum is a multiple of 10, then the credit card number is valid.

## File Structure

- **cc_validation.cpp:** Contains the source code for the credit card number validation program.
- **README.md:** This file providing information about the program.

## Notes

- The program checks for valid input before performing the validation.
- Make sure to provide clear instructions for users on how to input credit card numbers and exit the program.
- The Luhn Algorithm is a simple checksum algorithm and does not verify the authenticity of the credit card number.

## Author

[SIVARISHI B]
