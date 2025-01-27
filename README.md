# Brutus - MD5 Password Cracker

## Description
**Brutus** is a simple password cracking tool written in C that uses the MD5 algorithm to hash and test various password combinations. The program attempts to crack MD5 hashes by generating all possible combinations of characters from a defined alphabet and comparing their MD5 hash to a target hash.

The program works by taking an MD5 hash input from the user, and then attempting to match the hash by generating candidate passwords of a specified length.

## Features
- **MD5 Hash Cracking**: Given an MD5 hash, the tool tries to find the original password that corresponds to it.
- **Password Size**: Allows the user to specify the length of the password to crack.
- **Character Set**: The program uses an alphabet of lowercase letters (`a-z`) to generate possible passwords.
- **Efficient Hashing**: Uses the MD5 hashing function to generate hashes and compare them with the target hash.

## Technologies Used
- **C**: The tool is implemented in C.
- **MD5 Library**: Utilizes an MD5 library for generating and comparing MD5 hashes.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/anthocote19/brutus.git
