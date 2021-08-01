# Chapter 5: “Images” (pp.94-125)


## Choosing Images for your Site

A picture can say a thousand words, and great 
images help make the difference between an 
average-looking site and a really engaging one

**Storing Images on Your Site**

- If you are building a site from scratch, it is good 
practice to create a folder for all of the images 
the site uses.

### Adding Images


1. <img> 

- src
This tells the browser where 
it can find the image file. This 
will usually be a relative URL 
pointing to an image on your 
own site. (Here you can see that 
the images are in a child folder 
called images — relative URLs 
were covered on pages 83-84). 


- alt
This provides a text description 
of the image which describes the 
image if you cannot see it.


- title
You can also use the title
attribute with the <img> element 
to provide additional information 
about the image. Most browsers 
will display the content of this 
attribute in a tootip when the 
user hovers over the image.


#### Where to Place Images in Your Code

1. before a paragraph
The paragraph starts on a new 
line after the image.

2. inside the start of a 
paragraph
The first row of text aligns with 
the bottom of the image.

3. in the middle of a 
paragraph
The image is placed between the 
words of the paragraph that it 
appears in.


#### Old Code: Aligning Images Vertically

As _you saw on the last page_, the 
align attribute is no longer used 
in HTML5, but it is covered here 
because you may see it used in 
older websites and it is still used 
in the code created by some 
visual editors.



#### Tools to Edit & Save Images

- The most popular tool amongst 
web professionals is Adobe 
Photoshop. (In fact, professional 
web designers often use this 
software to design entire sites.) 
The full version of Photoshop is 
expensive, but there is a cheaper 
version called Photoshop 
Elements which would suit the 
needs of most beginners.

**Transparency**

Creating an image that is partially transparent 
(or "see-through") for the web involves 
selecting one of two formats:

1. Transparent GIF
If the transparent part of the 
image has straight edges and 
it is 100% transparent (that is, 
not semi-opaque), you can save 
the image as a GIF (with the 
transparency option selected)

2. PNG
If the transparent part of the 
image has diagonal or rounded 
edges or if you want a semiopaque transparency or a dropshadow, then you will need to 
save it as a PNG.



# Chapter 11: “Color” (pp.246-263)


## Foreground Color


The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:


1. rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)

2. hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80

3. color names
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan.


### Contrast

- When picking foreground and background 
colors, it is important to ensure that there is 
enough contrast for the text to be legible.


# Chapter 12: “Text” (pp.264-299)

## Specifying Typefaces
font-family

- The _font-family_ property 
allows you to specify the 
typeface that should be used for 
any text inside the element(s) to 
which a CSS rule applies.
The value of this property is the 
name of the typeface you want 
to use. 

### Letter & Word Spacing
letter-spacing, word-spacing 

- Kerning is the term 
typographers use for the space 
between each letter. You can 
control the space between each 
letter with the letter-spacing
property.



### Vertical Alignment
vertical-align

- It is more commonly used with 
inline elements such as <img>, 
<em>, or <strong> elements





###

Responding to Users
:hover, :active, :focus

1. hover
This is applied when a user 
hovers over an element with a 
pointing device such as a mouse. 
This has commonly been used 
to change the appearance of 
links and buttons when a user 
places their cursor over them. 


2. active
This is applied when an element 
is being activated by a user; for 
example, when a button is being 
pressed or a link being clicked. 



3. focus
This is applied when an element 
has focus. Any element that 
you can interact with, such as a 
link you can click on or any form 
control can have focus.




