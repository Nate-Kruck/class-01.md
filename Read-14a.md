# What Google Learned From Its Quest to Build the Perfect Team

1. People in teams tend to achieve better results and report higher job satisfaction. Project Artistotle's research team started to evalutate teams, from gender, time spent together, education, literally every aspect of a persons life. Yet they could never find patterns and studeied over 100 groups in a year. Good teams have members that speak in the same proportion but if it is just one person talking the whold time the collective intelligence declined.

## CSS Transforms

1. Transform syntax - include transform property followed by the value with ()

1. 2D Transforms
    * can be distorted or transformed with transform: rotate(20deg)
    * applied the rotate demo to my adventure game characters
    * skew images
    * create 2D cube images
    * transform origin can move images across the axis

1. 3D Transforms
    * 3D rotate with (perspective elements and rotate(X,Y,Z))
    * skey 3D images
    * transform and add shadow behind image

## Transitions & Animations

1. Transitions
    * element must have change in state for transition to take place
    * four properties(psuedo classes)
        1. :hover
        1. :focus
        1. :active
        1. :target
    * transition-property will determine what properties will be alerted in conjunction with the other transitional properties.
    * transition-duration can be set using time values including seconds and milliseconds
    * transition-timing-function property can be used to set the speed in which the transition will move, each property is followed by (cubic-bezier curve(x1, y1, x2, y2))

## 8 Simple CSS transitions
    * Fade in - good to draw attention to call to action (.fade:hover)
    * Change color - (.color:hover)
    * Grow and Shrink - (.grow:hover using -webkit-transform, -ms-transform and transform in style block)
    * Rotate - using (.rotae:hover)  
    -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
    * Square to Circle - (.circle:hover using border-radius in sytle block)
    * 3D Shadow - (.threed:hover using box-shadow, -webkit-transform and transform in style block)
    * Swing - highly complex and uses @keyframes with -webkit-transform and transform in style block
    * Insert Border - creates box shadow when being hovered over (.border:hover using box-shadow in style block)

## 6 Buttons Animated
    * an example animation code is given on codepen and it creates a cool effect where the buttons are slowly bouncing up and down. Uses a mixture of all the transitions and transformations I read before this.

## CSS3 Keyframes
    * this animation uses quite a bit of the -web-kits in the style block. It is a simple animation that sends a red ball bouncing up and down till it comes to a halt. 

## 404 Animation
    * This was a really cool animation as it rotated the 4 and 4 in and out of the center of the 0 to create 404. Definitely want to apply this to one of my projects coming up.

## Pure CSS Bounce
    * This animation starts out as a single white ball and drops then turns into a larger maroon circle then eventually a little square and disappears from the frame. They use keyframes, ball transform, ballbounce scalemask and webkit elements within the style block.