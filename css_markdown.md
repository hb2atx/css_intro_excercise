What is a CSS selector? Please give an example.
In CSS, selectors are patterns used to select the element(s) you want to style.

What is a CSS Declaration? Please give an example.
The declaration block contains one or more declarations separated by semicolons.
Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

What is a CSS Property? Please give an example.
A CSS property assign a style or behavior to an HTML element.

Examples include: color, border, margin, font-style, and transform.

What is a CSS Value? Please give an example.
Every CSS declaration includes a property / value pair. Depending on the property, the value can include a single integer or keyword, to a series of keywords and values with or without units. There are a common set of data types — values and units — that CSS properties accept. Below is an overview of most of these data types. Refer to the page for each value type for more detailed information.

What are the three ways to include CSS?
External CSS
Internal CSS
Inline CSS

What is the difference bettwen rgb and rgba?
RGB Color Scheme: It is a three-channel format containing data for red, green, and blue colors. In CSS, the RGB color format can be specified using:

Each parameter in rgb() function defines the intensity of colors in a range of 0 to 255. The value 0 defines no color of that type being used while 255 defines the highest value of that color being used.

RGBA Color Scheme: The RGBA color format is an extension of the RGB scheme with an added alpha channel that specifies the opacity of the color. In CSS, the RGBA color format can be specified using:

What is an em?
Relative to the font-size of the element (2em means 2 times the size of the current font)

What are the differences between em and rem?
 em Unit: The em unit allows setting the font size of an element relative to the font size of its parent. When the size of the parent element changes, the size of the child changes automatically.
rem Unit: The rem is based upon the font-size value of the root element, which is the <html> element. And if the <html> element doesn’t have a specified font-size, the browser default value of 16px is used. So here only the value of the root is considered, and there is no relation with a parent element.

How do you include a google font?
<head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
<style>
body {
  font-family: "Sofia", sans-serif;
}
</style>
</head>