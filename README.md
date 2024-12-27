# Scala: Handling Exceptions in Class Property Setters

This repository demonstrates a common error and its solution in Scala related to enforcing constraints on class properties.  The code showcases a simple `MyClass` with a `value` property that cannot be negative.  The example highlights how to use a setter method to validate inputs and throw an `IllegalArgumentException` if the constraint is violated.  The solution effectively addresses exception handling and provides clearer error messages.

## The Problem:

Using a `private var` with a setter without proper exception handling can lead to unexpected behavior and crashes if invalid values are provided. 

## The Solution:

Implementing a setter method that explicitly checks for invalid inputs and throws an exception provides better control over data integrity and helps in managing unexpected situations gracefully.