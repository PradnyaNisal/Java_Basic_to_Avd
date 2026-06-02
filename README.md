This repository contains Java programs from beginner to advanced level. Each program includes:	
Source Code
Explanation
Output
Important Concepts

# Java Programming: Basic to Advanced

## Overview

This repository contains Java programs from beginner to advanced level. Each program includes:

* Source Code
* Explanation
* Output
* Important Concepts

---

# 1. Hello World

## Code

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

## Explanation

* `main()` is the entry point of a Java program.
* `System.out.println()` prints text on the console.

## Output

```text
Hello World
```

---

# 2. Variables and Data Types

## Code

```java
public class Main {
    public static void main(String[] args) {

        int age = 25;
        double salary = 50000.50;
        char grade = 'A';
        boolean status = true;

        System.out.println(age);
        System.out.println(salary);
        System.out.println(grade);
        System.out.println(status);
    }
}
```

## Output

```text
25
50000.5
A
true
```

---

# 3. If-Else Statement

## Code

```java
public class Main {
    public static void main(String[] args) {

        int age = 18;

        if(age >= 18) {
            System.out.println("Eligible");
        } else {
            System.out.println("Not Eligible");
        }
    }
}
```

## Output

```text
Eligible
```

---

# 4. For Loop

## Code

```java
public class Main {
    public static void main(String[] args) {

        for(int i = 1; i <= 5; i++) {
            System.out.println(i);
        }
    }
}
```

## Output

```text
1
2
3
4
5
```

---

# 5. Arrays

## Code

```java
public class Main {
    public static void main(String[] args) {

        int arr[] = {10,20,30,40};

        for(int num : arr) {
            System.out.println(num);
        }
    }
}
```

## Output

```text
10
20
30
40
```

---

# 6. Methods

## Code

```java
public class Main {

    static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {

        System.out.println(add(10,20));
    }
}
```

## Output

```text
30
```

---

# 7. Class and Object

## Code

```java
class Student {

    int id = 101;
    String name = "Pradnya";
}

public class Main {

    public static void main(String[] args) {

        Student s = new Student();

        System.out.println(s.id);
        System.out.println(s.name);
    }
}
```

## Output

```text
101
Pradnya
```

---

# 8. Constructor

## Code

```java
class Student {

    Student() {
        System.out.println("Constructor Called");
    }
}

public class Main {

    public static void main(String[] args) {

        Student s = new Student();
    }
}
```

## Output

```text
Constructor Called
```

---

# 9. Inheritance

## Code

```java
class Animal {

    void sound() {
        System.out.println("Animal Sound");
    }
}

class Dog extends Animal {
}

public class Main {

    public static void main(String[] args) {

        Dog d = new Dog();
        d.sound();
    }
}
```

## Output

```text
Animal Sound
```

---

# 10. Method Overriding

## Output

```text
Dog Sound
```

---

# 11. Abstraction

## Output

```text
Circle Drawn
```

---

# 12. Interface

## Output

```text
Printing...
```

---

# 13. Exception Handling

## Output

```text
Exception Handled
```

---

# 14. String Reverse Program

## Output

```text
avaJ
```

---

# 15. ArrayList

## Output

```text
[Java, Python]
```

---

# 16. HashSet

## Output

```text
[10, 20]
```

---

# 17. HashMap

## Output

```text
{1=Java, 2=Python}
```

---

# 18. Lambda Expression (Java 8)

## Output

```text
Lambda Expression
```

---

# 19. Stream API

## Output

```text
30
40
```

---

# 20. Multithreading

## Output

```text
Thread Running
```

---

# 21. File Handling

## Output

```text
File Created Successfully
```

---

# 22. JDBC Connectivity

Topics:

* DriverManager
* Connection
* PreparedStatement
* ResultSet

---

# 23. Collections Framework

Topics:

* List
* Set
* Map
* Queue
* Iterator

---

# 24. Java 8 Features

Topics:

* Lambda Expressions
* Functional Interface
* Method Reference
* Stream API
* Optional

---

# 25. Advanced Java

Topics:

* JDBC
* Servlet
* JSP
* Hibernate
* Spring
* Spring Boot
* REST API

---

# 26. Data Structures Using Java

Topics:

* Stack
* Queue
* Linked List
* Tree
* Graph
* Heap

---

# 27. Important Interview Programs

* Palindrome Number
* Fibonacci Series
* Prime Number
* Factorial
* Armstrong Number
* String Reverse
* Anagram
* Duplicate Elements
* Bubble Sort
* Binary Search

---

## Author

Pradnya Nisal

Computer Engineering Graduate | Java Developer
