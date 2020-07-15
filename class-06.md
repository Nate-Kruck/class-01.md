# Understanding the problem domain is the hardest part of programming

1. Writing code is like putting together a jigsaw puzzle. 

    * problem domains will look completely different depending on your viewpoint

1. Understanding the problem domain will make programming easier. 

    * cut out cases and narrowing your focus to a particular part of the problem

# JavaScript Chapter 3 - Object Literals

* Objects group together a set of variables and functions to create a model of something you would recognize from the real world.

* Literal notation is the easies and most popular way to create objects.

    * var hotel = {
        name: 'Quay',
        rooms: 40,
        booked: 25,
        checkAvailability: function() {
            return this.rooms - this.booked;
        }
    }

# Chapter 5 - DOM

1. DOM tree is a model of a web page

1. Two steps to access/update DOM tree
    * step 1: Locate the node that represents the element you want to work with
    * step 2: Use its text content, child elements, and attributes

1. Methods that find elements in the DOM tree are called DOM queries
    * node list is a collection of nodes
    

1. Methods (search entire document to return individual elements)
    * getElementById()
    * querySelector()

1. Selecting Elements
    * using class attributes
    * tag name
    * CSS selectors

1. Looping through node list
    * use loops if you want to apply the same code to numerous elements

1. Traversing the DOM
    * parentNode
    * previousSibling
    * nextSibling
    * firstChild
    * lastChild

1. Adding or removing HTML Content
    * There are two very different approaches to adding and removing content from a DOM tree: the innerHTML property and DOM manipulation.

    * using the innerHTML property, you can access and amend the contents of an element, including any child elements

1. DOM manipulation (3 steps)

    1. createElement()
    1. createTextNode()
    1. appendChild()



