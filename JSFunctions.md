# JavaScript Expressions and Functions

Every time a computer performs a task, it follows a set of very specific instructions. Design becomes a big part of prgramming. Always start with a big picture and keep breaking down tasks into smaller pieces as you move along.

- Define the goal. Flowcharts are a usfull tool to get high-level tasks.
- Design the script. Focus on individual tasks.
- Code each step. Time to implement what you designed.

## Expressions

Expressions can assign value to a variable. Ex:

var name = "Cody";

Or they can use two or more values to return a single value. Ex:

var total = 15 * 5 

Expressions use operators. Operators can be assignment(=), arithmetic (*,-,/,%,++), string ("text"), coparison (>, <, >=, <=), and logical (&&,||,!)


## Functions

Functions group a series of statements together to avoid doing repetitive work.

To use a function, it's necessary to first *declare* it. Some functions can have parameters, which are placed inside (). "Return" keyword is used to return the value to the code that called the function.

function area (width, height){
return width * height;
}

After the function has been declared, it is possible to execute it, or *Call* it. The parameters in the () will be passed to the function and executed within. 

area (3,5)
