# Chart.JS Reading (tutorial for setting up charts in JS)

1. Chart.js
    * JavaScript plugin that uses HTML5 canvas element to draw the graph onto the page. 

1. Setup
    1. download chart.js
    1. copy chart.min.js out of unzipped folder and into directory you are working with

1. Chart Types
    * Line Chart
    * Pie Chart
    * Bar Chart


## Canvas API

1. Canvas Element
    * only has two attributes: height, width

1. Not like the image tag
    * the canvas element requires a closing tag

1. Canvas grid (coordinate space)
    * 1 unit of the grig corresponds to 1 pixel on the canvas

1. Drawing Rectangles
    * fillRect - draws a filled rectangle
    * strokeRect - draws a rectangular outline
    * clearRect - clears the specified rectangular area, making it fully transparent

1. Drawing Paths
    * A path is a list of points that connects segments of lines that can be different shapes. 
        * functions used to create a path: beginPath(), Path Methods, closePath(), stroke(), fill()

1. Colors
    * fillStyle = color => sets the style used when filling shapes
    * strokeStyle = color => sets the style for shapes' outlines

1. Transparency
    * globalAlpha = transparencyValue => must be between 0.0 to 1.0

1. Line Styles
    * lineWidth = value => sets the width of lines drawn in the future
    * lineCap = type => sets the appearance of the ends of lines
    * lineJoin = type => sets the apperance of the "corners" where lines meet
    * miterLimit = value => establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes
    * getLineDash() => returns the current line dash pattern array containing an even number of non-negative numbers

1. Drawing Text
    * fillText(text, x, y [, maxWidth]) => fills a given text at the given (x,y) position. Optionally with a maximum width to draw
    * strokeText(text, x, y [, maxWidth]) => strokes a given text at the given (x,y) position. Optionally with a maximum width to draw

1. Styling Text
    * font = value
    * textAlign = value
    * textBaseline = value
    * direction = valuex