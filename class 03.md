# Readings : HTML Lists, Control Flow with JS, and the CSS Box Model

## Duckett HTML book:

### Chapter 3: “Lists” (pp.62-73)

There are lots of occasions when we 
need to use lists. HTML provides us with 
three different types:

1. Ordered Lists
- <ol>
The ordered list is created with the <ol> element
- <li>
Each item in the list is placed between an opening <li> tag and a closing </li> tag. (**The listands for list item**.)

2. Unordered Lists

- <ul>
The unordered list is created with the <ul> element.
- </li>
Each item in the list is placed between an opening <li> tag and a closing </li> tag0. (***The li stands for list item***.) 

3. Definition Lists
- <dl>
The definition list is created with the <dl> element and usually 
consists of a series of terms and their definitions.
Inside the <dl> element you will usually see pairs of <dt> and 
<dd> elements.
- <dt>
This is used to contain the term being defined (the definition 
term).
- <dd>
This is used to contain the definition. Sometimes you might see a list 
where there are two terms used for the same definition or two 
different definitions for the same term.


## Example (lists)
<html>
<head>
 <title>Lists</title>
</head>
<body>
 <h1>Scrambled Eggs</h1>
 <p>Eggs are one of my favourite foods. Here is a 
 recipe for deliciously rich scrambled eggs.</p>
 <h2>Ingredients</h2>
 <ul>
 <li>2 eggs</li>
 <li>1tbs butter</li>
 <li>2tbs cream</li>
 </ul>
 <h2>Method</h2>
 <ol>
 <li>Melt butter in a frying pan over a medium 
 heat</li>
 <li>Gently mix the eggs and cream in a bowl</li>
 <li>Once butter has melted add cream and eggs</li>
 <li>Using a spatula fold the eggs from the edge of 
 the pan to the center every 20 seconds (as if 
 you are making an omelette)</li>
 <li>When the eggs are still moist remove from the 
 heat (it will continue to cook on the plate 
 until served)</li>
 </ol>
</body>
</html>


### chapter Chapter 13: “Boxes” (pp.300-329)

## Box Dimensions

By default a box is sized just big enough to hold its contents. To 
set your own _dimensions_ for a box you can use the height and 
width properties.The most popular ways to specify the size of a box are to use pixels, percentages, or ems. 



## Limiting Height

- In the same way that you might want to limit the width of a box 
on a page, you may also want o limit the height of it. This is 
achieved using the min-height and max-height properties.
The example on this page demonstrates these properties 
in action. 
- It also shows you what happens when the content of the 
box takes up more space than the size specified for the box. 



## Border Width

The border-width property is used to control the width 
of a border. The value of this property can either be given 
in pixels or using one of the following values:

- thin
- medium
- thick


_You can control the individual size of borders using four  separate properties_:

- border-top-width
- border-right-width
- border-bottom-width
- border-left-width

## Border Style

You can control the style of a border using the border-style
property. This property can take the following values:

- solid a single solid line

- dotted a series of square dots (if your border is 2px wide, then 
the dots are 2px squared with a 2px gap between each dot)

- dashed a series of short 

- double two solid lines (the value of the border-width
property creates the sum of the two lines)

- groove appears to be carved 
into the page

- ridge appears to stick out from 
the page

- inset appears embedded into 
the page

- outset looks like it is coming 
out of the screen

- hidden / none no border is shown

## Border Color

It is possible to individually control the colors of the borders 
on different sides of a box using:

- border-top-color
- border-right-color
- border-bottom-color
- border-left-color


## Shorthand

The border property allows you to specify the width, style and 
color of a border in one property (and the values should be coded 
in that specific order).


## Padding

The padding property allows you to specify how much space 
should appear between the content of an element and its border. 
The value of this property is most often specified in pixels (although it is also possible to 
use percentages or ems).
 If a percentage is used, the padding is a percentage of the browser 
window (or of the containing box if it is inside another box).

## margin

The margin property controls the gap between boxes. Its value 
is commonly given in pixels, although you may also use percentages or ems.

If one box sits on top of another, margins are collapsed , which 
means the larger of the two margins will be used and the smaller will be disregarded.


## Changing inline/block

The values this property can take are:
1. inline
This causes a block-level element to act like an inline element.

2. block
This causes an inline element to 
act like a block-level element.

3. inline-block
This causes a block-level element to flow like an inline element, while retaining other 
features of a block-level element.

4. none
This hides an element from the page. In this case, the element 
acts as though it is not on the page at all (although a user could 
still see the content of the box if they used the view source option 
in their browser).


## Hiding boxes

The visibility property allows you to hide boxes from users 
but It leaves a space where the element would have been.

This property can take two values:

- ***hidden***
This hides the element.

- ***visible***
This shows the element. If the visibility of an element 
is set to hidden, a blank space will appear in its place.


#  Duckett JS book: 

## Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)

**ARRAYS**

- An _array_ is a special type of variable. It doesn't just store one value; it stores a list of values. 

You should consider using an array whenever you are working 
with a list or a set of values that are related to each other. 

***Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold*** 


### CREATING AN ARRAY


The values are assigned to the array inside a pair of square brackets, and each value is 
separated by a comma.


This technique for creating an array is known as an array 
literal. 

- It is usually the preferred method for creating an array. 
You can also write each value on a separate line:

colors= ['white', 
'black', 
'custom']; 


### VALU ES IN ARRAYS

- Values in an array are accessed as if they are in a numbered list.

1. NUMBERING ITEMS IN AN ARRAY 
- Each item in an array is automatically given a number 
called an index. This can be used to access specific items in the array.

2. ACCESSING ITEMS IN AN ARRAY 
- To retrieve the third item on the list, the array name is specified 
along with the index number in square brackets. 

3. NUMBER OF ITEMS IN AN ARRAY
- Each array has a property called length, which holds the number 
of items in the array.


### ACCESSING & CHANGING 
VALUES IN AN ARRAY 

The first lines of code on the left create an array containing a list 
of three colors. (The values can be added on the same line or on 
separate lines as shown here.)

Having created the array, the third item on the list is changed 
from 'custom' to 'beige'. 

To access a value from an array, after the array name you specify 
the index number for that value inside square brackets.




## Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

### USING SWITCH STATEMENTS 

var msg; 
var level = 2; 
II Message 
11 Level 
c04/js/switch-statement .js 
/I Determine message based on level 
switch (level) { 
case 1: 
msg = 'Good luck on the first test ' ; 
break; 
case 2: 
msg = 'Second of three - keep going!'; 
break; 
case 3: 
msg = ' Final round, al most there!'; 
break; 
default : 
msg = 'Good l uck!'; 
break; 
var el = document.getEl ementByld('answer'); 
el .textContent = msg; 


- In this example, the purpose of the switch statement is to 
present the user with a different message depending on which 
level they are at. 

- The variable called leveL 1 contains a number indicating 
which level the user is on. This is then used as the switch value.

### TRUTHY & FALSY VALUES 

- Falsy values are treated as if they are false.
- Truthy values are treated as if they are true.


## KEY LOOP CONCEPTS 


**KEYWORDS** 

You will commonly see these 
two keywords used with loops: 
- break 
This keyword causes the 
termination of the loop and tells 
the interpreter to go onto the 
next statement of code outside 
of the loop. (You may also see it 
used in functions.)

- continue 
This keyword tells the interpreter 
to continue with the current 
iteration, and then check the 
condition again. (If it is true, the 
code runs again.)

PERFORMANCE ISSUES 

- If your loop is dealing with only 
a small number of items, this 
will not be an issue. If, however, 
your loop contains a lot of items, 
it can make the page slower to 
load. 

















