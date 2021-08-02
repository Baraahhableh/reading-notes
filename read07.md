# Readings : Object-Oriented Programming, HTML Tables

## From the Duckett HTML book:

#### Chapter 6: “Tables” (pp.126-145)

## Tables

- A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results.


### Basic Table Structure
1. <table>
The <table> element is used 
to create a table. The contents 
of the table are written out row 
by row.

2. <tr>
You indicate the start of each 
row using the opening <tr> tag. 
(The tr stands for table row.) 
It is followed by one or more 
3. <td> elements (one for each cell 
in that row). 

At the end of the row you use a 
closing </tr> tag.

4. <td>
Each cell of a table is 
represented using a <td>
element. (The td stands for 
table data.)
At the end of each cell you use a 
closing </td> tag.


## Long Tables

- These elements help people 
who use screen readers and also 
allow you to style these sections 
in a different manner than the 
rest of the table (as you will see 
when you learn about CSS).


1. <thead>
The headings of the table should 
sit inside the <thead> element. 
2. <tbody>
The body should sit inside the 
<tbody> element. 
3. <tfoot>
The footer belongs inside the 
<tfoot> element.


# Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

- GLOBAL OBJECTS: 
STRING O BJECT

**Whenever you have a value that is a string**, you can use the properties and methods of the String object on that value. This example stores the phrase "Home sweet home " in a variable.



### DATA TYPES REVISITED

- In JavaScript there are six data types: 
Five of them are described as simple (or primitive) data types. 
The sixth is the object (and is referred to as a complex data type).

1. String 
2. Number 
3. Boolean 
4. Undefined (a variable that has been declared, but 
no value has been assigned to it yet) 
5. Null (a variable with no value - it may have had 
one at some point, but no longer has a value).
6. 6.0bject 
Under the hood, arrays and functions are considered 
types of objects. 

- GLOBAL OBJECTS: DATE OBJECT (AND TIME)

The toDateStri ng () method 
will display the date in the 
following format: 
Wed Apr 16 1975. 
If you want to display the date in 
another way, you can construct 
a different date format using the 
individual methods listed above 
to represent the individual parts: 
day, date, month, year.

















