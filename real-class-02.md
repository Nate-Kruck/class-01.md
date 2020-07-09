# HTML Markup Chapter 2
## Adding Markup to the text

### Two types:
1. Structural Markup - (Section 1-7)
1. Semantic Markup - (Section 8-13)

## Section 1 - Headings
* HMTL has six "levels" of headings 'h1' through 'h6'

## Section 2 - Paragraphs -> show text

## Section 3 - Bold & Italic
* <'b'> <'i'> - (using single quotes since it tries to run in HTML)

## Section 4 - Superscript & Subscript
* 4<sup>th</sup>
* H<sub>2</sub>0

## Section 5 - White Space
* Adding extra spaces <br> or starting <br> on a new line helps code to be better readable.

## Section 6 - Line Breaks & Horizontal Rules
* <'br  /'> - starts a new line
* <'hr  /'> - adds line between sections
1. key note - these are empty elements which means there are no words between the opening and closing tags.

## Section 7 - Visual Editors
* Text editors
* We use visual studio code so I'm not sure this section was relevent?

# Semantic Markup
* Does not affect the structure of web page but adds extra info. 
* This is especially good for screen readers or search engines.

## Section 8 - Strong & Emphasis
* <'strong'> - strong importance
* <'em'> - subtly changes meaning

## Section 9 - Quotations
* <'blockquote'> - for long quotes
* <'q'> - short quotes

## Section 10 - Abbreviations & Acronyms 
* <'abbr title = "Proffessor">Prof<'/abbr'> converts to <abbr title = "Proffessor">Prof</abbr>

## Section 11 - Citations & Definitions 
* <'cite'>
* <'dfn'> - first time explaining new terminology

## Section 12 - Author Details
* <'address'> - contact details of author

## Section 13 - Changes to Content
* <'ins'> <ins>best</ins>
* <'del'> <del>worst</del>
* <'s'> <s>not relevant so don't delete</s>

# Chapter 10 - _Introducing Css_

1. Understanding Css
    * Imagine every HTML element is surround by invisible box
1.  Example Styles
    * Boxes - width/height
    * Text - size/color
    * Specific - lists/tables/forms
1.  Two parts to CSS rule
    * Selector 
    * Declaration - sit inside {} with a property and value
1.  External & Internal CSS
    * Link - href, type, rel
    * Style - Sits in html head
1. CSS Selectors
    * Gives a list of selectors along with their meaning and an example
1. Inheritance
    * Font-family or color specified in body{} will apply to most child elements

# JavaScript
## Chapter 2 - Basic JS Instructions

1. Statements - Set of instructions end with ;
    * code blocks are in {}
1. Write comments to better explain what code does
    * multi-line /*
    * single - line //
1. Variables - information temporarily stored in variables. (var)
1. Data Types
    * Numeric (0.15)
    * String ('Hi, Nate!')
    * Boolean (true/false)
1. Shorthand
    * Will save time when typing but can be difficult to follow
1. Six rules when naming variable
    * name must begin with letter, dollar sign or underscore
    * name can contain letters, numbers, $ or _
    * can't use keywords or reserved words
    * case sensitive 
    * use name that describes information that var stores
    * camelcase - camelCase
1. Arrays
    * use when working with list or set of values related
    * colors = ['red', 'white', 'blue'];
1. Expression
    * evalutates into a single value
        * example - var color = 'red';
1. Operators
    * = <> && + || * 
1. String Operator
    * only one (+)

# Chapter 4 - Decisions & Loops

1. Decision Making
    * use flow charts
1. Two components to decision
    * Evaluation of a condition
    * Conditional statements
1. Comparison Operators
    * ==, !=, >, <, ===, !==, >=,<=
1. Logical Operators
    * &&, ||, !
1. If Statements
    * evaluates a condition
1. If else statements
    * checks condions, if true then first block executes if false then second block is run. 