# What I learned in week 3

### Java Script
#### Monday
Learning about variables and equations

Today we did some functions and learned how they work on a JS platform

One of the main points is that the variables and functions work differently than math equations

In JS the order is the most important and so it is important to pay attention what was the last rule affecting the variable

### Tuesday
Function Parameters
        function //function declaration/ makeRed //function name/ (sender) /argument/{
            sender.style.color = 'red' //statement/
        }
Console Log
    Console log sends the function to the terminal.

To test something locally with JS you can go to terminal and used node command with doc name
        const userInput = process.argv[2] allows functions to be run in terminal with node like an app.

        The function keyword goes first, then goes the name of the function, then a list of parameters between the parentheses (comma-separated, empty in the example above) and finally the code of the function, also named “the function body”, between curly braces.

        Global variables
Variables declared outside of any function, such as the outer userName in the code above, are called global.

Global variables are visible from any function (unless shadowed by locals).

It’s a good practice to minimize the use of global variables. Modern code has few or no globals. Most variables reside in their functions. Sometimes though, they can be useful to store project-level data.