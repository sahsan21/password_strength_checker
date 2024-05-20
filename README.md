# Password Strength Checker

This is a simple Password Strength Checker written in Python. It evaluates the strength of a password based on length, the use of uppercase and lowercase letters, digits, and special characters. The tool provides a strength score and suggests improvements for weak passwords.

## Features

- Checks if the password is at least 8 characters long.
- Checks for the presence of uppercase letters.
- Checks for the presence of lowercase letters.
- Checks for the presence of digits.
- Checks for the presence of special characters.
- Provides feedback and suggestions to improve password strength.

## Requirements

- Python 3.x

## Installation

1. **Clone the repository:**

   git clone https://github.com/sahsan21/password_strength_checker.git

   cd password_strength_checker
  

3. **Install required libraries (if any):**

    For this project, we use the `re` library, which is included in the standard Python library, so no additional libraries are needed.

## Usage

1. **Run the script:**

    python3 password_strength_checker.py
   

2. **Follow the prompts:**

    Enter a password when prompted to check its strength. The script will evaluate the password and provide feedback.


## Example

$ python3 password_strength_checker.py
Enter a password to check its strength: P@ssw0rd123
Password Strength: Very Strong

$ python3 password_strength_checker.py
Enter a password to check its strength: pass
Password Strength: Very Weak
Suggestions to improve your password:
- Password should be at least 8 characters long.
- Password should contain at least one uppercase letter.
- Password should contain at least one digit.
- Password should contain at least one special character.
