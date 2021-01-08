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




