# Chapter 4 - Links
 * Links allow you to move from one page to another (surfing)

1. Writing Links
    * Links are created with the anchor(a) tag
        * example - <'a href="http://www.github.com">GitHub<'/a'>
    * Linking to different websites requires the full URL known as the absolute URL.
    * Linking to other pages within the same site is known as a relative URL.

1. Directory Structure
    * Folders = directories
    * URL - Uniform Resourse Locator - every page and every image has one.
    * Organize code for bigger sites, have good structure and be aware of the relationships between files. 

1. Relative Link Types
    * Same Folder
    * Child Folder
    * Grandchiled Folder
    * Parent Folder
    * Grandparent Folder

1. Email Links
    * mailto: will open users email program.

1. Opening links in a new Window
    * You use the target attribute with a value of _blank like so.. target="_blank"

# Chapter 15 - Layout

1. Building Blocks
    * CSS treats the HTML element like its in its own box
    * If one block element sits inside another this is known as the containing element or (parent)

1. Positioning schemes
    * Normal flow - paragraphs appear one after another
        * position:static
    * Relative Positioning - second paragraph is pushed down
        * position:relative
    * Absolute Positioining - Heading is positioned to the top right and 
    paragraphs start at top of screen
        * position:absolute
    * Fixed Positioning 
        * position:fixed
    * Floating Elements
        * float
            * Can also be used to place elements side-by-side
            * Can be cleared with the 'clear' property and take the values (left, right, both, none)
            * Overflow property helps to offset and problems that arrise from the parents of floated elements.
            * Create multi-column with (width, float, margin)
                * 3 column layout can be created by floating 3 div elements.

1. Screen Sizes/Resolution
    * Be aware of what size your users will be using
        * Designers try to create pages around 960-1000px

1. Fixed width/Liquid Layouts
    * Fixed - does not change if user expands or contracts.
    * Liquid - stretch and contract to with the user increasing or decreasing windon

# Chapter 3 - Functions Methods and Objects
* Functions let you group statements to perform a task

1. Declaring functions
    * function sayHello() {
        document.write('Hello!');
    }

1. Calling functions
    * sayHello();
    * give parameters to functions that need information
        * example : function getArea(width, height) {
            return width * height;
        }
        * calling that function like so -> getArea(3,5);
    * Functions can return one or more values using an array
    * Function declaration creates a function that you can call to your code at a later time.

1. Variable Scope - which parts of the program you can see. Once defined every part of your program can access a variable. 

# Reasons to Pair Program

1. Need a driver and a navigator.
    * Driver is typing
    * Navigator uses words to guide driver

1. Greater efficiency.
    * Easier to catch mistakes when two people are working on the code

1. Engaged
    * Helps to be more focused than working alone

1. Learning from fellow students
    * People have different skill sets so you can learn new ways to approach code by pair programming

1. Social Skills
    * You have to communicate which will help you to have long-term career impacts.

1. Work environment readiness
    * You'll have to pair program when you land a job as a fresh hire and if you are already familiar with the process then the transition will be much easier. 
    