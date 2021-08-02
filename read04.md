# Readings : HTML Links, JS Functions, and Intro to CSS Layout

## Chapter 4: Ch.4 “Links” (pp.74-93)

#### Writing Links
 

- Links are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute.

- The text between the opening 
<a> tag and closing </a> tag 
is known as link text. Where 
possible, your link text should 
explain where visitors will be 
taken if they click on it.

## Linking to Other Pages on the Same Site

If all the pages of the site are in 
the same folder, then the value 
of the href attribute is just the 
name of the file.


### Directory Structure

- The top-level folder is known 
as the root folder.  The root folder 
contains all of the other files and 
folders for a website.


### Opening Links in a New Window

- If you want a link to open in a 
new window, you can use the 
target attribute on the opening 
<a> tag. The value of this 
attribute should be _blank_. 

### Linking to a Specific Part of Another Page

- the **href attribute** 
will contain the address for the 
page (either an absolute URL or 
a relative URL), followed by the 
# symbol, followed by the value 
of the id attribute that is used on 
the element you are linking to.



# Chapter 15: “Layout” (pp.358-404)

## Layout

1. Controlling the position of elements
2. Creating site layouts
3. Designing for different sized screen


- To indicate where a box should be positioned, you may also need to use **box offset** properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.

### Normal Flow

- in normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow, but the syntax 
would be:

- position: static; 
I have not specified a width
property for the heading 
element, so you can see how it 
stretches the width of the entire 
browser window by default.


### Relative Positioning

Relative positioning moves an 
element in relation to where it 
would have been in normal flow.
For example, you can move it 10 
pixels lower than it would have 
been in normal flow or 20% to 
the right. 



### CLEARING FLOATs

It can take 
the following values:

- left
The left-hand side of the box 
should not touch any other 
elements appearing in the same 
containing element.
- right
The right-hand side of the 
box will not touch elements 
appearing in the same containing 
element.
- both
Neither the left nor right-hand 
sides of the box will touch 
elements appearing in the same 
containing element.
- none
Elements can touch either side.
In this example, the fourth 
paragraph has a class called 
clear. The CSS rule for this 
class uses the clear property 
to indicate that nothing should 
touch the left-hand side of it.



### The liquid layout 

- The liquid layout uses 
percentages to specify the width 
of each box so that the design 
will stretch to fit the size of the 
screen.
- When trying this in your 
browser, remember to make the 
window smaller and larger.
A Liquid Layout

### Layout Grids

Composition in any visual art (such as design, painting, or photography) 
is the placement or arrangement of visual elements — how they are 
organized on a page. Many designers use a grid structure to help them 
position items on a page, and the same is true for web designers.




