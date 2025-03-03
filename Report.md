﻿#Documentation:
 Password Generator Documentation
Author: Aibek kyzy Asel

1. Project Overview
This project creates a Password Generator that allows users to generate secure, random passwords. The user specifies the password length (6-20 characters) and whether to include numbers, uppercase letters, and special symbols. The program uses SecureRandom for secure randomness.

2. Key Features
User Input: User provides password length and choices for numbers, uppercase letters, and special symbols.
Password Generation: Generates a random password from the selected character sets (lowercase, numbers, uppercase, symbols).
Security: Uses SecureRandom for cryptographically secure random number generation.
Error Handling: Ensures valid input and that at least one character type is selected.
3. Challenges
Character Pool Construction: Dynamically building the character pool based on user preferences.
Cryptographically Secure Randomness: Using SecureRandom to avoid predictable passwords.
4. Websites Used
ChatGPT: Assisted in solving input validation and string handling issues.
GeeksforGeeks: Provided guidance on using SecureRandom for secure randomness.

