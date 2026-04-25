# Grouping Selectors
The CSS Universal Selector

The universal selector (*) selects all HTML elements on the page.

Example: The CSS rule below will affect every HTML element on page

* {
    text-algin: center;
    color: blue;
}

The CSS Grouping Selector 

The grouping selector selects all the HTML elements with the same style definitions. 

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

h1{
    text-align: center
    color: red;
}

h2{
    text-align: center;
    color: red;
} 

p{
    text-align: center;
    color: red;
}

It will be better to group the selectors, to minimize the code.

To group selectors, separate each selector with a comma. 

Example: In this example we have grouped the selectors from the code above: 
h1, h2, p{
    text-align: center;
    color: red;
}

All CSS Simple Selectors 

Selector                Example         Example description

#id                     #firtname       Selects the element with id="firstname"
.class                  .into           Selects all elements with class = "intro"
*                       *               Selects all elements
element                 p               Selects all <p>
element,element,...     div, p          Selects all <div> elements and all <p> elements


NEXT> [[CSS Selectors Code Challenge]]