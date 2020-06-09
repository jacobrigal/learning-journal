# Computer Architecture

## Four things common to all computers: 
1. Accept input
2. Store the input/data. 
3. Process the input/data.
4. Output the data. 

## Input 
+ User supplied data. Can come from mouse clicks, keystrokes, touch screen, sound, camera, and more. 
## Store info
+ Memory is where this happens (usally in RAM).
## Processing 
+ Data from memory is manipulated/changed using a series of commands (algorithms), then sends the changed info back to memory. 
##
Output
+ Information is sent back to a peripheral device, the screen, the speakers, or the network. In the latter case, the output becomes the input for another device.   

## BITS and BYTES
An on or off state in a wire = 1 (on) or 0 (off). 

8 wires can store 256 numbers in binary (0s and 1s), and 32 wires can store over 4 billion values.

## TEXT, IMAGES in BINARY
Letter are assigned a binary numbers, each color in a pixel also has a binary/number value. Sound can also be broken down into a range of numbers. Higher quality means a higher range of numbers (a more accurate representation).

## Circuits
Circuits modify and process input. They can flip the signal (NOT circuit), ADD bits, and other simple, logical calculations. Connecting them can do more complicated caculations. Smaller equals faster.

## Display a letter, step by step

1. Type a letter. 
2. Keyboard converts it to a binary number, sends to memory. 
3. Processor/CPU calculates how to display this letter.
4. CPU requests step by step instructions from memory on how to draw the letter.
5. Result stored in memory.
6. Results are outputted to screen, which converts the binary into pixels that are displayed. 

# Hardware/Software

+ Hardware = Stuff on the motherboard like circuits, chips like RAM, ROM, the CPU, as well as the Hard drive, track pad, and speakers. 

+ Software is the coded info that is stored, processed, and displayed through hardware. The OS manages this software that controls the hardware.

JavaSript is a high level coding language that uses human readable language to execute instructions in binary on the hardware. One Javascript function can execute hundreds or thousands of machine instructions in binary. 

# Javascript Data Types 

Variables in JS can hold different data types. This means that they are dynamic. Adding two different data types together will usually produce an error. However, if a number (integers) and a string (text) are added together, JS will write/log the variable as a string:

    var x = 20 + 4  + "Hens";
    console.log(x);
<br>

This logs the following to the console:
      
     >204Hens

## Strings/Text Strings

A series of characters, which is text. Best practice puts strings inside single quotes. This helps to distinguish it from html double quotes. Exceptions might be when using a single or double quote inside the string: 

    <p id="demo"></p>
    <script>
    var answer1 = "Hello world!";
    var answer2 = "Hello 'Bob!'";
    var answer3 = 'Hello "Bob!"';

    document.getElementById("demo").innerHTML =
    answer1 + "<br>" + 
    answer2 + "<br>" + 
    answer3;
    </script>


<br>
This will print the following to the webpage (because the JS is rendered in an .html webpage):
     
     Hello world!
     Hello 'Bob!'
     Hello "Bob!"

## Numbers 

    var x1 = 34.00;     // Written with decimals
    
    var x2 = 34;        // Written without decimals   

Big numbers/small numbers:

    var y = 123e5;      // 12300000
   
    var z = 123e-5;     // 0.00123

Math can be performed on these numbers (this example logs the math performed on the variables x1 and x2 shown at the start of this subsection):

    console.log(x1 + x2);
<br>
Logs:

    >68.00

## Booleans

Like a lightswitch that only has two settings/outputs: `true` and `false`. It tells you if a statement is true:

    var a = 1; 
    var b = 2;
    var c = 1;
    
    console.log(a == c);
    console.log(a == b);
    console.log(a != c);
    console.log(b > a);
<br>
Logs:

    >true
    false
    false
    true

##### Note on operators: the comparison in a boolean uses operators, such as those shown in the above example (`==` (equal) `!=` (not equal), etc.) 

## Arrays 
##### Examples from [W3 schools](https://www.w3schools.com/js/tryit.asp?filename=tryjs_datatypes_array) explain this data type:


    <h2>JavaScript Arrays</h2>

    <p>Array indexes are zero-based, which means the first item is [0].</p>

    <p id="demo"></p>

    <script>
    var cars = ["Saab","Volvo","BMW"];

    document.getElementById("demo").innerHTML = cars[0];
    </script>
<br>
Renders (more or less, on a webpage): 

    JavaScript Arrays
    
    Array indexes are zero-based, which means the first item is [0].

    Saab

## Objects

##### [W3 schools example](https://www.w3schools.com/js/tryit.asp?filename=tryjs_datatypes_object):

    <!DOCTYPE html>
    <html>
    <body>

    <h2>JavaScript Objects</h2>

    <p id="demo"></p>

      <script>
      var person = {
      firstName : "John",
      lastName  : "Doe",
      age     : 50,
      eyeColor  : "blue"
    };

    document.getElementById("demo").innerHTML =
    person.firstName + " is " + person.age + " years old.";
    </script>

    </body>
    </html>

Displays: 

      JavaScript Objects
      
      John is 50 years old.

## Undefined

This is a variable without a value assigned with an `=`:
    
    var yo;    // Value is undefined, type is undefined

