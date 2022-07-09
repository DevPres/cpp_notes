# Braced  Initialization

```c++
int number1{0}; // first integer to add (initialized to 0)
int number2{0}; // second integer to add (initialized to 0)
int sum{0}; // sum of number1 and number2 (initialized to 0)
```

declarations—number1, number2 and sum are the names of variables. These declarations specify that the variables number1, number2 and sum are data of type int, meaning they will hold integer (whole number) values, such as 7, –11, 0 and 31914. All variables must be declared with a name and a data type.

Lines 8–10 initialize each variable to 0 by placing a value in braces ({ and }) immediately following the variable’s name. This is known as braced initialization, which was introduced in C++11. Although it’s not always necessary to initialize every variable explicitly, doing so will help you avoid many kinds of problems.

## Naming convention

By convention, variable-name identifiers begin with a lowercase letter, and every word in the name after the first word begins with a capital letter—e.g., firstNumber starts its second word, Number, with a capital N. This naming convention is known as camel case, because the uppercase letters stand out like a camel’s humps.