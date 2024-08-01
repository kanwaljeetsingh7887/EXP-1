# EXP 1

### **Aim:** To print "Hello World" and study the following concepts:
+ **Introduce Basic C++ Syntax:**
 Demonstrate the fundamental structure of a C++ program, including header inclusion, the main() function, and the use of the return statement.
+ **Teach Basic Input/Output:** 
 Show how to use the std::cout stream to print text to the console, introducing standard output handling in C++.
+ **Familiarize with C++ Compilation Process:**
 Guide beginners on how to compile and run a C++ program, providing a practical introduction to using a C++ compiler (e.g., g++).

### Theory:
The "Hello, World!" program is often the first program written by beginners because it introduces key concepts like syntax, functions, input/output, and the compilation process. Understanding this basic program lays a strong foundation for learning more complex C++ programming concepts.

#### Structure of a C++ Program is as follows:
+ **Preprocessor Directives:** The line `#include <iostream>` is a preprocessor directive that tells the compiler to include the input-output stream library (iostream) in the program. This library allows us to use std::cout to print text to the console.
+ **The main() Function:** The main() function is the entry point of every C++ program. It’s where the execution begins. The function has a return type of int, indicating that it returns an integer value. In this case, it returns 0 to indicate successful execution.
+ **Standard Output Stream (std::cout):** The std::cout object is part of the C++ standard library and is used to output text to the console. The `<< operator` is used to send data to std::cout. In this program, "Hello, World!" is sent to the console, followed by std::endl, which inserts a newline character.
+ **Return Statement:** The return 0; statement indicates that the program has executed successfully. In C++, returning 0 from the main() function is a convention that signals to the operating system that the program completed without errors.

### Code:

1. **Clone the Repository**

   Clone the repository to your local machine using:

   ```sh
   git clone https://github.com/yourusername/hello-world-cpp.git
