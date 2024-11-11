Learning the "Codigo" Language

In this tutorial, we’ll explore the basics of Codigo, a custom programming language inspired by C++. Codigo is designed to be simple yet powerful, providing you with all the essential tools to write and execute code. It includes variables, conditionals, loops, functions, and basic arithmetic operations.

1. Variable Declarations

In Codigo, you can declare three types of variables: integers, floating-point numbers, and strings.

- `var`: Declares an integer variable.
- `float`: Declares a floating-point variable.
- `text`: Declares a string variable.

Example Syntax:
- `var x = 10;`  — Declares an integer variable `x` and assigns it the value 10.
- `float pi = 3.14;` — Declares a floating-point variable `pi` and assigns it the value 3.14.
- `text name = "John";` — Declares a string variable `name` and assigns it the value `"John"`.

Usage Example:
var x = 10;
float pi = 3.14;
text name = "John";

2. Printing Output

To display values or messages in the console, you use the `print` statement.

Syntax:
print <variableName>;

You can print variables or direct text.

Usage Example:
print x;  // Prints the value of 'x' (10)
print name;  // Prints "John"
print "Hello!";  // Prints the text "Hello!"

3. Conditional Statements

Conditional statements allow you to make decisions in your program based on conditions. You can use `if` and `else` blocks.

Syntax:
if (<condition>) {
    // Code to execute if condition is true
} else {
    // Code to execute if condition is false
}

Usage Example:
if (x > 5) {
    print "x is greater than 5";  
} else {
    print "x is less than or equal to 5";  
}

if (name == "John") {
    print "Hello, John!";
} else {
    print "Who are you?";
}

4. Loops

Loops are used to repeat a block of code multiple times. Codigo supports `while` loops.

Syntax:
while (<condition>) {
    // Code to repeat as long as condition is true
}

Usage Example:
while (x > 0) {
    print x;
    x = x - 1;  // Decrements x by 1 each time
}
This loop will keep executing as long as `x` is greater than 0, printing the value of `x` and decreasing it with each iteration.

5. Functions

Functions in Codigo allow you to define reusable code blocks. Functions can accept parameters and return values.

Syntax for Defining a Function:
func <functionName>(<param1>, <param2>, ...) {
    // Code block
    return <value>;
}

Syntax for Calling a Function:
call <functionName>(<arguments>);

Usage Example:
func add(a, b) {
    return a + b;
}

var result = add(3, 4);   // Calls the 'add' function with arguments 3 and 4
print result;  // Prints the result (7)

6. Arithmetic Operations

Codigo supports basic arithmetic operations, which can be performed on integers and floating-point numbers.

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Modulus (remainder): `%`

Usage Example:
var a = 5;
var b = 3;

var sum = a + b;       // sum = 8
var product = a * b;   // product = 15
var quotient = a / b;  // quotient = 1
var remainder = a % b; // remainder = 2

print sum;       // Prints 8
print product;   // Prints 15
print quotient;  // Prints 1
print remainder; // Prints 2

7. Advanced Features (Optional)

While the basics are enough for most tasks, you can extend Codigo with more advanced features, such as:

- Arrays: Store multiple values in a single variable.
- Nested Loops/Conditionals: Combine loops and conditionals to create more complex logic.
- Error Handling: Add checks for invalid operations or undefined variables.

Sample Codigo Program

Here’s an example of a simple Codigo program that combines all the concepts we've discussed.

# Variable declarations
var x = 10;
float pi = 3.14;
text name = "Alice";

# Print values
print "Program Start";
print x;  // Prints 10
print pi; // Prints 3.14
print name;  // Prints Alice

# Conditional statements
if (x > 5) {
    print "x is greater than 5";  
} else {
    print "x is less than or equal to 5";  
}

# While loop
while (x > 0) {
    print x;
    x = x - 1;  // Decrement x
}

# Function definition and usage
func multiply(a, b) {
    return a * b;
}

var result = multiply(4, 5);
print result;  // Prints 20

Expected Output:
Program Start
10
3.14
Alice
x is greater than 5
10
9
8
7
6
5
4
3
2
1
20

With this knowledge, you're ready to start writing and running Codigo programs, using basic concepts like variables, loops, conditionals, functions, and arithmetic operations.
