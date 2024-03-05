# EtchSketch
Etch-a-Sketch Project in 'TOP' foundations 

This is a project within 'The Odin Project' foundations course.  The idea is to
build something between a sketchpad and an Etch-A-Sketch using the basic HTML, CSS
and introductory Javascript DOM manipulation skills learned thus far.

Instructions:
    Create a 16 x 16 grid of square divs using JS.
    Create a container div to contain the grid (in html)
    Use flexbox to make the divs appear as a grid ( versus one on each line)
    Link CSS Stylesheet
    Use Browser developer tools to debug
    Check console for errors
    Check elements pane to see if the elements are being created via the DOM

    Create a "hover" effect so the dics change color when mouse over 
        (Use event listeners for mouse enter and mouse leave div)
    Techniques for changing div color include:
        Adding a new class to the div 
        Change the divs bg color using JS

    Add a button to the top of the screen that will alert the user asking for the 
    number of squares per side of the new grid.  The existing grid should be removed
    and a new grid should be generated in the same space the previous grid occupied.
    Set the limit for the user input to a maximum of 100.
    Research button tags in HTML and how can you can make a JS function run when one 
    is clicked.
    Research prompts as well
    You should be able to enter 64 and have a brand new 64 x 64 gird pop without 
    changing the total amount of pixels used.

    Extra Credit:
    Transform the behavior of the square when interacting with the mouse by 
    introducing a series of mods.
    Rather than squares being the same color, randomize the RGB values with each
    interaction.
    Implement a progressive darkening effect where each interaction adds 10% more
    black or color to the square.

    Psuedocode:
    Create a container to hold the grid
    Create the grid inside with JS
    Create a function to change the properties of each grid box when the mouse enters
    or exits
    Create a button asking for an input asking for the number of squares in the grid
    Clear and Modify the grid with users input
    input example 100 => creates 100 x 100 grid