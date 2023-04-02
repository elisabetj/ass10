# HBV202GAssignment10
A very simple implementation of a stack for storing integer numbers to be tested using JUnit4.

This project is a Maven project, i.e. it uses the standard Maven project structure that your IDE hopefully understands when you `git clone` it. The provided Maven POM includes the JUnit4 dependency.
### Java Packages:
Both the implementation and the tests are in Java package `is.hi.hbv202g.ass5`, 
but in the usual separate Maven `src` directories:

- `src/main/java`:
  - `IntStack.java`: Implementation of a simple stack.
  - `IntStackMain.java`: A class with a main method demonstrating some sample usage of the stack.

- `src/test/java`:
  - `IntStackTest.java`: A skeleton for a class containing JUnit4 test cases for the `IntStack` class, containing one sample test case.

### Maven:

- `mvn compile` compiles all implementation classes.
- `mvn exec:java` executes the main method of the implementation.
- `mvn test` runs all test cases (i.e. all classes with a name that either starts with `Test` or ends with `Test`, `Tests`, or `TestCase`).

### Main method
The main method can be run in pom.xml

[License file](src/LICENSE)

[UML Class diagram](src/site/markdown/design.md)

