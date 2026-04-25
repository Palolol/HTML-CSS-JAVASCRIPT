# Multiple Style Sheets

Multiple Style Sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

Assume that an external style sheet has the following style for the <h1> element:

h1 {
color: navy;
}

Then, assume that an internal style sheet also has the following

h1 {
color: orange
}

Example:
if the internal style is defined after the link to the external style sheet, the <h1> elements will be "orange":

<head>
<link rel="stylesheet" type="text/css" href ="mystyle.css">
<style> 
h1 {
    ccolor: orange;
}
</style>
</head>

Example:
However, if the internal style is defined before the link to the external style sheet, the <h1> elements will be "navy":

<head>
<style> 
h1 {
    color: orange;
}

# Cascading Ordder

What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by following rules, where number one has the highest priority.

    1. Inline style (inside an HTML element)
    2. External and internal style sheets(in the head section)
    3. Browser default

So, an inline style has the highest priority, and will override external and internal styles and browswer defualts.

NEXT> [[Code Challenge]]
