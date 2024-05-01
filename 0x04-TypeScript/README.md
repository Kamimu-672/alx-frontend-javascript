# TypeScript Learning Objectives

This project covers various aspects of TypeScript including basic types, interfaces, classes, functions, working with the DOM, generic types, namespaces, declaration merging, ambient namespaces, nominal typing, and more.

## Task 0: Creating an interface for a student

- Define an interface named `Student` with properties: firstName (string), lastName (string), age (number), and location (string).
- Create two students and add them to an array named `studentsList`.
- Render a table using Vanilla JavaScript with each row containing the first name of the student and their location.

## Task 1: Let's build a Teacher interface

- Create a `Teacher` interface with firstName, lastName, fullTimeEmployee, yearsOfExperience (optional), and location.
- Allow adding any attribute to the object like contract without specifying the name.
- Example usage provided in the task description.

## Task 2: Extending the Teacher class

- Write an interface named `Directors` that extends `Teacher` and requires an attribute named `numberOfReports`.
- Example usage provided in the task description.

## Task 3: Printing teachers

- Write a function `printTeacher` that returns the first letter of the firstName and the full lastName.
- Write an interface `printTeacherFunction` for the function.

## Task 4: Writing a class

- Create a class named `StudentClass` with constructor arguments firstName and lastName.
- Implement methods `workOnHomework` and `displayName`.
- Describe the constructor and the class through an interface.

## Task 5: Advanced types Part 1

- Create `DirectorInterface` and `TeacherInterface` with expected methods.
- Implement `Director` and `Teacher` classes.
- Create a function `createEmployee` that returns either a `Director` or a `Teacher` based on salary.
- Example usage provided in the task description.

## Task 6: Creating functions specific to employees

- Write functions `isDirector` and `executeWork` based on employee type.
- Example usage provided in the task description.

## Task 7: String literal types

- Define a string literal type named `Subjects` with values `Math` and `History`.
- Write a function `teachClass` that returns a specific string based on the subject.

## Task 8: Ambient Namespaces

- Create an interface and a type inside `interface.ts`.
- Import types into an ambient namespace and create type declarations for external library functions.
- Perform CRUD operations using imported types in `main.ts`.

## Task 9: Namespace & Declaration merging

- Define interfaces and classes inside namespaces.
- Using declaration merging, extend interfaces and add new attributes.
- Example usage provided in the task description.

## Task 10: Update task_4/js/main.ts

- Export constants for different subjects and a teacher object.
- Log information related to different subjects using exported constants.

## Task 11: Brand convention & Nominal typing

- Define interfaces with a unique brand property.
- Write functions to sum major and minor credits based on unique interfaces.

## Usage

- Each task directory contains configuration files and a `main.ts` file where you can write your code.
- Run `npm run build` to compile the TypeScript code.
- Ensure there are no TypeScript errors when building the project.

## Contributing

Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss what you would like to change.


