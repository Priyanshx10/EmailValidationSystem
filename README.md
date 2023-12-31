# EmailValidationSystem

 # Email Validation in Python

This Python script validates an email address based on a set of criteria. It checks for the following conditions:

1. **Minimum length of 6 characters**: The email address must have at least 6 characters.
2. **Starting with a letter**: The first character of the email address must be a letter.
3. **Exactly one "@" symbol**: The email address must contain exactly one "@" symbol.
4. **No spaces**: The email address must not contain any spaces.
5. **No uppercase letters**: The email address must not contain any uppercase letters.
6. **No special symbols other than "_", ".", and "@"**: The email address must not contain any special symbols other than "_", ".", and "@".
7. **Ending with ".com" or ".net"**: The email address must end with ".com" or ".net".

If any of these conditions are not met, the script will print an error message indicating the reason for the failure.

## Step-by-Step Explanation of the Code

The code starts by prompting the user to enter their email address. It then stores the entered email address in the variable `email`.

Next, the code checks if the length of the email address is greater than or equal to 6. If it is not, the script prints an error message and terminates.

If the length of the email address is valid, the code checks if the first character of the email address is a letter. If it is not, the script prints an error message and terminates.

If the first character of the email address is valid, the code checks if the email address contains exactly one "@" symbol. If it does not, the script prints an error message and terminates.

If the email address contains exactly one "@" symbol, the code checks if it contains any spaces. If it does, the script prints an error message and terminates.

If the email address does not contain any spaces, the code checks if it contains any uppercase letters. If it does, the script prints an error message and terminates.

If the email address does not contain any uppercase letters, the code checks if it contains any special symbols other than "_", ".", and "@". If it does, the script prints an error message and terminates.

If the email address does not contain any special symbols other than "_", ".", and "@", the code checks if it ends with ".com" or ".net". If it does not, the

