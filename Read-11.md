# HTML/CSS Images

1. Controlling sizes of Images
    * Width and heigth properties in CSS 
    * If you are consistent when specifying the width and height properties then you can use CSS to control the size rather than using HTML
    * Use small, medium or large names when adding on to the class attribute

1. Aligning Images in CSS
    * Float is good for aligning images
        * align-left
        * align-right
        * margin is used to keep space between the image and the text

1. Centering Images
    * Images are inline by default
    * Need to be turned into **block-level** elements
    * **text-align** can then be used to center the image

1. Background Images
    * path follows url inside parentheses and quotes
    * background-image: url("")

1. Repeating Images
    * background-repeat - repeat, repeat-x, repeat-y, no-repeat
    * background-attachment - fixed, scroll

1. Background Position
    * place image top, bottom, left, right, and center
    * use a pair of pixels or percentages

1. Rollover and Sprites
    * change link or button that changes to a different style when user moves their mouse over the element or clicks on it
    * using sprite is when a single image is used for different parts of the interface, this can help a website to load faster
    * use anchor tag (inline-block in CSS)

1. Contrast (background images)
    * contrast needs to be low in order for text to be legible.

## Practical Information

1. SEO
    * getting site to the top of the search list by using key words that you think users will enter into a search engine, and use the key words in the site.

1. On-Page SEO
    * seven key places where keywords can appear in order to improve findability
        1. Page title (title element that lives in head element)
        1. URL/web address (use keywords in the file name)
        1. Headings (hn element)
        1. Text (repeat keywords in body atleast 2 or 3 times)
        1. Link text (use keywords in text that create links)
        1. Image alt text
        1. Page descriptions (lives in head element, specified using a meta tag, should be sentence that describes content of page)

1. Identifying Keywords
    * Brainstorm - write them down and ask other people
    * Organize - group keywords into lists
    * Research - wordtracker.com is a site that will suggest additional keywords
    * Compare - use Googles advance search feature
    * Refine - pick the keywords you want to focus on
    * Map - pick 3-5 keywords or phrases that map to each page of the site

*google analytics to analyize the users that come to your site*

## MDN video/audio

1. use video/audio elements to embed video and audio into web pages
    * wrap player in div so it can be styled as one unit

    CSS Example :  
    
    .controls {  
  visibility: hidden;  
  opacity: 0.5;  
  width: 400px;  
  border-radius: 10px;  
  position: absolute;  
  bottom: 20px;  
  left: 50%;  
  margin-left: -200px;  
  background-color: black;  
  box-shadow: 3px 3px 5px black;  
  transition: 1s all;  
  display: flex;  
}

    .player:hover .controls, player:focus .controls {
  opacity: 1;
}

    * you can also style button icons in CSS (button:before) used to display content before each button
    * then remove default browser controls with JavaScript


## Flash, Video and Audio

1. Used to create animations and play audio/video
    * flash is on its way out but is good information to know.
    * being replaced by:
        * video sharing sites(youTube)
        * JavaScript