# Chapter 5: Images
1. Choosing Images

    - They should be relevant, convey the information and the right mood.
    - Do not take photos from other sites, you could get into trouble.

1. Storing Photos

    - Store images in a seperate folder.
    - Keeps you organized

1. Adding the Images

    - Use the <'img'> tag, which is an empty element, therefore it has no closing tag.
    - Requires attributes: src, alt and title

1. Height & Width

    - Specifying size can help browser to render text on the page, leaving the perfect amount of space for the image that takes longer to load.
    - CSS is primarily used for this now

1. Three Rules for Creating Images

    1. Save images in the right format (jpeg, gif or png)
    1. Save images at the right size
    1. Measure images in pixels  
    - Use adobe photoshop to edit and save photos

1. JPEG
     
    - Use jpeg when pictures contain many different colors

1. GIF

    - gif or png are used when the image has few colors or flat colors

1. Figure and Figure Caption

    - used to contain images and their captions
        - <'figure'> and <'figcaption'>

# Chapter 11: Color

1. Foreground and Background specificity

    - color is foreground
    - background-color is background
    - use rgb, hex codes or color names

1. RGB

    - rgb(102,205,170)

1. Hex codes

    - #66cdaa

1. Color names

    - MediumAquaMarine
    
1. Pick the right contrast

    - High contrast makes text easier to read
    - Medium contrast is good for long spans of text

1. Opacity (0.0 - 1.0)

    - opacity: 0.5  
    or  
    - rgba(0,0,0,0.5) 

1. HSL and HSLA

    - new ways to specify colors in CSS3 
    - starts with the letters hsl followed by individual values inside parentheses for Hue, Saturation and Lightness
    - Hue is between 0 and 360 degrees
    - Saturation is a percentage
    - Lightness is a percentage

# Chapter 12: Text

1. Formatting properly can have an effect on how readable your page is

1. Typeface Terminology

    1. Serif
    - have extra details on the ends of the main strokes of letters known as serifs

    2. Sans-serif
    - have straight ends to letters making a cleaner design
     
    3. Monospace
    - every letter is the same width

    4. Weight
    5. Style
    6. Stretched

1. Font-family 

    - lets you specify the typeface that should be used for any text inside the elements to which a CSS rule applies
    - specify more than one, incase the user does not have one of the fonts installed on their computer

1. Font-size

    - used pixels and the default is 16px

1. Type scales

    - pleasing to the eye and have changed little in the last 400 years
    - developed by European typographers in the sixteenth century

1. Font-face

    - allows you to use a font, even if the user does not have that font installed. This allows you to specify a path to a copy of that font so the users machine will download it

1. Understanding font formats

    - use fontsquirrel.com to help format fonts

1. Bold & Italic

    - font-weight
    - font-style

1. Uppercase/Lowercase

    - text-transform

1. Underline/Strike

    - text-decoration

1. Leading

    - line-height
        - increases vertical spacing between lines

1. Letter/Word Spacing

    - letter-spacing
    - word-spacing

1. Algnment

    - text-align
        -allows you to control alignment of text on a page

1. Vertical Alignment

    - vertical-align

1. Drop Shadow

    - text-shadow
        - adds drop shadow behind text

1. First Letter or Line (psuedo elements)

    - :first-letter
    - :first-line

1. Styling Links (psuedo classes)

    - :link
    - :visited

1. Responding to Users

    - :hover changes appearances of links and buttons when user places cursor over them
    - :active makes button or link actually feel like it is being pressed
    - :focus 

