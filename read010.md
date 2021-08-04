# JavaScript book, Ch. 10, “Error Handling & Debugging”


- JavaScript can be hard to learn and everyone makes 
mistakes when writing it. This chapter will help you learn 
how to find the errors in your code. It will also teach you how 
to write scripts that deal with potential errors gracefully. 


## ORDER OF EXECUTION

To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run: 

1. The greeting variable gets its value from the 
greetUser() function.

2. greetUser() creates the message by combining 
the string 'He 11 o ' with the result of getName (). 

3. getName () returns the name to greetUser(). 

2. greetUser() now knows the name, and combines 
it with the string. It then returns the message to the statement that called it in step 1. 

1. The value of the greeting is stored in memory. 

4. This greeting variable is written to an alert box.

### EXECUTION CONTEXTS 

The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new 
new execution context. They correspond to variable scope. 

### EXECUTION CONTEXT & HOISTING


Each time a script enters a new execution context, there are two phases 
of activity: 

1. PREPARE 
• The new scope is created 
• Variables, functions, and arguments are created 
• The value of the this keyword is determined.

2. EXECUTE 
• Now it can assign values to variables 
• Reference functions and run their code 
• Execute statements


### UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code.


#### HOW TO DEAL WITH ERRORS 

- ow that you know what an error is and how the browser treats them, there are two things you can do with the errors.
1. DEBUG THE SCRIPT TO FIX ERRORS 
If you come across an error while writing a script 
(or when someone reports a bug), you will need to 
debug the code, track down the source of the error, 
and fix it.

2. 2: HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, 
throw, and f i na 1 ly statements.

**The JavaScript console** is just one of several developer tools that are found in all modern browsers


#### A DEBUGGING WORKFLOW
- Debugging is about deduction: eliminating potential causes of an error. 
Here is a workflow for techniques you will meet over the next 20 pages. 
Try to narrow down where the problem might be, then look for clues.



### BROWSER DEV TOOLS & JAVASCRIPT CONSOLE

- The JavaScript console will tell you when there is a problem with a script, 
where to look for the problem, and what kind of issue it seems to be. 


- Browser manufacturers occasionally change how 
to access these tools. If they are not where stated, 
search the browser help files for "console." 


### BREAKPOINTS 

- You can pause the execution of a script on any 
line using breakpoints. Then you can check the 
values stored in variables at that point in time.



#### THROWING ERRORS

If you know something might cause a problem for your script, you can 
generate your own errors before the interpreter creates them. 

- To create your own error, you use the following line: 
throw new Error( 1
message 1
) ;





