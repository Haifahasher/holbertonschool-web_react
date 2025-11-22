# TypeScript Project

This project contains various TypeScript tasks demonstrating key concepts and features.

## Learning Objectives

At the end of this project, you should be able to explain:

- Basic types in TypeScript
- Interfaces, Classes, and functions
- How to work with the DOM and TypeScript
- Generic types
- How to use namespaces
- How to merge declarations
- How to use an ambient Namespace to import an external library
- Basic nominal typing with TypeScript

## Requirements

- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- Files will be transpiled on Ubuntu 18.04
- TS scripts will be checked with jest (version 24.9.*)
- Typescript compiler should not show any warning or error when compiling

## Project Structure

### Task 0: Creating an interface for a student
- Creates a `Student` interface with firstName, lastName, age, and location
- Creates two student objects and renders them in a table using Vanilla JavaScript

### Task 1: Building a Teacher interface
- Creates a `Teacher` interface with readonly properties
- Allows additional attributes to be added dynamically
- Extends Teacher with `Directors` interface
- Implements `printTeacher` function and interface
- Creates `StudentClass` with interfaces for constructor and class

### Task 2: Advanced types Part 1
- Creates `DirectorInterface` and `TeacherInterface`
- Implements `Director` and `Teacher` classes
- Creates `createEmployee` function that returns appropriate instance based on salary
- Implements `isDirector` and `executeWork` functions
- Creates string literal type `Subjects` with `teachClass` function

### Task 3: Ambient Namespaces
- Creates type definitions for `RowID` and `RowElement`
- Creates ambient declarations for external `crud.js` library
- Uses triple slash directives to include dependencies

### Task 4: Namespace & Declaration merging
- Organizes code using namespaces
- Demonstrates declaration merging for Teacher interface
- Creates Subject, Cpp, React, and Java classes within Subjects namespace

### Task 5: Brand convention & Nominal typing
- Creates `MajorCredits` and `MinorCredits` interfaces with brand properties
- Implements `sumMajorCredits` and `sumMinorCredits` functions for nominal typing

## Installation

1. Navigate to the specific task directory:
```bash
cd task_X
```

2. Install dependencies:
```bash
npm install
```

3. Build the project:
```bash
npm run build
```

4. Run development server:
```bash
npm run dev
```

## Author

Holberton School Web React Project

