# Functions 

**A block of code that designed to perform a task.**

**It's reuseable, which means it can be used several times.**

***-A function in JS is similar to a procedure ( a set of statements that performs a task or calculates a value ) but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.*** 

### Two ways to define a function: 

**1. Function declaretion.** 
  
  *_-consists of the function keyword, followed by:_*

  *_1-The name of the function._*

  *_2-A list of parameters to the function, enclosed in parentheses and separated by commas._*

  *_3-The JavaScript statements that define the function, enclosed in curly brackets._*

  *_For example, the following code defines a simple function:_*


     function nameOfFunction (param1,param2,param3,...){
       write the code I want to run 

       return statement
     }

**2. Function expressions.**

   **-The function keyword can be used to define a funtion inside an expression.**

  *_For example, the following code defines a simple function:_*

     var getData = function(param1,param2,param3,...){
       code I want to run 

       return statement 

     }

## Calling Functions

 **-Performs the specified actions with the indicated parameters.**

### The difference between Function declaration and Function expression .

**1. the way to write them.**

**2. The hoisting (which is about reordering), in function declaration it do not differ if you call the function before writing the function itself. But it does not work with the functiob expression because first you have to write the function then call it.**