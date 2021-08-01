# WHAT IS AN OBJECT? 

***Objects group together a set of variables and functions to create a model*** of a something you would recognize from the real world. In an object, variables and functions take on new names.

This object represents a hotel. It has five properties and one method. 
The object is in *curly braces*. It is stored in a variable called hotel . 


**Like variables and named functions, properties and methods have a name and a value. In an object, that name is called a key.** 


Programmers use a lot of name/value pairs: 

- HTML uses attribute names and values. 
- CSS uses property names and values.


### CREATING· OBJECTS USING LITERAL NOTATION 
______________________________________________

c3/ j s/obj ect-1itera1 . j s 
var hote l = { 
name: 'Quay', 
rooms: 40, 
booked : 25, 
checkAvailability: function() { 
return this.rooms - this.booked; 
} 
} ; 
JAVASCRIPT 
var el Name = document .getElementByld('hotelName'); 
elName.textContent =hotel .name; 
var elRooms = document.getElementByid{'rooms'); 
elRooms.textContent = hotel .checkAvailability();

_This example starts by creating an object using literal notation._

- This object is called hotel which represents a hotel called Quay with 40 rooms (25 of which have been booked). 
Next, the content of the page is updated with data from this object.
- It shows the name of the hotel by accessing the object's  name property and the number of vacant rooms using the 
checkAvail ability() method. 



#### CREATING MORE OBJECT LITERALS 
_if you had two objects on the same page, you would create each one using the same notation but store them in variables with different names_


# Document Object Model

### THE DOM TREE IS A MODEL OF A WEB PAGE

- As a browser loads a web page, it creates a model of that page. 
The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes. 

- ATTRIBUTE NODES 

1. attribute 

The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.

2. TEXT NODES 
Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node. 

