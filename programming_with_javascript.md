# Programming with JavaScript
## What's a script? "A series on short instructions, each of which is performed in order to solve the problem at hand." -Duckett. Analogies:
+ Recipes. Step-by-step instructions, new terms.
+ Handbook. Protocol for certain situations/scenarios. You only need to follow the steps for that case.
+ Manual. A series of tests carried out step-by-step.

## Writing a script. Steps:

1. Define the goal. What task do you want solved/completed? 
2. Design the script. Break up the various goals into series of tasks. This can be in plain English. 
3. Code each step. Use computer readable scripts like JS! 

## Operators (create a single value from two or more values)

+ Assignment operators. Give a value to any variable with `=` as in `var direction = 'up';`
+ Arithmetic operators. Basic math: `total = 4 + 4;` These are `+ - * /` plus, minus, multiply, divide, and `++, --, %`, increment (adds one to the current number), decrement, modulus (shows remainder after division of numbers). 
+ String operators. Combine (concatenate) two text values with a `+`: `hi = 'hi' + 'Tim!';`
+ Comparison operators. Greater than, less than, etc. Returns true or false. 
+ Logical operators. Combine values and return true or false. Example `&&` (AND), `|` (OR),  

## Expressions 
+ Evaluate to one value.
+ Rely on operators to determine the final value. 

## Functions (a series of statements grouped together because they do a specific thing...a way to store these steps to be performed)
+ Packaged in a code block (one or more statements in curly braces) `{}` 
+ Parameters `()` are values passed to the function before the steps in curly braces are performed on the values. Not all functions have these, though they all have `()` after the name of the function.  
+ Return value. For when you want the function to give you a calculated value. Uses return keyword. 
+ Functions are defined beginning with `function` keyword.
+ Function are named after `function` keyword with camelCase. Sometimes called an <i>identifier</i>.

Example: 

        function speakFrench() {
            document.write('Bonjour');
        }      

The code inside the function is sort of like a mini-function, called a <i>method</i>. 

Returning a value:<br>

        function getArea(width, height) {
            return width * height;
        }

Every time this function is called, the values of the variable width and height may change. However, because they will need to be known to calculate area, they must be passed in as `parameters`. Note that they are seperated by a comma. There can be more than two, FYI. 