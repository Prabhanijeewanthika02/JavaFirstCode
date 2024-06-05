Lesson 01 :

---

# Welcome to My First Java Code

### Introduction

This is my very first Java program! It's a simple "Hello World" example that prints the message to the console.

### Code Explanation

```java
public class FirstJavaCode {

    public static void main(String[] args) {
        
        System.out.println("Hello World"); 
        
    }
    
}
```

#### Code Explanation:

- **`public class FirstJavaCode {`**: Defines a class named `FirstJavaCode`. In Java, the filename must match the class name exactly.

- **`public static void main(String[] args) {`**: This line signifies the start of the program's execution. Every Java application starts executing from the `main` method.

- **`System.out.println("Hello World");`**: This line prints the string "Hello World" to the console. `System.out` is an object that represents the console, and `println` is a method to print a line.

### How to Run

To run this Java program, follow these steps:

1. **Compile**: Open our terminal or command prompt, navigate to the directory containing `FirstJavaCode.java`, and compile the code using the `javac` command:
   ```
   javac FirstJavaCode.java
   ```

2. **Execute**: After compiling successfully, run the compiled program using the `java` command:
   ```
   java FirstJavaCode
   ```

3. **Output**: We should see the message "Hello World" printed to the console.
