# Holberton School Web React - TypeScript Project

This repository contains TypeScript exercises and tasks covering fundamental TypeScript concepts and features.

## Project Overview

This project is part of the Holberton School Web React curriculum and focuses on TypeScript fundamentals, including interfaces, classes, functions, namespaces, and advanced type features.

## Repository Structure

```
holbertonschool-web_react/
├── TypeScript/
│   ├── README.md              # Detailed project documentation
│   ├── task_0/                # Student interface and DOM manipulation
│   ├── task_1/                # Teacher interface and class implementation
│   ├── task_2/                # Advanced types and unions
│   ├── task_3/                # Ambient namespaces
│   ├── task_4/                # Namespace and declaration merging
│   └── task_5/                # Brand convention and nominal typing
└── README.md                  # This file
```

## Learning Objectives

By completing this project, you will learn:

- Basic types in TypeScript
- Interfaces, Classes, and functions
- How to work with the DOM and TypeScript
- Generic types
- How to use namespaces
- How to merge declarations
- How to use an ambient Namespace to import an external library
- Basic nominal typing with TypeScript

## Requirements

- **Allowed editors**: vi, vim, emacs, Visual Studio Code
- **File standards**: All files must end with a new line
- **Environment**: Code will be transpiled on Ubuntu 18.04
- **Testing**: Scripts will be checked with Jest (version 24.9.*)
- **Documentation**: README.md file is mandatory
- **File extensions**: Use `.ts` extension when possible
- **Compiler**: TypeScript compiler should not show any warnings or errors

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/Haifahasher/holbertonschool-web_react.git
cd holbertonschool-web_react/TypeScript
```

2. Navigate to a specific task directory:
```bash
cd task_X
```

3. Install dependencies:
```bash
npm install
```

4. Build the project:
```bash
npm run build
```

5. Run tests:
```bash
npm test
```

6. Start development server:
```bash
npm run start-dev
```

## Tasks

### Task 0: Creating an interface for a student
- Create a `Student` interface
- Render a table using Vanilla JavaScript

### Task 1: Building a Teacher interface
- Create `Teacher` interface with readonly properties
- Extend with `Directors` interface
- Implement `printTeacher` function
- Create `StudentClass` with interfaces

### Task 2: Advanced types Part 1
- Create `Director` and `Teacher` interfaces
- Implement employee creation functions
- String literal types

### Task 3: Ambient Namespaces
- Create type definitions for external library
- Use triple-slash directives

### Task 4: Namespace & Declaration merging
- Organize code using namespaces
- Demonstrate declaration merging

### Task 5: Brand convention & Nominal typing
- Implement brand properties for type safety
- Create credit sum functions

## Technologies

- **TypeScript**: ^4.9.5
- **Webpack**: ^5.88.2
- **Jest**: ^29.7.0
- **ESLint**: ^9.24.0

## Author

**Haifahasher** - Holberton School Student

## License

This project is part of the Holberton School curriculum.

