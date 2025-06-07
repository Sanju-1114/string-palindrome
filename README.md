# String Palindrome Checker

## Overview

This C++ program checks whether a given string is a palindrome. A palindrome is a string that reads the same forward and backward (e.g., "racecar").

## File

- **string_pallindrome.cpp**: Contains the source code for the palindrome checker.

## Functionality

- The program defines a function `isPalindrome` that takes a string as input.
- It creates a copy of the input string, reverses it, and compares it with the original.
- If the strings match, it outputs "Palindrome"; otherwise, it outputs "Not Palindrome".
- The `main` function tests the `isPalindrome` function with three example strings: "Sanju", "racecar", and "Ac3e3ca".

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Sanju-1114/string-palindrome.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd string-palindrome
   ```

## Usage

1. **Compile the program**:

   ```bash
   g++ string_pallindrome.cpp -o palindrome
   ```

2. **Run the program**:

   ```bash
   ./palindrome
   ```

3. **Expected Output**:

   ```
   Not Palindrome
   Palindrome
   Palindrome
   ```

## Dependencies

- C++ Standard Library ( `<iostream>`, `<cstring>`, `<algorithm>` )

## Notes

- The program is case-sensitive and considers spaces and special characters as part of the string.
- The commented-out `cout` statements in the `isPalindrome` function can be uncommented for debugging to see the original and reversed strings.


   # By Sanju