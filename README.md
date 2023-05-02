# Email Validation

This Python code is designed to validate the format of an email address input by the user. It checks various criteria to determine if the email address is valid or not.

## How it works
The code prompts the user to enter an email address using the input() function. It then checks the following criteria in sequence:

1. The length of the email address must be at least 6 characters long.
2. The first character of the email address must be a letter.
3. The email address must contain exactly one "@" symbol.
4. The email address must end with either ".com" or ".edu".

If any of these criteria are not met, the code will print a message indicating which criterion the email failed to meet.

Assuming the email passes these initial tests, the code then checks each character of the email address using a loop. The loop checks if each character is a space, a letter (and if it is uppercase), a digit, or one of the allowed special characters ("_", ".", and "@").

If any character in the email address is a space, an uppercase letter, or a character other than a letter, digit, or allowed special character, the code sets a flag variable to indicate that the email address is invalid.

Finally, the code checks if any of the flags are set, and if so, it prints a message indicating that the email address is invalid. If no flags are set, the code prints a message indicating that the email address is valid.

## How to use
To use this code, run it in a Python interpreter or execute it in a Python IDE. When prompted, enter the email address you want to validate.

If the email address meets the specified criteria, the code will print a message indicating that it is a valid email address. If the email address does not meet the criteria, the code will print a message indicating which criterion the email failed to meet.