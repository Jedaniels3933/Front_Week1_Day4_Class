#  CSS Styling Language- not a programming language- aids code 

##  Use selectors 

3 ways to add css to a page
1. inline - not recommended  located in the -head-
2. Internal- inside the page - not recommended   located in -head-
3. External- best 
 
### CSS Syntax

1.Selectors
2.Properties
3. Values   
'''
selector{
    property1:value
    propertry2:value
}
'''

### CSS Selector

##Descendant combinator
Example
```
<!DOCTYPE html>
<html>
<head>
<style>
div p {
  background-color: yellow;
}
</style>
</head>
<body>

<h2>Descendant Selector</h2>

<p>The descendant selector matches all elements that are descendants of a specified element.</p>

<div>
  <p>Paragraph 1 in the div.</p>
  <p>Paragraph 2 in the div.</p>
  <section><p>Paragraph 3 in the div.</p></section>
</div>

<p>Paragraph 4. Not in a div.</p>
<p>Paragraph 5. Not in a div.</p>

</body>
</html>
```
- child classes are indented 
PLus selector is + Sibling class
example div + p 

General sibling selector

div ~ p {
    background-color:red;
}

Child is a descendant 

Element Selectors are under class and Id 

# Colors 
hex codes  color : OOOOff = red
background-color: rgb(255,10, 5)

# FONTS
{font family }

PX or relative lengths 

Font size - em example 
rem best and vw = size of screen


For padding and box see the CSS box model to see what you can alter 
padding is the amount of white space by default around the inside of the border
