 # EXP 1

## Aim:
_**To print "Hello World", create a calculator program and understand the following concepts:**_
+ **Introduce Basic C++ Syntax:**
 Demonstrate the fundamental structure of a C++ program, including header inclusion, the main() function, and the use of the return statement.
+ **Teach Basic Input/Output:** 
 Show how to use the std::cout stream to print text to the console, introducing standard output handling in C++.
+ **Familiarize with C++ Compilation Process:**
 Guide beginners on how to compile and run a C++ program, providing a practical introduction to using a C++ compiler (e.g., g++).

## **Software:** 
 VSCode


## Theory:
_The "Hello, World!" program is often the first program written by beginners because it introduces key concepts like syntax, functions, input/output, and the compilation process. Understanding this basic program lays a strong foundation for learning more complex C++ programming concepts._

### Structure of a C++ Program is as follows:
+ **Preprocessor Directives:** The line `#include <iostream>` is a preprocessor directive that tells the compiler to include the input-output stream library (iostream) in the program. This library allows us to use std::cout to print text to the console.
+ **The main() Function:** The main() function is the entry point of every C++ program. It’s where the execution begins. The function has a return type of int, indicating that it returns an integer value. In this case, it returns 0 to indicate successful execution.
+ **Standard Output Stream (std::cout):** The std::cout object is part of the C++ standard library and is used to output text to the console. The `<< operator` is used to send data to std::cout. In this program, "Hello, World!" is sent to the console, followed by std::endl, which inserts a newline character.
+ **Return Statement:** The return 0; statement indicates that the program has executed successfully. In C++, returning 0 from the main() function is a convention that signals to the operating system that the program completed without errors.

## Code 1:(Hello World)
```
//KANWALJEET SINGH
//23070123124
//ENTCB2
//EXP 1
#include<iostream>
int main(){
   std::cout<<"HELLO WORLD";
    return 0;
}
```
## Output:
![image](https://github.com/user-attachments/assets/dedc5068-16e6-4deb-a7fa-f21098f34806)

## Code 2:(Caluclator Program)
```
//KANWALJEET SINGH
//23070123124
//ENTC B2
//EXP 1B
#include<iostream>
using namespace std;
int main() {
int n1, n2, sum=0, sub, prod, div;
cout<<"Enter first number."; 
cin>>n1;
cout<<"Enter second number.";
cin>>n2;
sum=n1+n2;
cout<<"Sum of the numbers is: "<<sum<<"\n"; 
sub=n1-n2;
cout<<"Difference of the numbers is: "<<sub<<"\n"; 
prod=n1*n2;
cout<<"Product of the numbers is: "<<prod<<"\n"; 
div=n1/n2;
cout<<"Quotient is: "<<div<<"\n";
return 0;
}
```
## Output:
![image](https://github.com/user-attachments/assets/cd8b65c7-95b4-4b7e-ba61-fcbd11865d19)

## Conclusion:
This simple program demonstrates the basic structure and workflow of a C++ program, including the use of headers, the main function, standard output, and the return statement.





