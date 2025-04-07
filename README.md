Zoo Management System
A console-based application that simulates a simple zoo management system with different animal types, developed as part of the ITDEV-185 course.
Features

Add Animals: Add lions, elephants, and monkeys to the zoo
Animal Sounds: Make all animals in the zoo speak
Limited Capacity: Zoo has a maximum capacity of 3 animals
Exception Handling: Custom exceptions for various error scenarios

How It Works
This application demonstrates object-oriented programming concepts through a simple zoo management system:

The program starts with an empty zoo
Users can add different types of animals (lion, elephant, monkey)
Users can make all animals in the zoo "speak" with unique sounds
The zoo has a maximum capacity, and exceptions are thrown when trying to exceed it
Custom exceptions handle various error cases (empty zoo, unsupported animal types)

Technical Highlights

Abstract Classes: Uses an abstract Animal class with a pure virtual speak() method
Inheritance: Concrete animal classes (Lion, Elephant, Monkey) inherit from the base class
Polymorphism: Each animal type implements its own version of the speak() method
Smart Pointers: Uses std::unique_ptr for memory management
Exception Handling: Custom ZooException class for specific error scenarios
Modern C++ Features: Demonstrates C++11/14/17 features like smart pointers and std::make_unique

Sample Usage:

Add an animal to the zoo (lion, elephant, monkey), type 'speak' to hear them, or 'exit' to leave: lion
Lion added to the zoo.
Add an animal to the zoo (lion, elephant, monkey), type 'speak' to hear them, or 'exit' to leave: elephant
Elephant added to the zoo.
Add an animal to the zoo (lion, elephant, monkey), type 'speak' to hear them, or 'exit' to leave: speak
Lion says: Roar!
Elephant says: Trumpet!

Project Structure
The project is structured with several classes to demonstrate OOP principles:

Animal.h: Abstract base class defining the interface
Lion.h, Elephant.h, Monkey.h: Concrete animal classes
Zoo.h/Zoo.cpp: Class managing the collection of animals
ZooExceptions.h: Custom exception class
main.cpp: Entry point and user interface

Building the Project
This project can be compiled with any standard C++ compiler that supports C++14 or later. It was developed using Visual Studio 2022.

Author:
Domeneak Addison
