# CSS
- Cascading Stylesheets, Stylesheet/styling language
- Not a programming language
- Used for website layout and design
- Can be extended with Sass/Less (Do I need to know this?)
## Ways to add CSS to your HTML
- Inline CSS: Directly to HTML Element Remember inline adds to one line.  (Don't use this one.)
- Internal CSS: Using the <style> tags within a single document. Used within the head of the document. You cannot reuse CSS if you use this method. 
- External CSS: Linking an external .css file. This is most commonly used so you can reuse your CSS code for a different HTML file. 
## Selectors
- You can use the element name as the selector to your style tag. example below is Internal CSS.

```CS

<style type="text/css">
{h1
    color:red;
}
```
- Alternatate to using the element name as the selector you can use a class or id. If you would like all elements to have the same CSS you can use your element name as the selector. If you want a specific element it is better to use a class or id. 
## Colors- There are a couple ways you can show colors
- Color Names
- HTML5 Color Names (Color suggestions will auto appear)
- Hexadecimal (uses 6 colors numbers using characters 0-F you can shorten to 3 characters.)
- RGB (uses 3 color numbers using numbers 0-255 to alter color.)

```CS
body {
    background-color: blanchedalmond;
}
h1 {
    color: #00ff00;
}
p {
    color: rgb(0,0,255);
}
```
## Text Font
- Web Safe Fonts are font that can be used for most programs. 
- Google Font Library you would need to put the link of that font on top of your HTML file. 
- In case a certain font is not supported on a browser it is best to list a few backup fonts. Times New Roman is the default font if you do not specify one. 

```cs
font-family: Arial, Helvetica, sans-serif;
```
## Font Size
- Font size is the size of the font in pixels (px). The default size is 16px you can change the font size to be bigger or smaller then the 16px.
## Font-weight
- The font weight is used to change the boldness. (Reminder better to use this for bold instead of using HTML). Bold, normal or using a number can change the boldness. 
```cs
font-size:16px;
font-weight:bold;
```
- You can use a shortcut for some of these elements. 

```cs
font: normal Arial, Helvetica, sans-serif;
``` 
## Line Height
- Line height is the distace from each line in the text. You use em units for line height in websites. 
```cs
line-height:1.6em;
```
## Class vs. ID
- Class is used when you plan on using the css element more then once (such as adjusting color, size etc). Reuse classes. When targeting a class in HTML use the period and the class name. .box-1
- For classes you can grab a child element within the parent class. Below we are looking to grab the <h1> child element within the parent class .box-1.
```cs
.box-1 h1{
    font-family:Tahoma;
}
```
- An id is meant to be more unique then class. This would be if you planning on using it the one time. (Such as using the id with nav.) When targeting an ID in the HTML use a hashtag with the ID name. #exampleid
## Width
- Width will change the margin of the element using pixels. When using pixels the width will remain the same no matter the size of the window. Use percentage to have the width alter along with the page window. 
## Margin
- Margin is the amount of space between the outside of the document and the border. Using auto will have equal margin between each side of the element. This will bring the container to the middle of the page. 
```cs
.container{
    
    width:80%;
    margin:auto;
    // width:500px;
}
```
## Box Model
- Each section of the box model is organized with top, right, bottom, left.  
- Top Margin- Is the space between the outside of the document and the border. 
- Border- Is the border of the element. 
- Padding- Is the space between the content and the border. 
- Content- Is each element on your page. 
## Margin and padding shorthand
- Margin is on the outside of the the elements border. 
```cs
p{
    margin-top:5px;
    margin-right:10px;
    margin-bottom:5px;
    margin-left:10px;
}
p{
    // short hand in clockwise order top, right, bottom, left.
    margin: 5px 10px 5px 10px;
}
p{
    // Smallest shorthand this will be used if your top/bottom (first number)and right/left(second number) is the same. 
    margin: 5px 10px;
}
```
## Borders
- Borders can have their margin, color and weight changed. 
- Borders options is solid, dotted, double. Using border-top-style.
- Borders can be shorthand as well. If you would like to have the borders the same on all sides. Instead of putting border-right etc. put border.
```cs
border-right:5px red solid;
border:5px red solid;
```
