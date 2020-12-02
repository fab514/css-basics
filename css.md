# Things you can do using CSS

- CSS has been adopted by all major browsers and allows you to control:
    color
    fonts
    positioning
    spacing
    sizing
    decorations
    transitions

# Using an external Css sheet.
- <link rel="stylesheet" href="./color-style.css">

# CSS Block
- you can use a block. red-text will be the name assigned. When putting that name in a section of the document it will be red. You can have multiple elements in a block. 
<style>
    .red-text {
        color: red;
        font-size: 30px;
    }
<h2 class="red-text">Cat text</h2>   

</style>

# Fonts
## Font Family - When wanting to change the font of text type in font-family: Verdana "sans serif" 
 - You can upload a font from google font library by grabbing the link the site and putting it above the style element. 
 - When putting in font some fonts may not work on some browsers. Better to have fallback fonts. If a fallback font is not specified css would automatically fallback on a generic text. 
 # Image
 - when putting in an image use <img src="file" alt="file name"/> An image does no have a closing tag.
 - adding a class to style element can let you use the set class more then once. .smaller-image {
     width: 200px;
     height :100px;
 }
 - Border have multiple properties including style, color and width. When using multiple classes put in the following class= "class1 class2" 
 .thick-purple-border {
     border-color: purple;
     border-width: thick;
     border-style: solid;
     border-radius: 10 px;
 }
 - A border width can be altered using pixels. border-width: 10px. A border can be given rounded corners using border-radius: 10px. Using border-radius: 50% will give you an almost circular border. 
## ID attributes
- id attributes should be unique
- Benefits for id attributes, to style a single element and can later modify specific elements in Javascript. 
## Adjust Padding
- Control space for HTML elements include padding, border and margin
- Padding controls the amount of space between elements content and border. 
- An elements margin controls the amount of space between the elements border and surrounding elements. You can use a negative value of margin to make the element bigger. 
- You can change padding on each side of the element padding-top padding-right padding-bottom padding-left. You can also use a clockwise motion instead of listing all. padding 50px 40px 50px 40px
- Change margins on different sides using margin-top margin-right margin-bottom margin-left.
