# Java Interview Questions
Welcome to the Java Interview Questions Repository! This repository is a curated collection of Java questions categorized by difficulty: Easy, Medium, and Hard. Whether you are a beginner aiming to grasp the basics or an expert wanting to challenge yourself, this repository will help you improve your Java skills.

## Introduction

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a versatile language used for building a range of applications from web to mobile to enterprise applications. This repository is designed to help you practice and master Java by solving a variety of questions ranging from easy to hard.

## Why Java?

- **Platform-Independent**: Java's "write once, run anywhere" capability makes it a widely-used language for cross-platform applications.
- **Robust and Secure**: Java provides strong memory management and built-in security features.
- **Object-Oriented**: Java's object-oriented nature makes it easy to manage and modify code.
- **Extensive Libraries**: Java has a rich set of APIs and libraries that simplify development.

## Question Categories

### Easy

These questions cover basic Java concepts, syntax, and simple programming tasks. Ideal for beginners.

### Medium

These questions delve into more complex topics such as data structures, algorithms, and object-oriented programming principles.

### Hard

These questions are designed for advanced users and cover topics like multithreading, concurrency, advanced data structures, and performance optimization.

## Contributing

We welcome contributions from the community! If you have a question or improvement that you think should be included, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Add your question or improvement in the appropriate category folder (`easy`, `medium`, `hard`).
4. Submit a pull request with a detailed description of your changes.

---

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

### Table of Contents
### Level : Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is Java?](#1-what-is-java) |
| 2   | [Explain JVM, JRE, and JDK.](#2-explain-jvm-jre-and-jdk) |
| 3   | [What are the main features of Java?](#3-what-are-the-main-features-of-java) |
| 4   | [What is the difference between JDK and JRE?](#4-what-is-the-difference-between-jdk-and-jre) |
| 5   | [Explain public static void main(String args[]).](#5-explain-public-static-void-mainstring-args) |
| 6   | [What is a constructor in Java?](#6-what-is-a-constructor-in-java) |
| 7   | [What are the types of constructors in Java?](#7-what-are-the-types-of-constructors-in-java) |
| 8   | [What is a default constructor?](#8-what-is-a-default-constructor) |
| 9   | [Explain method overloading.](#9-explain-method-overloading) |
| 10  | [What is method overriding?](#10-what-is-method-overriding) |
| 11  | [What is inheritance?](#11-what-is-inheritance) |
| 12  | [Explain polymorphism.](#12-explain-polymorphism) |
| 13  | [What is encapsulation?](#13-what-is-encapsulation) |
| 14  | [What is abstraction?](#14-what-is-abstraction) |
| 15  | [What are the access modifiers in Java?](#15-what-are-the-access-modifiers-in-java) |
| 16  | [Explain the use of 'this' keyword.](#16-explain-the-use-of-this-keyword) |
| 17  | [What is a static method?](#17-what-is-a-static-method) |
| 18  | [What is the difference between static and non-static methods?](#18-what-is-the-difference-between-static-and-non-static-methods) |
| 19  | [What is the final keyword in Java?](#19-what-is-the-final-keyword-in-java) |
| 20  | [What are the data types in Java?](#20-what-are-the-data-types-in-java) |
| 21  | [What is the difference between int and Integer?](#21-what-is-the-difference-between-int-and-integer) |
| 22  | [What are the control statements in Java?](#22-what-are-the-control-statements-in-java) |
| 23  | [Explain the use of break and continue.](#23-explain-the-use-of-break-and-continue) |
| 24  | [What is a loop in Java?](#24-what-is-a-loop-in-java) |
| 25  | [What are the types of loops in Java?](#25-what-are-the-types-of-loops-in-java) |
| 26  | [What is an array in Java?](#26-what-is-an-array-in-java) |
| 27  | [How do you declare an array in Java?](#27-how-do-you-declare-an-array-in-java) |
| 28  | [What is the default value of an array?](#28-what-is-the-default-value-of-an-array) |
| 29  | [Explain the concept of an array of objects.](#29-explain-the-concept-of-an-array-of-objects) |
| 30  | [What is a string in Java?](#30-what-is-a-string-in-java) |
| 31  | [How do you declare a string in Java?](#31-how-do-you-declare-a-string-in-java) |
| 32  | [What is the difference between String and StringBuffer?](#32-what-is-the-difference-between-string-and-stringbuffer) |
| 33  | [What is the difference between StringBuilder and StringBuffer?](#33-what-is-the-difference-between-stringbuilder-and-stringbuffer) |
| 34  | [What are the commonly used methods of String class?](#34-what-are-the-commonly-used-methods-of-string-class) |
| 35  | [How do you compare strings in Java?](#35-how-do-you-compare-strings-in-java) |
| 36  | [What is an exception in Java?](#36-what-is-an-exception-in-java) |
| 37  | [Explain the try-catch block.](#37-explain-the-try-catch-block) |
| 38  | [What is the difference between checked and unchecked exceptions?](#38-what-is-the-difference-between-checked-and-unchecked-exceptions) |
| 39  | [What is the use of the finally block?](#39-what-is-the-use-of-the-finally-block) |
| 40  | [What is the throw keyword?](#40-what-is-the-throw-keyword) |
| 41  | [What is the throws keyword?](#41-what-is-the-throws-keyword) |
| 42  | [Explain the concept of exception propagation.](#42-explain-the-concept-of-exception-propagation) |
| 43  | [What are the types of exceptions in Java?](#43-what-are-the-types-of-exceptions-in-java) |
| 44  | [What is a custom exception?](#44-what-is-a-custom-exception) |
| 45  | [What is the use of the synchronized keyword?](#45-what-is-the-use-of-the-synchronized-keyword) |
| 46  | [What is multithreading?](#46-what-is-multithreading) |
| 47  | [What is the difference between a thread and a process?](#47-what-is-the-difference-between-a-thread-and-a-process) |
| 48  | [How do you create a thread in Java?](#48-how-do-you-create-a-thread-in-java) |
| 49  | [What is the Runnable interface?](#49-what-is-the-runnable-interface) |
| 50  | [What is the Thread class?](#50-what-is-the-thread-class) |
| 51  | [What are the states of a thread in Java?](#51-what-are-the-states-of-a-thread-in-java) |
| 52  | [What is thread priority?](#52-what-is-thread-priority) |
| 53  | [What is the difference between wait() and sleep()?](#53-what-is-the-difference-between-wait-and-sleep) |
| 54  | [What is the use of the join() method?](#54-what-is-the-use-of-the-join-method) |
| 55  | [What is the difference between notify() and notifyAll()?](#55-what-is-the-difference-between-notify-and-notifyall) |
| 56  | [What is the difference between a class and an object?](#56-what-is-the-difference-between-a-class-and-an-object) |
| 57  | [What is the use of the new keyword?](#57-what-is-the-use-of-the-new-keyword) |
| 58  | [What is the difference between an abstract class and an interface?](#58-what-is-the-difference-between-an-abstract-class-and-an-interface) |
| 59  | [What is a package in Java?](#59-what-is-a-package-in-java) |
| 60  | [What is the use of the import statement?](#60-what-is-the-use-of-the-import-statement) |
| 61  | [What is the difference between import and static import?](#61-what-is-the-difference-between-import-and-static-import) |
| 62  | [What is the use of the super keyword?](#62-what-is-the-use-of-the-super-keyword) |
| 63  | [What is the difference between an interface and a class?](#63-what-is-the-difference-between-an-interface-and-a-class) |
| 64  | [What is the use of the instanceof keyword?](#64-what-is-the-use-of-the-instanceof-keyword) |
| 65  | [What is a nested class?](#65-what-is-a-nested-class) |
| 66  | [What is an inner class?](#66-what-is-an-inner-class) |
| 67  | [What is a local inner class?](#67-what-is-a-local-inner-class) |
| 68  | [What is an anonymous inner class?](#68-what-is-an-anonymous-inner-class) |
| 69  | [What is a static nested class?](#69-what-is-a-static-nested-class) |
| 70  | [What is the use of the transient keyword?](#70-what-is-the-use-of-the-transient-keyword) |
| 71  | [What is the use of the volatile keyword?](#71-what-is-the-use-of-the-volatile-keyword) |
| 72  | [What is serialization?](#72-what-is-serialization) |
| 73  | [What is deserialization?](#73-what-is-deserialization) |
| 74  | [What is the use of the Serializable interface?](#74-what-is-the-use-of-the-serializable-interface) |
| 75  | [What is the difference between serialization and deserialization?](#75-what-is-the-difference-between-serialization-and-deserialization) |
| 76  | [What is the use of the Externalizable interface?](#76-what-is-the-use-of-the-externalizable-interface) |
| 77  | [What is the use of the readObject() method?](#77-what-is-the-use-of-the-readobject-method) |
| 78  | [What is the use of the writeObject() method?](#78-what-is-the-use-of-the-writeobject-method) |
| 79  | [What is the use of the ClassNotFoundException?](#79-what-is-the-use-of-the-classnotfoundexception) |
| 80  | [What is the use of the IOException?](#80-what-is-the-use-of-the-ioexception) |
| 81  | [What is the use of the FileNotFoundException?](#81-what-is-the-use-of-the-filenotfoundexception) |
| 82  | [What is the use of the EOFException?](#82-what-is-the-use-of-the-eofexception) |
| 83  | [What is the use of the ObjectInputStream class?](#83-what-is-the-use-of-the-objectinputstream-class) |
| 84  | [What is the use of the ObjectOutputStream class?](#84-what-is-the-use-of-the-objectoutputstream-class) |
| 85  | [What is the use of the FileInputStream class?](#85-what-is-the-use-of-the-fileinputstream-class) |
| 86  | [What is the use of the FileOutputStream class?](#86-what-is-the-use-of-the-fileoutputstream-class) |
| 87  | [What is the use of the BufferedReader class?](#87-what-is-the-use-of-the-bufferedreader-class) |
| 88  | [What is the use of the BufferedWriter class?](#88-what-is-the-use-of-the-bufferedwriter-class) |
| 89  | [What is the use of the PrintWriter class?](#89-what-is-the-use-of-the-printwriter-class) |
| 90  | [What is the use of the Scanner class?](#90-what-is-the-use-of-the-scanner-class) |
| 91  | [What is the use of the System.in?](#91-what-is-the-use-of-the-systemin) |
| 92  | [What is the use of the System.out?](#92-what-is-the-use-of-the-systemout) |
| 93  | [What is the use of the System.err?](#93-what-is-the-use-of-the-systemerr) |
| 94  | [What is the use of the printf() method?](#94-what-is-the-use-of-the-printf-method) |
| 95  | [What is the use of the format() method?](#95-what-is-the-use-of-the-format-method) |
| 96  | [What is the use of the println() method?](#96-what-is-the-use-of-the-println-method) |
| 97  | [What is the use of the print() method?](#97-what-is-the-use-of-the-print-method) |
| 98  | [What is the use of the read() method?](#98-what-is-the-use-of-the-read-method) |
| 99  | [What is the use of the write() method?](#99-what-is-the-use-of-the-write-method) |
| 100 | [What is the use of the flush() method?](#100-what-is-the-use-of-the-flush-method) |


# Easy Java Interview Questions and Answers
## 1. What is Java?
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

#### **[⬆ Back to Top](#level--easy)**
---

## 2. Explain JVM, JRE, and JDK.
- **JVM (Java Virtual Machine):** An abstract machine that enables your computer to run a Java program. It provides a runtime environment in which Java bytecode can be executed.
- **JRE (Java Runtime Environment):** A package that provides the libraries, Java Virtual Machine, and other components to run applications written in Java. It does not contain tools for Java development like compilers or debuggers.
- **JDK (Java Development Kit):** A full-featured software development kit for Java. It includes JRE as well as development tools like compilers and debuggers.

#### **[⬆ Back to Top](#level--easy)**
---

## 3. What are the main features of Java?
- **Object-Oriented:** Everything in Java is an object.
- **Platform-Independent:** Java code can run on any platform that supports Java.
- **Simple:** Easy to learn and use.
- **Secure:** Java provides a secure environment for developing applications.
- **Architecture-Neutral:** Java programs are architecture-neutral.
- **Portable:** Java programs can be carried out on any platform without any implementation.
- **Robust:** Java is strong and has strong memory management.
- **Multithreaded:** Java supports multithreading.
- **Interpreted:** Java bytecode is translated on the fly to native machine instructions.
- **High-Performance:** Java is faster than traditional interpreted programming languages.
- **Distributed:** Java is designed for the distributed environment of the internet.

#### **[⬆ Back to Top](#level--easy)**
---

## 4. What is the difference between JDK and JRE?
- **JDK:** Includes tools for developing, debugging, and monitoring Java applications.
- **JRE:** Provides the libraries and JVM necessary to run Java applications.

#### **[⬆ Back to Top](#level--easy)**
---

## 5. Explain `public static void main(String args[])`.
- **public:** Accessible from anywhere.
- **static:** Can be called without creating an instance of the class.
- **void:** Does not return any value.
- **main:** The main method is the entry point of the application.
- **String args[]:** An array of strings that stores arguments passed by the command line.

#### **[⬆ Back to Top](#level--easy)**
---

## 6. What is a constructor in Java?
A constructor in Java is a special method that is used to initialize objects. The constructor is called when an object of a class is created. It can be used to set initial values for object attributes.

```java
public class MyClass {
    int x;  // Create a class attribute

    // Create a class constructor for the MyClass class
    public MyClass() {
        x = 5;  // Set the initial value for the class attribute x
    }

    public static void main(String[] args) {
        MyClass myObj = new MyClass(); // Create an object of class MyClass
        System.out.println(myObj.x); // Print the value of x
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 7. What are the types of constructors in Java?
- **Default Constructor:** A constructor that does not accept any parameters.
- **Parameterized Constructor:** A constructor that accepts one or more parameters.

#### **[⬆ Back to Top](#level--easy)**
---

## 8. What is a default constructor?
A default constructor is a constructor that does not take any arguments. If no constructor is defined in a class, the Java compiler creates a default constructor for the class.

```java
public class MyClass {
    int x;

    public MyClass() {
        // Default constructor
        x = 0;
    }

    public static void main(String[] args) {
        MyClass obj = new MyClass();
        System.out.println(obj.x); // Output will be 0
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 9. Explain method overloading.
Method overloading allows a class to have more than one method with the same name, provided their parameter lists are different. It is a way to achieve polymorphism in Java.

```java
public class MyClass {
    static int add(int a, int b) {
        return a + b;
    }

    static double add(double a, double b) {
        return a + b;
    }

    public static void main(String[] args) {
        System.out.println(add(10, 20)); // Calls int version
        System.out.println(add(10.5, 20.5)); // Calls double version
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 10. What is method overriding?
Method overriding occurs when a subclass provides a specific implementation for a method that is already defined in its superclass. The method in the subclass must have the same name, return type, and parameters as the method in the superclass.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound(); // Calls the overridden method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 11. What is inheritance?
Inheritance is a mechanism in Java by which one class is allowed to inherit the features (fields and methods) of another class. It promotes code reusability and establishes a relationship between classes.

```java
class Animal {
    void eat() {
        System.out.println("This animal eats food");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("This dog barks");
    }

    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.eat(); // Calls the inherited method from Animal class
        dog.bark(); // Calls the method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 12. Explain polymorphism.
Polymorphism in Java allows one interface to be used for a general class of actions. The specific action is determined by the exact nature of the situation.

- **Compile-time polymorphism:** Achieved by method overloading.
- **Runtime polymorphism:** Achieved by method overriding.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound(); // Calls the overridden method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 13. What is encapsulation?
Encapsulation is the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates and keeps both safe from outside interference and misuse.

```java
public class EncapsulationExample {
    private String name;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 14. What is abstraction?
Abstraction is the process of hiding the implementation details and showing only functionality to the user. It helps to reduce complexity and allows the programmer to focus on interactions.

```java
abstract class Animal {
    abstract void sound();
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 15. What are the access modifiers in Java?
- **public:** Accessible from everywhere.
- **private:** Accessible only within the declared class.
- **protected:** Accessible within the same package and subclasses.
- **default (no modifier):** Accessible only within the same package.

#### **[⬆ Back to Top](#level--easy)**
---

## 16. Explain the use of 'this' keyword.
The `this` keyword refers to the current object in a method or constructor. It can be used to refer to the current class instance variable, invoke the current class method, or return the current class instance from a method.

```java
public class ThisExample {
    int x;

    ThisExample(int x) {
        this.x = x;
    }

    void display() {
        System.out.println("Value of x is: " + this.x);
    }

    public static void main(String[] args) {
        ThisExample obj = new ThisExample(10);
        obj.display();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 17. What is a static method?
A static method belongs to the class rather than instances of the class. It can be invoked without creating an instance of the class.

```java
public class StaticMethodExample {
    static void display() {
        System.out.println("This is a static method.");
    }

    public static void main(String[] args) {
        StaticMethodExample.display();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 18. What is the difference between static and non-static methods?
- **Static methods:** Belong to the class, can be called without creating an object, cannot access instance variables and instance methods directly.
- **Non-static methods:** Belong to an instance of the class, can access instance variables and methods.

#### **[⬆ Back to Top](#level--easy)**
---

## 19. What is the final keyword in Java?
- **final variable:** Cannot be changed once initialized.
- **final method:** Cannot be overridden by subclasses.
- **final class:** Cannot be subclassed.

```java
public class FinalExample {
    final int MAX_VALUE = 100;

    final void display() {
        System.out.println("This is a final method.");
    }

    public static void main(String[] args) {
        FinalExample obj = new FinalExample();
        System.out.println("MAX_VALUE: " + obj.MAX_VALUE);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 20. What are the data types in Java?
- **Primitive data types:** byte, short, int, long, float, double, char, boolean.
- **Non-primitive data types:** String, Arrays, Classes, Interfaces.

#### **[⬆ Back to Top](#level--easy)**
---

## 21. What is the difference between int and Integer?
- **int:** A primitive data type.
- **Integer:** A wrapper class for the primitive data type `int`.

```java
int a = 10;
Integer b = 10;
```

#### **[⬆ Back to Top](#level--easy)**
---

## 22. What are the control statements in Java?
- **Decision-making statements:** if, if-else, switch.
- **Loop statements:** for, while, do-while.
- **Branching statements:** break, continue, return.

#### **[⬆ Back to Top](#level--easy)**
---

## 23. Explain the use of break and continue.
- **break:** Terminates the loop or switch statement.
- **continue:** Skips the current iteration of a loop and proceeds to the next iteration.

```java
public class BreakContinueExample {
    public static void main(String[] args) {
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                break; // Stops the loop when i is 5
            }
            System.out.println(i);
        }

        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                continue; // Skips the iteration when i is 5
            }
            System.out.println(i);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 24. What is a loop in Java?
A loop is a programming construct that repeats a block of code as long as a specified condition is true.

#### **[⬆ Back to Top](#level--easy)**
---

## 25. What are the types of loops in Java?
- **for loop**
- **while loop**
- **do-while loop**

```java
public class LoopExample {
    public static void main(String[] args) {
        // for loop
        for (int i = 0; i < 5; i++) {
            System.out.println("For loop: " + i);
        }

        // while loop
        int j = 0;
        while (j < 5) {
            System.out.println("While loop: " + j);
            j++;
        }

        // do-while loop
        int k = 0;
        do {
            System.out.println("Do-while loop: " + k);
            k++;
        } while (k < 5);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 26. What is an array in Java?
An array is a collection of similar types of elements stored in contiguous memory locations.

#### **[⬆ Back to Top](#level--easy)**
---

## 27. How do you declare an array in Java?
```java
int[] arr = new int[5];
```

#### **[⬆ Back to Top](#level--easy)**
---

## 28. What is the default value of an array?
- **int, short, byte, long:** 0
- **float, double:** 0.0
- **char:** '\u0000'
- **boolean:** false
- **Object:** null

#### **[⬆ Back to Top](#level--easy)**
---

## 29. Explain the concept of an array of objects.
An array of objects is an array that holds references to objects of a class.

```java
class Student {
    String name;

    Student(String name) {
        this.name = name;
    }
}

public class ArrayOfObjectsExample {
    public static void main(String[] args) {
        Student[] students = new Student[3];
        students[0] = new Student("John");
        students[1] = new Student("Jane");
        students[2] = new Student("Jake");

        for (Student student : students) {
            System.out.println(student.name);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 30. What is a string in Java?
A string is a sequence of characters. In Java, strings are objects of the `String` class.

#### **[⬆ Back to Top](#level--easy)**
---

## 31. How do you declare a string in Java?
```java
String str = "Hello, World!";
```

#### **[⬆ Back to Top](#level--easy)**
---

## 32. What is the difference between String and StringBuffer?
- **String:** Immutable (cannot be changed once created).
- **StringBuffer:** Mutable (can be changed after creation), synchronized.

#### **[⬆ Back to Top](#level--easy)**
---

## 33. What is the difference between StringBuilder and StringBuffer?
- **StringBuilder:** Mutable and not synchronized (faster).
- **StringBuffer:** Mutable and synchronized (thread-safe).

#### **[⬆ Back to Top](#level--easy)**
---

## 34. What are the commonly used methods of String class?
- `length()`
- `charAt(int index)`
- `substring(int beginIndex, int endIndex)`
- `equals(Object obj)`
- `compareTo(String anotherString)`
- `toLowerCase()`
- `toUpperCase()`
- `trim()`
- `replace(char oldChar, char newChar)`

#### **[⬆ Back to Top](#level--easy)**
---

## 35. How do you compare strings in Java?
- **Using `equals()` method:** Compares the content of strings.
- **Using `==` operator:** Compares the reference of strings.

```java
String str1 = "Hello";
String str2 = "Hello";
String str3 = new String("Hello");

System.out.println(str1.equals(str2)); // true
System.out.println(str1 == str2); // true
System.out.println(str1 == str3); // false
```

#### **[⬆ Back to Top](#level--easy)**
---

## 36. What is an exception in Java?
An exception is an event that occurs during the execution of a program and disrupts its normal flow. It is an object that wraps an error event that can occur within a method and is passed to the runtime system.

#### **[⬆ Back to Top](#level--easy)**
---

## 37. Explain the try-catch block.
A `try-catch` block is used to handle exceptions. The code that might throw an exception is placed inside the `try` block, and the code to handle the exception is placed inside the `catch` block.

```java
try {
    int data = 50 / 0; // This will throw an exception
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 38. What is the difference between checked and unchecked exceptions?
- **Checked exceptions:** Checked at compile-time (e.g., IOException).
- **Unchecked exceptions:** Checked at runtime (e.g., ArithmeticException, NullPointerException).

#### **[⬆ Back to Top](#level--easy)**
---

## 39. What is the use of the finally block?
The `finally` block is used to execute important code such as closing resources. It is always executed whether an exception is handled or not.

```java
try {
    int data = 50 / 0;
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
} finally {
    System.out.println("Finally block executed");
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 40. What is the throw keyword?
The `throw` keyword is used to explicitly throw an exception.

```java
public class ThrowExample {
    static void validate(int age) {
        if (age < 18)
            throw new ArithmeticException("Not valid age");
        else
            System.out.println("Welcome to vote");
    }

    public static void main(String[] args) {
        validate(13);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 41. What is the throws keyword?
The `throws` keyword is used to declare an exception. It specifies that a method can throw a particular type of exception.

```java
import java.io.*;

public class ThrowsExample {
    void method() throws IOException {
        throw new IOException("Device error");
    }

    public static void main(String[] args) {
        try {
            new ThrowsExample().method();
        } catch (Exception e) {
            System.out.println(e);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 42. Explain the concept of exception propagation.
Exception propagation refers to the process by which an exception is passed from the point it occurred to a method that can handle it. If an exception is not caught in the current method, it is propagated to the caller method, and so on.

#### **[⬆ Back to Top](#level--easy)**
---

## 43. What are the types of exceptions in Java?
- **Checked exceptions:** Exceptions that are checked at compile-time.
- **Unchecked exceptions:** Exceptions that are checked at runtime.

#### **[⬆ Back to Top](#level--easy)**
---

## 44. What is a custom exception?
A custom exception is a user-defined exception class that extends `Exception` or `RuntimeException`.

```java
class MyException extends Exception {
    public MyException(String s) {
        super(s);
    }
}

public class CustomExceptionExample {
    public static void main(String[] args) {
        try {
            throw new MyException("Custom Exception");
        } catch (MyException e) {
            System.out.println(e.getMessage());
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 45. What is the use of the synchronized keyword?
The `synchronized` keyword is used to control the access of multiple threads to a shared resource. It ensures that only one thread can access the synchronized method or block at a time.

#### **[⬆ Back to Top](#level--easy)**
---

## 46. What is multithreading?
Multithreading is a feature of Java that allows concurrent execution of two or more parts of a program to maximize the utilization of CPU.

#### **[⬆ Back to Top](#level--easy)**
---

## 47. What is the difference between a thread and a process?
- **Thread:** A lightweight subprocess, a smallest unit of processing.
- **Process:** A heavyweight process, an independent unit of execution.

#### **[⬆ Back to Top](#level--easy)**
---

## 48. How do you create a thread in Java?
- **By extending `Thread` class**
- **By implementing `Runnable` interface**

#### **[⬆ Back to Top](#level--easy)**
---
