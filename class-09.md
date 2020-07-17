# Readings for class 09 (Read 09)

## Chapter 7: Forms

1. Why Forms?

    * Best known form on the web: Google's search box  

    1. Adding Text:  
        * Text-input
        * Password-input
        * Text-area

    1. Making Choices:
        * Radio buttons
        * Checkboxes
        * Drop-down boxes

    1. Submitting Forms:
        * Submit buttons
        * Image buttons

    1. Uploading Files:
        * File upload

1. How do these forms work?

    * A user fills out a form then clicks a button to submit the info to the server.

    * Forms may have many different form controls and they each gather different information.

1. Form Structure

    * Form controls live within the form element.

        * action - value is the URL for the page on the server that will receive the information in the formwhen it is submitted.

        * method - get/post

            * get - values from the form are added to the end of the URL specified in the action attribute.

            * post - values are sent in HTTP headers
                * post is used when the form allows users to upload a file, the form is very long, the form contains sensitive data(passwords) and if the form adds info to, or deletes it from a database.

1. Grouping Form Elements

    * <'fieldset'> - group related controls together

        * <'legend'> - child element to <'fieldset'> that contains a caption that helps identify the purpose of that group of form controls.

## Chapter 14: Lists, Tables, and Forms

* Bullet point styles

    * list-style-type: allows you to control the shape or style of a bullet point(marker)

* Images for bullets

    * list-style-image: you can specify an image to act as a bullet point(make page stylish)

    ## !LIST SHORTHAND --> (list-style:) allows you to express the markers, style, image and position properties in any order. (helps to keep code clean and organized)

1. Styling Forms

    1. Most common to style:

        * text-inputs and text-areas
        * submit buttons
        * labels on forms, to get the form controls to align nicely

1. Cursor Styles

    * cursor:

        * auto, crosshair, default, pointer, move, text, wait, help, url("cursor.gif")

## ! only use these values to add helpful info for users in places they would expect to see that cursor

## Chapter 6: Events (JavaScript)

1. Different Event Types

    * a list is displayed on page 246 that has a selection of events that occur in the browser while you are browsing the web. Any event can be used to trigger a function in JS code.

1. Terminology

    * fired/raised: when an event has occured
    * trigger: when the click event fires it 'triggers' a function 

1. Event Handling

    1. select the element
    1. indicate which event on selected node will trigger response
    1. state the code you want to run when event occurs

1. Three ways to bind event to an element

    1. HTML event handlers (page 251)
    1. Traditional DOM event handlers (page 252)
    1. DOM level 2 event listeners (page 254)

1. Event Flow

    * HTML elements are nested inside of other elements. If you hover or click on a link then you will also be hovering or clicking on its parent element. 
    * Flow of events only matters when code has event handlers on an element AND one of its ancestor or descendant elements.

1. Event Object

    * When an event occurs, the event object will tell you information about the event and the element it happened upon.

1. Different types of events

    * UI (user interface) - occurs as a result of interaction with a browser window
    * Load: used to trigger scripts that access the contents of the page.
    * Focus/Blur: HTML elements you can interact with - links and form elements
    * Mouse events: when mouse is moved and buttons are clicked
    * Click: self-explanatory
    * Keyboard events: when user interacts with keyboard
    * Form events: submit, change, input
    * Mutation events: when elements are added or removed from the DOM, the structure changes, this triggers a mutation event
    * HTML5 events: DOMContentLoaded, hashchange, beforeunload

1. Where do events occur?

    * the event object can tell you where the cursor was positioned when an event was triggered.