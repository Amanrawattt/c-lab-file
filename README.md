# c-lab-file
C# Console Programming
1. Demonstrate the working of C# SDK
This program prints a message to verify that the C# SDK is working correctly.


using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("C# SDK is working correctly.");
    }
}

2. Use of Various Data Types in C#
This program demonstrates different data types available in C#.


using System;

class DataTypesExample
{
    static void Main()
    {
        int intValue = 10;
        float floatValue = 10.5f;
        double doubleValue = 20.99;
        char charValue = 'A';
        bool boolValue = true;
        string stringValue = "Hello, C#";

        Console.WriteLine("Integer: " + intValue);
        Console.WriteLine("Float: " + floatValue);
        Console.WriteLine("Double: " + doubleValue);
        Console.WriteLine("Char: " + charValue);
        Console.WriteLine("Boolean: " + boolValue);
        Console.WriteLine("String: " + stringValue);
    }
}

3. Understanding Control Statements
This program demonstrates the use of control statements such as if-else, loops, and switch case.


using System;

class ControlStatements
{
    static void Main()
    {
        int number = 10;

        // If-Else statement
        if (number % 2 == 0)
            Console.WriteLine("Even Number");
        else
            Console.WriteLine("Odd Number");

        // For Loop
        for (int i = 1; i <= 5; i++)
            Console.WriteLine("For Loop Iteration: " + i);

        // While Loop
        int count = 0;
        while (count < 3)
        {
            Console.WriteLine("While Loop Iteration: " + count);
            count++;
        }

        // Switch Case
        int day = 3;
        switch (day)
        {
            case 1:
                Console.WriteLine("Monday");
                break;
            case 2:
                Console.WriteLine("Tuesday");
                break;
            case 3:
                Console.WriteLine("Wednesday");
                break;
            default:
                Console.WriteLine("Invalid Day");
                break;
        }
    }
}

4. Understanding Library Functions
This program demonstrates some commonly used built-in library functions in C#.


using System;

class LibraryFunctions
{
    static void Main()
    {
        string text = "Hello, C#";
        Console.WriteLine("Upper Case: " + text.ToUpper());
        Console.WriteLine("Lower Case: " + text.ToLower());
        Console.WriteLine("Length: " + text.Length);

        double sqrtValue = Math.Sqrt(25);
        Console.WriteLine("Square Root of 25: " + sqrtValue);

        int maxValue = Math.Max(10, 20);
        Console.WriteLine("Max Value between 10 and 20: " + maxValue);
    }
}

5. Various Operators in C#
This program demonstrates different types of operators used in C#.


using System;

class OperatorsExample
{
    static void Main()
    {
        int a = 10, b = 5;
        
        // Arithmetic Operators
        Console.WriteLine("Addition: " + (a + b));
        Console.WriteLine("Subtraction: " + (a - b));
        Console.WriteLine("Multiplication: " + (a * b));
        Console.WriteLine("Division: " + (a / b));
        Console.WriteLine("Modulus: " + (a % b));

        // Unary Operators
        Console.WriteLine("Increment: " + (++a));
        Console.WriteLine("Decrement: " + (--b));

        // Logical Operators
        bool x = true, y = false;
        Console.WriteLine("AND Operator: " + (x && y));
        Console.WriteLine("OR Operator: " + (x || y));
        Console.WriteLine("NOT Operator: " + (!x));

        // Bitwise Operators
        int bitA = 5, bitB = 3; // 5 = 101, 3 = 011
        Console.WriteLine("Bitwise AND: " + (bitA & bitB));
        Console.WriteLine("Bitwise OR: " + (bitA | bitB));
        Console.WriteLine("Bitwise XOR: " + (bitA ^ bitB));

        // Assignment Operators
        int num = 10;
        num += 5;
        Console.WriteLine("Assignment += : " + num);

        // Conditional (Ternary) Operator
        int min = (a < b) ? a : b;
        Console.WriteLine("Minimum Value: " + min);
    }
}
