# Ola-Password-Analyzer
Cybersecurity Project, Password Analyzer

## Password Validator

This repository contains a Python script for validating passwords. The script checks for the following criteria to ensure a password meets basic security requirements:

- Minimum length of 8 characters
- At least one lowercase letter
- At least one uppercase letter
- At least one digit
- At least one special character (`!@#$%&`)

## Script Overview

The main script is `password_validator.py`. It defines a function, `validate_password(password)`, that takes a password string as input and returns a validation message. The possible messages are:

- `"Not Valid Password: Too short"`: If the password is less than 8 characters.
- `"Not Valid Password: No lowercase letter"`: If the password does not contain a lowercase letter.
- `"Not Valid Password: No uppercase letter"`: If the password does not contain an uppercase letter.
- `"Not Valid Password: No number"`: If the password does not contain a digit.
- `"Not Valid Password: No special character"`: If the password does not contain a special character.
- `"Valid Password"`: If the password meets all the criteria.

## Usage

1. Clone the repository:
   ```bash
   git clone
