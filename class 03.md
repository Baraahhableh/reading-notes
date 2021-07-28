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

