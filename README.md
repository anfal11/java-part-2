# javaInputOutputExpression

This repository contains examples and code snippets demonstrating Java input/output operations, expressions, blocks, conditions, and more. These examples are designed to help you understand fundamental Java concepts and how to use them in your projects.

## Table of Contents

- [Java Input and Output](#java-input-and-output)
- [Java Expressions](#java-expressions)
- [Java Blocks and Conditions](#java-blocks-and-conditions)

## Java Input and Output

The code in this section demonstrates how to handle various input and output operations in Java, including:

- Printing text to the console using `System.out.print()`, `System.out.println()`, and `System.out.printf()`.
- Concatenating strings and variables.
- Reading different types of user input using the `Scanner` class (e.g., integers, floats, doubles, and strings).

### Example:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner java = new Scanner(System.in);

        // Getting float input
        System.out.print("Enter a float number: ");
        float myFloat = java.nextFloat();
        System.out.println("Your entered float number is = " + myFloat);

        // Getting double input
        System.out.print("Enter a double number: ");
        double myDouble = java.nextDouble();
        System.out.println("Your entered double number is: " + myDouble);
        
        java.nextLine();  // Consume the newline
        
        // Getting string input
        System.out.print("Enter a string: ");
        String myString = java.nextLine();
        System.out.println("Your entered string is " + myString);
    }
}
```

## Java Expressions

This section covers basic expressions in Java, including arithmetic operations and comparison between values.

### Example:

```java
int score = 90;
Double a = 2.2, b = 3.4, result;
result = a + b - 3.4;

if (score > 80) {
    System.out.println("Excellent score!");
}
```

## Java Blocks and Conditions

Here, you'll find examples of using blocks, conditional statements, and the ternary operator in Java.

### Example:

```java
int number = 10;

if (number > 0) {
    System.out.println("The number is positive");
} else if (number < 0) {
    System.out.println("The number is negative");
} else {
    System.out.println("The number is zero");
}

// Ternary operator
int number1 = 12, number2 = 9, number3 = 33;
int largest = (number1 >= number2) ? ((number1 >= number3) ? number1 : number3) : ((number2 >= number3) ? number2 : number3);
System.out.println("The largest number is " + largest);
```



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
