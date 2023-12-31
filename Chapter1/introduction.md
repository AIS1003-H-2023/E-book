## Introduction

Programming is the process of giving instructions to a computer to perform specific tasks. Think of it as creating a set of step-by-step directions for the computer to follow in order to achieve a desired outcome. These instructions are written using a [programming language](https://en.wikipedia.org/wiki/Programming_language), which is a special kind of language that computers can understand.

Here's a simple breakdown of how programming works:

1. __Writing Code:__ Just like you write sentences to communicate with people, you write code to communicate with computers. Code consists of lines of instructions written in a programming language like C++, Python, Java, or others.
2. __Editing and Debugging:__ Sometimes, you might make mistakes in your instructions. This is similar to typos or errors in regular writing. You need to carefully review your code, find errors (bugs), and fix them.
3. __Executing Code:__ Once your code is error-free, you give it to the computer. The computer reads your instructions line by line and performs the tasks you've specified.
4. __Output:__ Depending on your instructions, the computer might perform calculations, display text, create graphics, or do various other things. This is the result of your programming effort.
5. __Iterations and Loops:__ Just like when you repeat steps to make several sandwiches, you can use loops in programming to repeat certain tasks multiple times.
6. __Conditional Statements:__ If you want the computer to make decisions based on certain conditions (e.g., "If the bread is toasted, then spread peanut butter"), you use conditional statements, similar to making choices in everyday life.
7. __Variables:__ You can also give names to values or data and store them in variables. For instance, you might have a `peanutButter` variable that holds the quantity of peanut butter you want to use.
8. __Functions:__ These are like mini-recipes that you can use over and over again. Instead of writing the same set of instructions multiple times, you can create a function and use it whenever you need.
9. __Debugging:__ Debugging is like troubleshooting. If something goes wrong, you need to identify the issue, fix it, and ensure that your code runs smoothly.
10. __Practice and Learning:__ Learning programming is like learning any other skill. You improve by practicing, experimenting, and learning from your mistakes. As you gain experience, you'll be able to create more complex and powerful programs. It helps to to have a (selfmade) problem to solve.

Remember, programming is a tool that allows you to solve problems, automate tasks, and create amazing things on a computer. It might seem a bit challenging at first, but with practice and persistence, you'll become more comfortable and confident in your programming abilities.

---
### Introduction to Object-Oriented Programming (OOP)

Imagine being able to model real-world objects, their behaviors, and interactions in your programs, making your code more organized, reusable, and easier to manage. OOP is a powerful approach used in programming to create well-structured and efficient software.

#### What is Object-Oriented Programming?

Object-Oriented Programming (OOP) is a programming paradigm that focuses on designing and organizing code around the concept of "objects." An object is a self-contained unit that combines both data (attributes) and the operations (methods or functions) that can be performed on that data. This approach helps to mimic real-world scenarios and relationships within your code.

#### Key Concepts of OOP:

1. __Objects:__ Objects are the building blocks of OOP. They represent entities or things in the real world and encapsulate both data and the actions that can be performed on that data.
2. __Classes:__ A class is like a blueprint for creating objects. It defines the structure and behavior that objects of that class will have.
3. __Attributes (Properties):__ These are the data or characteristics that describe an object. For instance, if you're modeling a "Car" object, attributes might include "color," "make," and "model."
4. __Methods (Functions):__ Methods are the actions or behaviors that objects can perform. For the "Car" object, methods could be "startEngine," "accelerate," and "brake."
5. __Encapsulation:__ Encapsulation refers to the practice of bundling data (attributes) and methods (functions) that operate on that data into a single unit (object). It helps keep related code together and ensures data integrity.
6. __Inheritance:__ Inheritance allows you to create a new class (subclass) based on an existing class (superclass). The subclass inherits attributes and methods from the superclass, enabling code reuse and hierarchy.
7. __Polymorphism:__ Polymorphism allows objects of different classes to be treated as objects of a common superclass. It facilitates code flexibility and reusability through method overriding.

To start with OOP, you'll learn to design classes, create objects, define attributes, implement methods, and understand the relationships between classes. Practice is key, so as you dive into OOP, don't hesitate to create small projects and explore how these concepts work in practice.

Remember, OOP is a foundational concept used in various programming languages like C++, Java, Python, and more. As you become more familiar with its principles, you'll be able to design elegant and efficient solutions to complex problems in your programming journey.

#### Why Learn OOP?

Learning OOP has several benefits:

- __Modularity:__ OOP encourages breaking down complex problems into smaller, manageable units (objects), making code more modular and maintainable.
- __Code Reusability:__ With classes and inheritance, you can reuse existing code, reducing redundancy and development time.
- __Abstraction:__ OOP enables you to abstract complex real-world concepts into simplified, manageable models within your code.
- __Collaboration:__ OOP promotes collaboration among developers by allowing them to work on different parts of a project independently.

#### OOP compared to other paradigmes

|              | OOP                                                                                                                          | Procedural                                                                                            | Functional                                                                                                                    |
|--------------|------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| __Focus__        | OOP focuses on modeling real-world entities as objects, combining data and methods that operate on the data.                 | Procedural programming focuses on procedures or functions that execute a sequence of statements.      | Functional programming focuses on treating computation as the evaluation of mathematical functions and avoiding mutable data. |
| __Key Concepts__ | Classes, objects, inheritance, encapsulation, polymorphism.                                                                  | Functions, sequences, variables.                                                                      | First-class functions, immutability, higher-order functions.                                                                  |
| __Advantages__   | Encourages code reusability, modularity, and easy maintenance. Supports complex systems by representing entities as objects. | Simple and straightforward for smaller tasks. Emphasizes clear step-by-step procedures.               | Emphasizes clear data flows and avoids side effects. Well-suited for tasks involving data transformations.                    |
| __Examples__     | C++, Java, Python.                                                                                                           | C, Pascal.                                                                                            | Haskell, Lisp, Clojure.                                                                                                       |
| __Metaphor__     | Think of objects as self-contained entities with attributes and behaviors, much like objects in the real world.              | Think of programming as a series of well-defined steps or instructions, much like following a recipe. | Think of programming as composing and applying functions to data, like mathematical transformations.                          |

##### Commonalities and Considerations:

All paradigms have their strengths and are suitable for different scenarios.
OOP is useful for modeling real-world systems and creating reusable components.
Procedural programming is suitable for simple tasks and clear, step-by-step procedures.
Functional programming is good for tasks involving data transformations and avoiding side effects.
As you explore programming paradigms, remember that they're not exclusive; you can often use elements from different paradigms to suit the needs of your projects. 
Understanding the strengths and characteristics of each paradigm will help you choose the right approach for your coding challenges.

---
### Introduction to C++

Imagine having the power to create software, games, and applications that can do almost anything you can think of. C++ is a programming language that allows you to turn your ideas into functional and interactive programs.

#### What is C++

C++ is a versatile and widely used programming language known for its combination of power and efficiency. It was developed as an extension of the [C programming language](https://en.wikipedia.org/wiki/C_(programming_language)), adding features that make it easier to organize and manage your code. C++ is used in a wide range of applications, from creating games and mobile apps to building complex software systems and even controlling hardware devices. C++ supports OOP, as well as other programming paradigms, making in a multi-paradigm language. The focus in this course, however, lies with OOP.

C++ is also a statically typed programming language, which means that the data types of variables are determined and checked at compile-time, before the program is executed. Understanding what this means is essential for writing correct and predictable code. In C++, every variable you declare must have a specific data type associated with it. This data type indicates what kind of value the variable can hold. C++ enforces this type-checking at compile-time, which is when your code is transformed into machine-executable instructions.
When you declare a variable in C++, you specify its data type explicitly. For example:

```cpp
int age;      // 'age' is an integer variable
double price; // 'price' is a double (decimal) variable
```

By specifying the data type, you're telling the compiler what kind of value the variable will hold.
Static typing promotes _type safety_. It helps catch errors before your program runs. If you try to use a variable in a way that's inconsistent with its data type, the compiler will generate an error during compilation, preventing you from creating programs that could cause unexpected behavior or crashes. Overall, some of the benefits of Static Typing are:

- __Predictable Behavior:__ Static typing helps you catch type-related errors early, reducing runtime surprises.
- __Performance:__ Statically typed languages can often optimize code better, as the compiler knows the exact data types being used.
- __Code Readability:__ By knowing the data types, other programmers can quickly understand the purpose of variables.

While static typing offers numerous benefits, it can be seen as a bit more rigid compared to dynamically typed languages (e.g., Python) where variables can change types at runtime. However, this rigidity aids in preventing many types of errors.

#### Why learn C++

Learning C++ opens up a world of possibilities. Here are a few reasons why you might want to learn this language:

- __Versatility:__ C++ can be used to develop a wide variety of applications, from simple console programs to complex graphical user interfaces and even real-time simulations.
- __Performance:__ C++ allows you to write code that runs efficiently and quickly. This is especially important for tasks that require high performance, such as games and scientific simulations.
- __Game Development:__ Many popular games and game engines, like Unreal Engine, are built using C++ because of its performance and control over hardware resources.
- __System Programming:__ C++ is used for creating system-level software, drivers, and operating systems.
- __Career Opportunities:__ Knowledge of C++ is a valuable skill in the software development industry, opening doors to various job opportunities.

You might have heard that C++ is a difficult language to learn. This is somewhat true, however, the language has evolved a lot since its inception in 1985. Todays C++ programmers should be using best practices for the language standards C++11 and newer. Also known as _modern C++_. The newer language standards have made the language much easier to use. This course uses C++17.

The gist of _modern C++_ is as follows:

> Modern C++ is characterized by a set of programming practices, language features, and design principles that aim to enhance code clarity, efficiency, and safety. It encourages the use of standardized libraries, smart pointers, lambda expressions, type inference, and other features to write concise, expressive, and maintainable code. The emphasis is on leveraging the C++11 and later standards to achieve a balance between high-level abstractions and low-level control while promoting best practices for memory management and code organization.

#### Key concepts to be explored:

As you embark on your journey with C++, here are some key concepts you'll learn about:

1. __Syntax and Basics:__ You'll learn how to write and structure C++ code, including variables, data types, input/output, and basic operations.
2. __Control Flow:__ Discover how to make decisions using conditional statements (if, else) and how to create loops to repeat tasks.
3. __Functions:__ Explore the concept of functions, which allow you to break your code into reusable blocks and simplify complex tasks.
4. __Classes and Objects:__ Dive into the world of Object-Oriented Programming (OOP). Learn about classes, objects, and how to create your own custom data types.
5. __Memory Management:__ Understand how memory is allocated and managed in C++, as well as concepts like pointers and references.
6. __C++ Standard Library:__ Explore a collection of pre-built classes and functions that provide powerful tools for common programming tasks.

Learning C++ is an exciting adventure that requires practice and patience. Start by writing simple programs and gradually work your way up to more complex projects. Don't be afraid to make mistakes – they're an essential part of the learning process. There are numerous online resources, tutorials, and communities where you can ask questions and seek help. 

- [Stack Overflow](https://stackoverflow.com/) - This is where you often end up searching Google for help. An invaluable resource for any programmer.
- [learncpp.com](https://www.learncpp.com/) - LearnCpp.com is a free website devoted to teaching you how to program in C++.
- [ChatGPT](https://chat.openai.com/) - Used correctly, ChatGPT can be great companion and sparring partner. 

Remember, with determination and practice, you'll be well on your way to mastering C++ and creating your own remarkable software.

Happy coding, and welcome to the world of C++ programming!
