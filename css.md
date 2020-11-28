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
 }