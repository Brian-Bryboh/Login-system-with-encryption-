# Login System with Encryption

This is a simple Java console application that implements a basic login system with password encryption.

## Features

- Register users with encrypted passwords
- Login authentication by verifying encrypted passwords
- Uses SHA-256 hashing for password encryption
- Stores users in memory (for simplicity)

## How to Run

1. Compile the program:

javac LoginSystem.java

2. Run the program:

java LoginSystem

3. You will be able to:
- Register a new user (username + password)
- Login using registered credentials

## How It Works

- Passwords are hashed using SHA-256 before being stored.
- During login, the entered password is hashed and compared with the stored hash.
