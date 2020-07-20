# Chapter 10 - Error handling & Debugging

1. Order of Execution
    * order in which statements are processed 

1. Execution Context
    * Global Context - code that is in the script, but not a function
    * Function Context - Code ran without a function (each function has its own function context)
    * EVAL Context

1. Variable Scope
    * Global Variable - declared outside a funtion, can be used anywhere because it has a global scope
    * Function Level Scope - When a variable is declared within a function, it can only be used within that function.

1. The Stack
    * JavaScript interpreter processes one line of code at a time.

1. Two phases each time a script enters a new execution context
    1. Prepare - new scope created, variable, functions and arguments are created. The value of 'this' keyword is determined.
    1. Execute - Can assign values to variables, reference functions can run their code, execute statements

1. Lexical Scope
    * functions are linked to the object they were difined within

1. Understanding Errors
    * If a JavaScript statement generates an error, then it throws an EXCEPTION

1. Error Objects
    * Properties --  
    Name: Type of Execution  
    Message: Description  
    fileNumber: Name of the JavaScript file  
    lineNumber: Line number of error

    * Seven types of built-in error objects
        1. Error - Generic Error is template
        1. SyntaxError - Syntax has not been followed
        1. ReferrenceError - Tried to reference a variable that is not declared/within scope
        1. TypeError - An unexpected data type that cannot be coerced
        1. RangeError - Numbers not in acceptable range
        1. URIError - 
        1. EvalError
