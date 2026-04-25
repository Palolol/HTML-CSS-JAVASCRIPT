How to Add CSS

When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.

There are three ways of inserting a style sheet:

    1. External CSS - link to an external .css file
    2. Internal CSS - use the <style> element in the head section
    3. Inline CSS - use the style attribute on HTML elements

External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to tthe external style sheet file inside the <link> element, inside the head section.

Example:
External styles are defined within the <link> element, inside the <head> section of an HTML page:

Example : External styles are definedd within the <link> element, inside the head <head> section of an HTML page:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mystyle.css ">
</head>
<body>

</body>
</html>

An external style sheet can be written in any text editor, and must be saved with a .css extension

The external .css file should not contain any HTML tags.

Here is how the "mystyle.css" file looks:

"mystyle.css"
body{
background-color: lightblue;
}

h1 {
color: Navy;
margin-left: 20px;
}

Note: Do not add a space between the property value (20) and the unit (px):
Incorrect (space): margin-left: 20px;
Correct (no space): margin-left: 20px;

NEXT> [[Add internal CSS]]
