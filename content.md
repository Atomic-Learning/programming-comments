Comments are annotations in the source code of a program that are ignored when the code is executed.

# In-Line Comments

An "in-line" comment is a comment that is placed on the same line as a piece of code, such as in the pseudocode example below:

```
SET total TO 0  // Initialize total to zero
FOR EACH item IN list  // Loop through each item in the list
    ADD item TO total  // Add the current item to total
END FOR
```

In this example, the comments follow the `//` character (different languages will use different characters to indicate a comment) and provide explanations for each line of code, making it easier for someone reading the code to understand its purpose and functionality. Don't worry if you are unfamiliar with what the code is doing; the focus here is on how comments are used rather than the specific programming language.

# Comments Lines

Comments may also be placed on their own lines, separate from any code. This is useful for providing more detailed explanations or for temporarily disabling code during debugging. For example:

```
// This function calculates the factorial of a number
FUNCTION factorial(n)
    IF n IS 0 THEN
        RETURN 1  // Base case: factorial of 0 is 1
    ELSE
        RETURN n * factorial(n - 1)  // Recursive case
    END IF
END FUNCTION
```

# Block Comments

Some programming languages support block comments, which allow you to comment out multiple lines of code at once. Block comments are typically enclosed within specific start and end markers. For example:

```
/*
This is a block comment.
It can span multiple lines.
*/
```

# Purpose of Comments

Comments serve several important purposes in programming:

* **Explain Code:** They help explain what the code does, making it easier for others (or yourself at a later date) to understand the logic and purpose behind the code.
* **Improve Readability:** Well-placed comments can improve the overall readability of the code, making it easier to follow complex logic.
* **Debugging Aid:** Comments can be used to temporarily disable parts of the code during debugging without deleting the code.
* **Documentation:** They can serve as documentation for functions, classes, and modules, describing their purpose, parameters, and return values.
