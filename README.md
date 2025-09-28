# JS-Notes

**Why is let used instead of VAR?
let allows you to declare variables that are limited to the scope of a block statement, or expression on which it is used, 
unlike the var keyword, which declares a variable globally, or locally to an entire function regardless of block scope.
************************************

**Read about Execution Context and Lexical Environmnet.

**There are two kinds of Execution Context in JavaScript:
1.Global Execution Context (GEC)
2.Function Execution Context (FEC)

++ Since every function call gets its own FEC, there can be more than one FEC in the run-time of a script ++ 

**Clouser ???

Encapsulation = “Hide the data inside a capsule and control access to it.”
Abstraction = “Hide the complex implementation and show only the necessary functionality.”
Method overriding: Both Dog and Cat override the speak method from Animal.
Polymorphism: The makeAnimalSpeak function treats Dog and Cat instances as objects of type Animal, demonstrating that the same method speak() behaves differently based on the object.
 polymorphism is advantageous because it enables programmers to create objects with identical functionality, i.e., functions with identical names that operate identically. In some other areas of the OOP framework, you can, however, change some portions of the shared code or even the entire
