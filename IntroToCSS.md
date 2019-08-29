# Intro to CSS

CSS allows to create rules that control how website components are presented. 

CSS consists of a selector and a declaration. Each declaration has a property and a value. CSS declaration is placed inside { } and ends with ;

For example: h1 {font-family: Arial;}

CSS can be placed inside html code, but the prefered method is to place CSS code in a separate file. This allows for a better control of the code.

All selectors are case sensitive. Here are some of the inheritance rules:

`universal selector` *{} applies to all elements on the page

`type selector`  h1, h2 {} targets specifically listed elements

`class selector` .note{}  targets only the elements with the value of the listed class

`id selector` #id{} targets id attributes

`child selector` li>a {} targets any \<a> element which is a child of \<li>.


All elements of CSS cascade down. For example, all properties of \<body> will apply to child elements.

# Color

There are 3 ways to specify colors in CSS: RGB values (Ex: rgb(102, 205,170)), hex codes (EX: #66cdaa), and color names (Ex: MediumAquaMarine). Without any specifications, it's transparent.

## Opacity

The value of opacity is between o and 1. There are several ways to specify opacity:

- opacity: 0.6;
- rgba (0,0,0,0.6)

## Hue, Saturation, Lightness

hsla will allow you to express all 3 elements + alpha.

ex: background color: hsla (0,100%, 100%,0)


