---
layout: post
title: Foundations Overview
description: All of the foundations and the hws
categories: ['DevOps']
permalink: /csa/OverviewFoundations
comments: True
---

# YAYAYAY SO FUN AP CSA Units 1-9 Summary

<details>
<summary><strong>Unit 1: Primitive Types</strong></summary>

- **Basic Data Types**: int, double, boolean, char
- **Variable Declaration**: Example: `int x = 5;`
- **Arithmetic Operators**: +, -, *, /, %, with precedence rules (PEMDAS)
- **Type Casting**: Converting between `int` and `double` (note truncation for double to int)
- **Input Handling**: `Scanner sc = new Scanner(System.in);`
- **Output Handling**: `System.out.println();`

Primitives = monkeys = simple

Basically: primitives are the most basic data types which are stored as their actual values in variables and not just a memory address.
</details>

---

<details>
<summary><strong>Unit 2: Working with Objects</strong></summary>

- **Object Creation**: Objects instantiated with `new`
- **Strings**: Example: `String str = "hello";`
  - **Common Methods**: `length()`, `substring()`, `indexOf()`, `charAt()`
- **Null References**: `null` as a placeholder for uninitialized objects
- **Equality Check**: `==` for references, `.equals()` for content comparison
- **Math Operations**: `Math.pow()`, `Math.sqrt()`, `Math.random()`

Objects are just like instantiations of a class; they create a new "instance" of the class that it's creating/calling to create. This means that methods that are defined within that class are within the variable the object is stored in.
</details>

---

<details>
<summary><strong>Unit 3: Boolean Expressions and If Statements</strong></summary>

- **Boolean Operators**: `&&`, `||`, `!`
- **Comparison Operators**: `<`, `>`, `<=`, `>=`, `==`, `!=`
- **Conditional Statements**:
  - `if`, `else if`, `else`
  - **Nesting**: Embedding conditions within other conditions
- **Logical Expressions**: Combine conditions for complex decision-making

Basically: and -> `&&`, or -> `||`, not -> `!`, and if statements have parentheses and brackets 🤯
</details>

---

<details>
<summary><strong>Unit 4: Loops and Iteration</strong></summary>

- **Types of Loops**:
  - `while(condition) { }`
  - `for(initialization; condition; update) { }`
  - `do { } while(condition);`
- **Break/Continue**: Interrupt or skip loop iterations
- **Nested Loops**: Loops within loops
- **Use Cases**: Array traversal, searching, counting operations

For-each loops are a bit different:
`for (type var : array) {}`
</details>

---

<details>
<summary><strong>Unit 5: Creating Classes</strong></summary>

- **Class Structure**: Fields, methods, constructors
- **Constructor**: Used to initialize an object's state
  - Example: `public ClassName(type parameter) { }`
- **Getters**: Access field values
- **Setters**: Modify field values
- **Static Members**: Shared across all instances of the class
- **Encapsulation**: Protect fields using private access and public methods

Getters and setters are just methods that.... wait for it.... GET AND SET

Constructor: `public`, `private`, `static`, `void` etc.
</details>

---

<details>
<summary><strong>Unit 6: Arrays</strong></summary>

- **Array Declaration**: Example: `type[] arrayName = new type[size];`
- **Accessing Elements**: `array[index]`
- **Traversing Arrays**: Use loops to iterate through elements
- **Common Operations**: Finding max, min, sum, and average
- **Bounds Checking**: Prevent `ArrayIndexOutOfBoundsException`

Arrays: Don't ask for more than you have, else you get an `ArrayIndexOutOfBoundsException`. Unlike Collegeboard, Java is sane and starts indexing at 0.
</details>

---

<details>
<summary><strong>Unit 7: ArrayList</strong></summary>

- **Declaration**: `ArrayList<Type> list = new ArrayList<>();`
- **Key Methods**: 
  - `add()`, `remove()`, `set()`, `get()`, `size()`
- **Dynamic Resizing**: ArrayList can grow or shrink in size
- **Iteration**: Use for-each or standard for loops
- **Autoboxing/Unboxing**: Automatic conversion between primitives and wrapper types

Benefits over `List`: You can dynamically modify, especially useful when modifying while iterating.
</details>

---

<details>
<summary><strong>Unit 8: 2D Arrays</strong></summary>

- **Declaration**: `type[][] arrayName = new type[rows][cols];`
- **Element Access**: `array[row][col]`
- **Traversing**: Use nested loops for row-column iteration
- **Applications**: Common in grids and matrix-related problems
- **Algorithms**: Processing row-wise or column-wise

2D Arrays: Basically chonkier arrays. An array within an array. THE MATRIX.

![image](https://github.com/user-attachments/assets/b74499e9-4a63-4bec-b079-3eda6a58e468)
</details>

---

<details>
<summary><strong>Unit 9: Inheritance</strong></summary>

- **Inheritance Basics**: `class Subclass extends Superclass`
- **Subclass**: Inherits fields and methods from the superclass
- **Overriding Methods**: Redefining a method from the superclass in a subclass
- **Super Keyword**: Used to call the superclass constructor or methods
- **Polymorphism**: Using a superclass reference for a subclass object
- **Object Class**: All classes derive from `Object`

Inheritance is kinda weird, but you can make your class and program structure like a tree and use the trunk to make leaves. By using `super`, you're essentially calling the superclass constructor and using its methods.
</details>

---
Yayyyyy

