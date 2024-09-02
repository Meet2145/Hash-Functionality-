# Hash Function Implementation

## Overview
This project demonstrates a simple implementation of hash functions using Python's built-in hashlib library. Hash functions are essential in ensuring data integrity and secure communication. This script allows you to input a message and generate its hash using common algorithms like MD5, SHA-1, and SHA-256.

## Features
- **Support for Multiple Hash Algorithms**: The script supports MD5, SHA-1, and SHA-256 algorithms.
- **User Input**: The script prompts the user to enter a message and select a hash algorithm.
- **Data Integrity**: Hash values generated by the script can be used to verify the integrity of the input data.

## Prerequisites
- **Python 3.x**: Ensure Python 3 is installed on your system.

## Getting Started

### Installation
No external libraries are required for this project. The hashlib library used in this project is part of Python's standard library.

**Run the Script**:
- Open your terminal or command prompt and navigate to the directory where the script is located.
- Run the script with Python:
      
bash
python3 hash_function.py

**Input and Output**:
- The script will prompt you to enter a message.
- Then, you'll be asked to choose a hash algorithm (md5, sha1, or sha256).
- The script will generate and display the hash value of the message.

### Example

bash
Enter the message to hash: Hello, World!

Choose a hash algorithm (md5, sha1, sha256): sha256

The SHA256 hash of the message is: a591a6d40bf420404a011733cfb7b190d62c65bf0bcda32b
