# Implementation-of-Runtime-Polymorphism-Using-Virtual-Functions-and-Abstract-Classes
C++ program demonstrating polymorphism using abstract classes and virtual functions to calculate the area of different shapes.

## Description
This project demonstrates polymorphism in C++ using an abstract base class and virtual functions. It calculates the area of different shapes such as a circle, rectangle, and triangle using a common `Shape` interface.

## Project Idea
The program defines a base class named `Shape` with a pure virtual function `area()`. Each derived class (`Circle`, `Rectangle`, and `Triangle`) implements its own version of the function. A pointer to the base class is used to call the correct method at runtime.

## Features
- Abstract base class
- Pure virtual function
- Runtime polymorphism
- Area calculation for different shapes
