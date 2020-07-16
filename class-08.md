# Web Reading - Local Storage
## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

1. HTML5 Storage
    
    * Uses named key/value pairs
    * Calling setItem() with a named key that exists will overwrite the previous value.
    * Calling getItem() with a non-existent key will return 'null' rather than throw an exception
    * You can treat the localStorage object as an "array" by using the square brackets.
        * the example given in the reading is as follows -
            * var foo = localStorage.getItem("bar");  
                //...  
                localStorage.setItem("bar", foo);  
                the above example could also be rewritten using the []  
                var foo = localStorage["bar"];  
                //...  
                localStorage["bar"] = foo;

    