---

# javaInputOutputExpression

This repository contains examples of Java input/output operations, expressions, blocks, and conditional statements. The code snippets include detailed comments to help you understand how different Java concepts work.

## Java Input and Output

The code in this section demonstrates various input and output operations in Java, including printing text, concatenating strings, and handling user input through the `Scanner` class.

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        // Uncomment the following lines to see different output operations

        // System.out.print("I love Java"); // just print the content inside the quote
        // System.out.println("Java is fun"); // next line refers println

        // System.out.printf("Java is interesting");
        // System.out.printf("Java is interesting");

        // System.out.println("1. Java");
        // System.out.println("2. JavaScript");

        // System.out.print("1. Kotlin");
        // System.out.print("2. Swift");

        // Concatenation
        // Double number = -10.6;
        // System.out.println("I am " + "a Java lover.");
        // System.out.println("Number = " + number);

        // Java input

        // // create an object of Scanner
        // Scanner input = new Scanner(System.in);

        // System.out.print("Enter an integer: ");

        // // take input from a user
        // int number = input.nextInt();

        // System.out.println("You have entered " + number);

        // // closing the scanner object
        // input.close();

        // Handling different types of input using Scanner

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

## Java Blocks, Conditions, and Expressions

This section illustrates how to use Java expressions, blocks, and conditional statements like `if`, `if-else`, and `ternary` operators. Each example is provided with comments to explain its purpose.

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        // Expressions in Java
        // int score;
        // score = 90;

        // Double a = 2.2, b = 3.4, result;
        // result = a + b - 3.4;

        // if (number1 == number2)
        //     System.out.println("Number 1 is greater than number 2");

        // Java statements
        // int score = 9 * 5;

        // ++i // expression
        // ++i; // statement

        // Java blocks
        // String brand = "Artcell";
        // if (brand == "Artcell") { // start of a block
        //     System.out.print("I will");
        //     System.out.print("go there");
        // }  // end of a block

        // Conditions in Java

        // If condition
        // if (condition - boolean expression) {
        //     // statement execute if condition true otherwise skip
        // }

        // int number = 10;
        // if (number < 0) { // 10 < 0
        //     System.out.println("The number is negative");
        // }
        // System.out.println("Statement is outside of if block");

        // If...else condition
        // if (condition) {
        //     // if block
        // } else {
        //     // else block
        // }

        // int number = 10;

        // if (number > 0) {
        //     System.out.println("The number is positive");
        // } else {
        //     System.out.println("The number is negative");
        // }
        // System.out.println("Outside of if else block");

        // If...else...if ladder
        // if (condition) {
        //     // code
        // } else if (condition) {
        //     // code
        // } else if (condition) {
        //     // code
        // } else {
        //     // code
        // }

        // int number = -10;
        // if (number > 0) {
        //     System.out.println("The number is positive");
        // } else if (number < 0) {
        //     System.out.println("The number is negative");
        // } else {
        //     System.out.println("The number is 0");
        // }

        // Example of finding the largest number using nested if-else
        // Double number1 = -1.0, number2 = -4.5, number3 = -5.3, largest;

        // if number1 is greater than or equal to number2
        // if (number1 >= number2) {
        //     if (number1 >= number3) {
        //         largest = number1;
        //     } else {
        //         largest = number3;
        //     }
        // } else {
        //     if (number2 >= number3) {
        //         largest = number2;
        //     } else {
        //         largest = number3;
        //     }
        // }

        // System.out.println("Largest number is: " + largest);

        // Ternary operator in Java
        // Syntax:   condition ? expression1 : expression2;

        // Scanner input = new Scanner(System.in);
        // System.out.println("Enter your math mark: ");
        // double mark = input.nextDouble();

        // Ternary operator
        // String result = (mark > 40) ? "pass" : "fail";

        // System.out.println("You have " + result + "ed the exam.");

        // input.close();

        // Example of finding the largest number using the ternary operator
        int number1 = 12, number2 = 9, number3 = 33;
        int largest = (number1 >= number2) ? ((number1 >= number3) ? number1 : number3) : ((number2 >= number3) ? number2 : number3);
        System.out.println("Largest number is " + largest);
    }
}
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
