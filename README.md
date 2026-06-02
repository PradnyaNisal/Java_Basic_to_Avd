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

## Code

```java
class Animal {
    void sound() {
        System.out.println("Animal Sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog Sound");
    }
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
Dog Sound
```

---

# 11. Abstraction

## Code

```java
abstract class Shape {
    abstract void draw();
}

class Circle extends Shape {
    void draw() {
        System.out.println("Circle Drawn");
    }
}

public class Main {
    public static void main(String[] args) {
        Shape s = new Circle();
        s.draw();
    }
}
```

## Output

```text
Circle Drawn
```

---

# 12. Interface

## Code

```java
interface Printable {
    void print();
}

class Test implements Printable {
    public void print() {
        System.out.println("Printing...");
    }
}

public class Main {
    public static void main(String[] args) {
        Test t = new Test();
        t.print();
    }
}
```

## Output

```text
Printing...
```

---

# 13. Exception Handling

## Code

```java
public class Main {
    public static void main(String[] args) {

        try {
            int a = 10 / 0;
        } catch (Exception e) {
            System.out.println("Exception Handled");
        }
    }
}
```

## Output

```text
Exception Handled
```

---

# 14. String Reverse Program

## Code

```java
public class Main {
    public static void main(String[] args) {

        String str = "Java";

        for (int i = str.length() - 1; i >= 0; i--) {
            System.out.print(str.charAt(i));
        }
    }
}
```

## Output

```text
avaJ
```

---

# 15. ArrayList

## Code

```java
import java.util.*;

public class Main {
    public static void main(String[] args) {

        ArrayList<String> list = new ArrayList<>();

        list.add("Java");
        list.add("Python");

        System.out.println(list);
    }
}
```

## Output

```text
[Java, Python]
```

---

# 16. HashSet

## Code

```java
import java.util.*;

public class Main {
    public static void main(String[] args) {

        HashSet<Integer> set = new HashSet<>();

        set.add(10);
        set.add(20);

        System.out.println(set);
    }
}
```

## Output

```text
[10, 20]
```

---

# 17. HashMap

## Code

```java
import java.util.*;

public class Main {
    public static void main(String[] args) {

        HashMap<Integer, String> map = new HashMap<>();

        map.put(1, "Java");
        map.put(2, "Python");

        System.out.println(map);
    }
}
```

## Output

```text
{1=Java, 2=Python}
```

---

# 18. Lambda Expression (Java 8)

## Code

```java
interface Demo {
    void show();
}

public class Main {
    public static void main(String[] args) {

        Demo d = () -> System.out.println("Lambda Expression");

        d.show();
    }
}
```

## Output

```text
Lambda Expression
```

---

# 19. Stream API

## Code

```java
import java.util.*;

public class Main {
    public static void main(String[] args) {

        List<Integer> list = Arrays.asList(10, 20, 30, 40);

        list.stream()
            .filter(x -> x > 20)
            .forEach(System.out::println);
    }
}
```

## Output

```text
30
40
```

---

# 20. Multithreading

## Code

```java
class MyThread extends Thread {

    public void run() {
        System.out.println("Thread Running");
    }
}

public class Main {
    public static void main(String[] args) {

        MyThread t = new MyThread();

        t.start();
    }
}
```

## Output

```text
Thread Running
```

---

# 21. File Handling

## Code

```java
import java.io.FileWriter;

public class Main {
    public static void main(String[] args) {

        try {
            FileWriter fw = new FileWriter("test.txt");
            fw.write("Hello Java");
            fw.close();

            System.out.println("File Created Successfully");
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}
```

## Output

```text
File Created Successfully
```
