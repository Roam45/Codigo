Tutorial: Learning the "Codigo" Language
In this tutorial, we will explain how to use and understand the Codigo language, which has a simple, C++-like syntax for basic programming tasks. Codigo supports features like variables, conditionals, loops, functions, and basic arithmetic operations.

Overview of Codigo
"Codigo" is a custom language designed to provide an easy way to write code similar to C++. It offers a small subset of features necessary for writing programs, such as:

Variables (with data types such as integers, floating-point numbers, and strings)
Printing output
Conditional statements (like if conditions)
Loops (like while loops)
User-defined functions
Let’s dive into each feature and its syntax.

1. Variable Declarations
In Codigo, you can declare variables with specific data types: integers, floating-point numbers, and strings.

Syntax for Variable Declarations:
codigo
Copy code
var <variableName> = <value>;
float <variableName> = <value>;
text <variableName> = "<value>";
var: Used to declare an integer variable.
float: Used to declare a floating-point variable.
text: Used to declare a string variable.
Examples:
codigo
Copy code
var x = 10;       // Declares an integer variable 'x' and assigns it the value 10
float pi = 3.14;  // Declares a float variable 'pi' and assigns it the value 3.14
text name = "John";  // Declares a string variable 'name' and assigns it "John"
In these examples, x is an integer, pi is a floating-point number, and name is a string.

2. Printing Output
To print values or messages to the console, you use the print command.

Syntax:
codigo
Copy code
print <variableName>;
You can print variables or text directly.
Examples:
codigo
Copy code
print x;          // Prints the value of variable 'x' (which is 10)
print name;       // Prints the value of variable 'name' (which is "John")
print "Hello!";   // Prints the string "Hello!"
The print statement allows you to display values or messages from your code to the console.

3. Conditional Statements
Conditional statements allow you to make decisions in your program. In Codigo, you can use if and else to control the flow based on certain conditions.

Syntax:
codigo
Copy code
if (<condition>) {
    // code to execute if condition is true
} else {
    // code to execute if condition is false
}
The if block executes the code inside if the condition evaluates to true.
The else block executes the code inside if the condition is false.
Examples:
codigo
Copy code
if (x > 5) {
    print "x is greater than 5";   // Prints if x is greater than 5
} else {
    print "x is less than or equal to 5";   // Prints if x is less than or equal to 5
}

if (name == "John") {
    print "Hello John!";
} else {
    print "Who are you?";
}
In the first example, if x is greater than 5, the message "x is greater than 5" will be printed. If not, "x is less than or equal to 5" will be printed.

4. Loops
Loops allow you to repeat a block of code multiple times. In Codigo, we have while loops.

Syntax:
codigo
Copy code
while (<condition>) {
    // code to repeat while condition is true
}
The loop will continue executing the block of code as long as the condition evaluates to true.
The condition is evaluated before every iteration.
Examples:
codigo
Copy code
while (x > 0) {
    print x;
    x = x - 1;    // Decreases x by 1 in each iteration
}
In this example, the loop will print the value of x and then subtract 1 from x on each iteration. The loop will continue until x is no longer greater than 0.

5. Functions
Functions in Codigo allow you to group reusable code into blocks. Functions can accept parameters and return values.

Syntax:
codigo
Copy code
func <functionName>(<param1>, <param2>, ...) {
    // function body
    return <value>;
}
func: Keyword used to define a function.
return: Returns a value from the function.
Examples:
codigo
Copy code
func add(a, b) {
    return a + b;
}

var result = add(3, 4);   // Calls the add function with arguments 3 and 4
print result;             // Prints the result (7)
In this example:

The function add takes two parameters a and b and returns their sum.
We then call add(3, 4) and store the result in the variable result.
Finally, we print result, which will display 7.
6. Arithmetic Operations
Codigo supports basic arithmetic operations for integers and floats. You can use the following operators:

Addition: +
Subtraction: -
Multiplication: *
Division: /
Modulus (remainder): %
Examples:
codigo
Copy code
var a = 5;
var b = 3;
var sum = a + b;      // sum = 8
var product = a * b;  // product = 15
var quotient = a / b; // quotient = 1
var remainder = a % b; // remainder = 2

print sum;        // Prints 8
print product;    // Prints 15
print quotient;   // Prints 1
print remainder;  // Prints 2
These operations work for both integers and floating-point numbers.

7. Advanced Features (Optional)
While the basics are sufficient for many tasks, you can also extend the functionality by introducing:

Arrays: You can store multiple values in a single variable using arrays.
Complex Functions: Functions with multiple parameters or nested functions.
Nested Loops and Conditionals: Combining loops and conditionals for more complex logic.
Sample Codigo Program
Here is a simple example program in Codigo that uses all the features we've covered so far.

codigo
Copy code
// Variable declarations
var x = 10;
float pi = 3.14;
text name = "Alice";

// Printing values
print "Program Start";
print x;
print pi;
print name;

// Conditional statements
if (x > 5) {
    print "x is greater than 5";
} else {
    print "x is less than or equal to 5";
}

// While loop
while (x > 0) {
    print x;
    x = x - 1;    // Decrement x
}

// Function definition and usage
func multiply(a, b) {
    return a * b;
}

var result = multiply(4, 5);
print result;  // Prints 20
Output:
csharp
Copy code
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
Conclusion
This concludes our tutorial on Codigo! You now know how to:

Declare variables
Print outputs to the console
Use conditionals (if, else)
Use loops (while)
Define and call functions
Perform basic arithmetic operations
This small but powerful language allows you to express logic in a clear and straightforward way, similar to C++, while keeping things simple for beginners. You can extend Codigo by adding more complex features like arrays, objects, or more advanced function definitions.

Feel free to experiment with the code and create your own programs in Codigo!



