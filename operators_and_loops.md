# Operators and Loops

## Tony Robbins and and AI (loops for thought)

I just watched a video of Tony Robbins, the inspirational speaker and self help guru, interviewing an AI. Someone commented, "the AI might not have mastered emotions, but it can sure turn a metaphor." 

That got me thinking how language and speciifcally comparisons and metaphors, are complex yet also simple enough to be quantified/qualified logically. 

As for emotions, I suppose they are kind of like, to use a very basic analogy, like the display of a webpage. to an AI without any neurotransmitters and hapiness hormones, like us! They are but an imperfect mirror of their creator's personalities, and serve only to make the AI seem more appealingly human, i.e. likeable. 

Emotions also help guide the AI, because it responds to human emotions detected as input. 

The dark side is that an AI can be instructed, code-wise, based on certain input, or not, to display hate or anger, or to instill it. If the programmer chooses the right logical operators, code, neural net framework, etc., or if the code behaves in an unexpected way, it has been ethically compromised, potentially. 

We expect that the code impoyed by AI has been vetted and refactored to be beyond reproach, beyond hacking, perhaps by Tony Robbins himself (lol!). Perhaps we can only pray and code, friends, and stay aware of ethical infosec principles in software development (information security). But the issues here speak volumes to the need for inpired, rigorous coding in our day and age more than ever. 

These issues also speak to the need to imploy sound, ethical logic in code. Which brings me to JavaScript operators and loops! Whew! 

- Conditions and Conditional statments. 

- `if` statements use an inherent, automatic if/then logic without having to write "then." They also can use `else` which basically means, "if not."

       if (happiness_level > 50) {
         console.log('You are doing OK. Remember, you can do this! Keep trying!; 
      } 
      else { 
        console.log('Hope you feel better. Don't give up!');        
      }

## Logical `%%`, `||`, and `!` operators (AND, OR, and NOT). 

These all evaluate to  `true` or `false`. 

`&&` asks 'do both or all expressions evaluate to true?' If not, the assigned value in memory for that statment (which is often assigned to a variable) is `false`. If so, `true`.  

        if (1 > 0 && true == false) { 
             console.log('AND-mein!');
        }
          else {
              console.log('false.');
        }
        
        >>false.


|| asks, 'is one of these expressions `true` (such as is `true == true` (yes) or is `(1 > 0)` true (yes). Even if the other expression is false, as in: 

          if (1 > 0 || true == false) { 
             console.log('Truthy OR, bro!');
          }
          else {
              console.log('false.');
          }
        
        >>Truthy OR, bro!

NOT `!` operator (also note how the Boolean value of `true`, or potentially `false`, is returned automatically/ You will only see this in a terminal/console, not displayed on a webpage). 
`false` is the return value:  

        !(1 == 1); 
        
        >>false

Variables are usually assigned to these evaluations, often in function that additionally define different objects, or classes of objects, and call certain methods for those objects. 

Hopefully you are beginning to understand some of those concepts. Just remember that objects represent real world objects, like the webpage index.html document, and have methods you can call to do things, or choose things about, that object, like document.write() (writes to the page) or document.getElementById() chooses an html/css ID in the document to do something with.  

In this case it will usually give it a variable to do perform more logical steps on, such as displaying it (a method) with certan propeties: 

        var x = document.getElementById("demo");  
         // Get the element with id="demo"
        x.style.color = "red";                     
        // Change the color of the element

In this case `.color` is the property of the `.style` method called on the object `x`. Yes, a variable can be an object! 

# `while` and `for` loops

## `while`

        while (i < 10) {
     text += "  number is " + i;
         i++;
        }

FYI `i` stages for integer.

The logged output (if coded to log to console) would be:

        >> number is 0
         number is 1
         number is 2
         number is 3
         number is 4
         number is 5
         number is 6
         number is 7
         number is 8
         number is 9


## `for` 
Instead of writing:

     text += cars[0] + "<br>";
     text += cars[1] + "<br>";
     text += cars[2] + "<br>";
     text += cars[3] + "<br>";
     text += cars[4] + "<br>";
     text += cars[5] + "<br>";

You can write:

    var i;
     for (i = 0; i < cars.length; i++) 
    text += cars[i] + "<br>";
    }

Result if logged: 

    >>BMW
    Volvo
    Saab
    Ford
    Fiat
    Audi

## Arrays

The previous example was actually incomplete because it left out the array object that was created by assigned different cars to that object. The whole page would look like this: 

    <!DOCTYPE html>
    <html>
            <body>
                <h2>JavaScript For Loop</h2>
                    <p id="demo"></p>
    <script>
    
    var cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"];
    var text = "";
    var i;
    for (i = 0; i < cars.length; i++) {
    text += cars[i] + "<br>";
    }
    
    document.getElementById("demo").innerHTML = text;
        
        </script>

            </body>
     </html>

The cars inside the brackets are actually integer numbers in the array, staring with the 0 position. Assigning `i` to `0` means starting the loop with the first car, and counting up until the length of the array has been looped (`++i`).

`{
    text += cars[i] + "<br>";
    }` just adds the text/string together. Because they aren't numbers, they are just displayed sequentially. 

[See this Mozilla Dev page for more info on all the Assignment operators, such as `+=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators#Assignment_operators)

[For all operators and assignment operators](https://www.w3schools.com/js/js_operators.asp)
