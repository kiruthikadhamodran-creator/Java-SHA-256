Algorithm
Step 1

Read the input string from the user.

Step 2

Create a SHA-256 MessageDigest object.

Step 3

Convert the input string into a byte array.

Step 4

Apply the SHA-256 hashing algorithm to generate the hash bytes.

Step 5

Convert each byte of the hash into a two-digit hexadecimal value.

Step 6

Append all hexadecimal values to form the final hash string.

Step 7

Display the SHA-256 hash value.

Pseudocode
START

Read input string

Create MessageDigest object using SHA-256

Convert string to byte array

Generate hash bytes

Create empty string builder

FOR each byte in hash
    Convert byte to hexadecimal
    Append to string builder
END FOR

Print hexadecimal hash

STOP
Flow of Execution
Input String
      │
      ▼
Convert to Bytes
      │
      ▼
Apply SHA-256 Algorithm
      │
      ▼
Generate Hash Bytes
      │
      ▼
Convert to Hexadecimal
      │
      ▼
Display Hash Value
README
Project Title

SHA-256 Hash Generator using Java

Objective

To generate the SHA-256 cryptographic hash value of a given input string using Java's built-in security library.

Requirements
Java JDK 8 or higher
Any Java IDE (Eclipse, IntelliJ IDEA, VS Code) or Command Prompt
Files
Solution.java
Compilation
javac Solution.java
Execution
java Solution
Sample Input
HelloWorld
Sample Output
872e4e50ce9990d8b041330c47c9ddd11bec6b503ae9386a99da8584e9bb12c4
Features
Uses standard Java Security API.
Generates secure SHA-256 hash values.
Produces a fixed-length 64-character hexadecimal output.
Efficient and easy to implement.
Time Complexity
O(n)

where n is the length of the input string.

Space Complexity
O(n)

for storing the input and generated hash bytes.

Applications
Password hashing
File integrity verification
Digital signatures
Blockchain systems
Secure authentication mechanisms
