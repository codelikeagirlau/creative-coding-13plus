# Creative Coding with Processing
Join us for a two-hour introduction to coding through digital art-making using the open source language of Processing. Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts. Learn the basics in a sociable, fun and engaging context. Code Like a Girl workshops are a great place for girls and women to come together and learn to code for the first time; the team not only teach computational thinking and coding skills but we put a great emphasis on empowering girls and women to feel confident in the area of technology. Equipment will be provided and no previous knowledge of coding is required for this workshop.

## Learning Objectives

In this workshop, we will cover the following:

 - Learn how to make basic shapes with Processing
 - Learn about RGB colours and how these differ from paint colours
 - Apply what you've learned to create sketches
 - Learn some basic programming concepts
 - Apply these concepts to make editing and enhancing your sketches easier
 - Use data from the mouse to animate your sketch

 ## Setting Up
 - Make sure you have a computer with Processing installed on it
 - If you don't have a copy, you can download Processing here https://processing.org/download/

 ## Getting started

 - Open up Processing on your computer
 - Go to the File menu and click New
 - To create your first sketch, set the size of the canvas with the command `size(500,500);`
 - Save your sketch by clicking CTRL+S or Command + S
 - Click the play button. You should see a blank sketch

 ### Activity 1: Practise using basic Processing commands
 
 * We will learn to understand the canvas and draw some basic shapes
 * The canvas on a computer has an x-axis from left to right and a y-axis from top to bottom
 * Create a basic shape like a rectangle by typing `rect(10,10,200,100);`
 * Try out the following code to draw an ellipse and a triangle:
   - `ellipse(120,120,150,200);`
   - `triangle(110,100,130,100,120,110);`
 * Try out some other shapes

 #### Basic shapes
 |    |
 |----|
 | line(x1, y1, x2, y2) |
 | ellipse(x, y, width, height) |
 | rect(x, y, width, height)	|
 | rect(x, y, width, height, radius) |
 | rect(x1, y1, x2, y2,x3, y3, x4, y4) |
 | quad(x1, y1, x2, y2,x3, y3, x4, y4) |
 | triangle(x1, y1, x2, y2,x3, y3) |
 |  |

 #### Adding colour

 * To add colour we will use two commands, **fill** and **stroke**.
 * Each command is followed by three numbers, the RGB colour, that represent the colour in terms of its primary colours: red, green and blue
 * Each colour can have a value between 0 and 255 of each of the primary colours

 |    |
 |----|
 | fill(r,g,b) |
 | stroke(r,g,b) |
 |  |

 0 = no colour, 255 = full colour.
 - Remember RGB colours combine differently to the way that paint colours do
 - The RGB primary colours are red, green and blue
 - Some example colours:
   - Red is (255,0,0)
   - Green is (0,255,0)
   - Cyan is (0,255,255)
   - Black is (0,0,0)
   - White is (255,255,255)
 - Use https://htmlcolorcodes.com/color-picker/ to help you pick
 
  #### Practise!
  - Create a sketch
  - Draw a few simple shapes
  - Practise using different strokes and fills to colour the shapes
  - **CHALLENGE**: Can you use what you’ve learnt to draw an eye?

 #### Create a character!
  - Now use these shapes and commands to create a character
  - Be creative!


 ## Activity 2: Learn about basic Programming concepts
 ### Variables
 We will go through the basic concept of variables. We cover two types of variables
 - Integer variables
 - Colour variables

 The word **integer** means a whole number.
 To declare and use an integer variable, try the following code:
 - `int eyeDiameter = 30;`
 - `ellipse(50,50, eyeDiameter, eyeDiameter;`


 To declare and use a colour variable, try the following code:
 - `color awesomePink = color(249, 206, 215);`
 - `fill(awesomePink);`
 - Note: the spelling to use is the American spelling `color`
 - Remember that to see this colour, we need to follow this code with something to apply the colour to!

 Variables names are very important. Well-named variables make code easier to read and understand, while poorly named variables can have the opposite effect. If you take care to name your variables well, you will make it easier for yourself to update your code at a later date. Remeber, it might not always be you who has to update the code!
 
 Try to make the names of your variables meaningful. It is better to have a longer more meaningful name like `pink` than an abbreviation like `p` that you might forget the meaning of later.

 #### Practise!
 - Create some variables to replace some values in your code
 - Use both colours and integers
 - Try to name your variables so that their purpose is clear
 - **CHALLENGE**: Can you create a variable that allows you to easily change if your characteer's eyes look up or down?

 ### Adding interactivity
 To get your code to move, start by setting up two sections
 - void setup() { }
 - void draw() { }

 The `setup()` section runs noly once and the beginning.
 The `draw()` section runs repeatedly in a loop and is the place your code to be animated will go.

 #### Using mouse data
 - Processing gives you a way of using data from the mouse to update your sketch
 - You can use the current x and y position of the cursor using `mouseX` and `mouseY`
 - In the `draw()` section, we can replace integer values with `mouseX` or `mouseY` 
 - Every time the mouse moves, this section will be redrawn

 ### Try it out!
 - Put your code into two sections
 - Replace one or two variables with mouseX or mouseY
 - What happens?
 - **CHALLENGE!**: Can you get your character's eyes to follow                 the mouse movements?


 ## Wrap Up

 - In this workshop, we covered the basics of how to create shapes and sketches using the Processing language.
 - We learnt the introductory coding concept of variables, how they are declared, what a variable type is and how we can use variables to help us to code. We also learned the importance of naming variables to make code clearer.
 - We learnt how to use data from the mouse to update our sketches, and how this allows us to enhance our sketches through animation.

 ## What's Next?

- Further reading and things to do for attendees: 
    - There is a lot of information available online about Processing at
        -  https://processing.org/
    - You can download Processing on your own computer at home from https://processing.org/download/
    - If you are inspired by or enjoy learning from videos, go to http://www.youtube.com and search for 'Processing artwork' to find examples of sketches others have created
    - If you learn best from examples try the Processing tutorials and examples at
        - https://processing.org/tutorials/
        - https://processing.org/examples/
