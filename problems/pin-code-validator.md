
# ATM PIN Code Validation Kata

Welcome to the ATM PIN Code Validation Kata! In this coding exercise, you'll be working with PIN codes to determine if they are valid or not. Let's dive into it!

## Problem

ATM machines allow PIN codes with exactly 4 digits or exactly 6 digits. Your task is to create a function that checks whether a given PIN string is valid.

## Task

Write a function `validatePin(pin)` that takes a PIN string as input and returns `true` if the PIN is valid (4 or 6 digits) and `false` otherwise.

## Example

```python
validatePin("1234")  // Returns: True
validatePin("12345")  // Returns: False (invalid length)
validatePin("000000")  // Returns: True
validatePin("a234")  // Returns: False (contains non-digit characters)
```

## How to Use

1. Clone this repository to your local machine (Only if you have not cloned it already).
2. Navigate to the `solutions/<your-name>` directory.
3. Create a new file, e.g., `pin-code-validator.js`.
4. Implement your solution in the created file.
5. Test your solution with various PIN strings.
6. Run your script to see if the validation works as expected.

## Testing

You can test your solution by running the script and checking the output for different PIN strings. Feel free to use the provided examples as a starting point.

## Contributing

If you'd like to contribute improvements or alternative solutions, feel free to create a pull request. Your contributions are appreciated!

## Need Help?

If you have any questions or need assistance, don't hesitate to reach out. Remember, practice is key, and every step you take makes you a better coder!

Happy coding! 🚀
