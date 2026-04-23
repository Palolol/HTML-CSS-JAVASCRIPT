# CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to syle.

We can divide CSS selectors into five categories.

Simple Selectors (select elements based on name, id, class)
[[Combinatorselectors]] (select elements based on a specific relationship between them)
[[Pseudo-class selectors]] (select elements based on a certain state)
[[Pseudo-elements selectors]] (select and style a part of an element)
[[Attribute selectors]] (select elements based on an attribute or attribute value)

This page will explain the most basic CSS selectors.

Example
Here, all <p> elements on the page will be the center-align, with a red text color::after
p {
text-align: center;
color: red;
}

The CSS id Selector

The [[id]] selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unigue within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of element.

Example:
The CSS rule below will be applied to the HTML element with id = "para1":

#para1 {
text-align: center;
color: red;
}

Note: An id name cannot start with a number!

The CSS class Selector

The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period(.) character, followed by the class name

Example In this example all HTML elements with class = "center" will be red and center=aligned:

.center {
text-align: center;
color: red;
}

You can also specify that only specific HTML elements should be affected by a class.

Example: In this example only <p> elements with class ="center" will be red and center-aligned::after

p.center{
text-align: center;
color: red
}

HTML elements can also refer to more than one class.

Example: In this example the <p> element wil be styled according to class="center" and to class ="large":

<p class="center large"> This paragraph refers to two classes.</p>

Note again: A class name cannot start with a number.

NEXT> [[Grouping Selectors]]
