# CSS Layout

## Chapter 15: Layout


### NORMAL FLOW, position:static

- In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position: static;

- Relative Positioning, position:relative
Relative positioning moves an element in relation to where it would have been in normal flow. 

- You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow. 

- Absolute Positioning, position:absolute
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 


- Fixed Positioning, position:fixed
Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. 

- Overlapping Elements, z-index
When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page.



- The z-index is sometimes referred to as the stacking context (as if the blocks have been stacked on top of each other on a z axis). If you are familiar with desktop publishing packages, it is the equivalent of using the 'bring to front' and 'send to back' features.

### Floating Elements: float
**The float property** allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. 

### Clearing Floats: clear
- The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

1. left
The left-hand side of the box should not touch any other elements appearing in the same containing element.
2. right
The right-hand side of the box will not touch elements appearing in the same containing element.
3. both
Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
4. none
Elements can touch either side.



#### Creating Multi-Column Layouts with Floats
Many web pages use multiple columns in their design. The following three CSS properties are used to position the columns next to each other: width This sets the width of the columns. 

- Screen Sizes
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

- Screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

- Page Sizes
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

- Fixed Width Layouts
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

- Liquid Layouts
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.



## CSS Frameworks
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

Multiple Style Sheets:
1. @import
There are two ways to add multiple style sheets to a page:
 - Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.
 - In the HTML you can use a separate <'link> element for each style sheet.

2. link On this page you can see the other technique for including multiple style sheets. Inside the <'head> element is a separate <'link> element for each style sheet. 