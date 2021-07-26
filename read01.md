
# Chapter 1: Structure (pp.12-39)
How Pages Use Structure:
The use of headings and subheadings in any document often reflects a hierarchy of information This might be expanded upon under subheadings lower down on the page.

***HTML Describes the Structure of Pages ***
To describe the structure of a web page, we add code to the words we want to appear on the page. The HTML code is made up of characters that live inside angled brackets which are called HTML elements.
Elements are:

made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.)
tells the browser something about the information that sits between its opening and closing tags (Tags act like containers).
The terms "tag" and "element" are often used interchangeably. Tags are often referred to as elements. Also, opening tags can carry attributes, which tell us more about the content of that element
Attributes:


## Tell us more about elements
provide additional information about the contents of an element
Appear on the opening tag of the element
Require a name and a value, separated by an equals sign.
The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.


Different attributes can have different values.
The majority of attributes can only be used on certain elements
Most attribute values are either predefined or follow a specific format.
contains information about the page
usually has a <title> element inside it.


Looking at How Other sites are Built
- Simply go to the website that you want to look at and right click and select "View Page Source." You should see a new window appear, and it will contain the source code that was used to create this page.
In general to learn HTML you need to know what tags are available for you to use, what they do, and where they can go.
Chapter 8: Extra Markup (p.176-199)
The Evolution of HTML:
HTML 4 Released 1997
XHTML 1.0 Released 2000
HTML5 Released 2000
DOCTYPEs:
DOCTYPES tell browsers which version of HTML you are using.
Type	Expression
HTML5	
HTML 4	
Transitional XHTML 1.0	
Strict XHTML 1.0	
XML Declaration	
Comments in HTML
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
Advantages:
Because, no matter how familiar you are with the page at the time of writing it, when you come back to it later (or if someone else needs to look at the code), comments will make it much easier to understand.
Comments can be viewed by anyone who looks at the source code behind the page although they are not visible to users in the main browser window.
.
They can be used around blocks of code to stop that code from being displayed in the browser.
ID Attribute:
The id attribute is known as a global attribute because it can be used on any element
Every HTML element can carry the id attribute.
It is used to uniquely identify that element from other elements on the page.
Its value should start with a letter or an underscore (not a number or any other character).
It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
For CSS: giving an element a unique identity allows you to style it differently than any other instance of the same element on the page
For JavaScript: id attributes can be used to allow the script to work with that particular element.
Class Attribute:
Every HTML element can also carry a class attribute
A way to identify several elements as being different from the other elements on the page (rather than uniquely identifying one element within a document)

-Using this attribute will only change its appearance if there is a CSS rule.

Block Elements:
Block level elements are those that will always appear to start on a new line in the browser window. Examples of block elements are
,
,

, and
.


### Inline Elements:
Inline elements are those that will always appear to continue on the same line as their neighbouring elements. Examples of inline elements are , , , and .
Grouping Text & Elements In a Block:
This element allows you to group a set of elements together in one block-level box. (to contain all of the elements for the header of your site i.e. the logo and the navigation, or to contain comments from visitors.
make it easier to follow your code to hold each section of the page.
In a browser, the contents of the element will start on a new line, but other than this it will make no difference to the presentation of the page. 


grouping Text & Elements Inline:
The element acts like an inline equivalent of the
element. It is used to:
Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
Contain a number of inline elements
Control the appearance of the content of this element using CSS
A class or id attribute is used with elements to explain the purpose of this element. 


IFrames: (This term is an abbreviation of inline frame)
<iframe>
This element is like a little window that has been cut into your page which in that window you can see another page.
It can be used to embed a Google Map into a page.
The content of the iframe can be any html page.
There are a few attributes that you will need to know to use it when using <iframe> element:
src: This attribute specifies the URL of the page to show in the frame.
height: This attribute specifies the height of the iframe in pixels.
width: This attribute specifies the width of the iframe in pixels
scrolling: This attribute:
- indicates whether the iframe should have scrollbars or not.
- It is important if the page inside the iframe is larger than the space you have allowed for it.
- It allows the user to move around the frame to see more content, and can take one of three values: -
yes (to show scrollbars),
no (to hide scrollbars)
auto (to show them only if needed).


## Information About Your Pages
Lives inside the element and contains information about that web page.
not visible to users.
an empty element (does not have a closing tag).
fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive.
uses attributes to carry the information, like: the name and content attributes, which tend to be used together and specify properties of the entire page.
The value of the name attribute is the property you are setting.
: the name attribute indicates an intention to specify a description for the page.
Commonly used values: description, keywords, and robots.
The value of the content attribute is the value that you want to give to this property.
: the content attribute is where this description is actually specified.
also uses the http-equiv and content attributes in pairs. Following are examples for the http-equiv attribute:
author: This defines the author of the web page.
pragma: This prevents the browser from caching the page, and has the value of "no-cache".




1. Headers & Footers
The main header or footer that appears at the top or bottom of every page on the site.

2. Navigation
The element is used to contain the major navigational blocks on the site such as the primary site navigation.


3. Articles
*The element acts as a container for any section of a page that could stand alone and potentially be syndicated. *

4. Article
The element has two purposes, depending on whether it is inside an element or not.



5. Sections
The element groups related content together, and typically each section would have its own heading.


6. Heading Groups
The purpose of the element is to **group together a set of one or more
through elements so that they are treated as one single heading.**

7. Figures
It can be used to contain any content that is referenced from the main flow of an article (not just images).

8. Sectioning Elements
The element will remain an important way to group together related elements



Helping Older Browsers Understand

Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of CSS below which states which new elements should be rendered as block-level elements:

header, section, footer, aside, nav, article, figure { display: block;}

#### Chapter 18: Process & Design (pp.452-475)
Who is the Site For?
Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

Why Do People Visit YOUR Website?
Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason.

What Your Visitors are Trying to Achieve?
It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations. 


## What Information Do Your Visitors Need?
You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve their goals quickly and effectively. You may want to offer additional supporting information that you think they might find helpful. You can prioritize levels of information from key points down to non-essential or background information.





WireFrames
*A wireframe is a simple sketch of the key information that needs to go on each page of a site.*



*Visual hierarchy*
Most web users do not read entire pages. Rather, they skim to find information. You can use contrast to create a visual hierarchy that gets across your key message and helps users find what they are looking for. Visual hierarchy refers to the order in which your eyes perceive what they see.


Designing Navigation
Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized. Good navigation tends to follow these principles: Concise, Clear, Selective, Context, Interactive, and Consistent.

JavaScript Book:
Chapter 1: The ABC of Programming (pp.11-52)
A. ***What is a script and how do I create one?***
A script is a series of instructions that a computer can follow to achieve a goal. Scripts are made up of instructions a computer can follow step by step. It can run different sections of the code in response to the situation around them.
Writing a script:
To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
DEFINE THE GOAL
First, you need to define the task you want to achieve. 2. ##### DESIGN THE SCRIPT To design a script you split the goal out into a series of tasks that are going to be involved in solving the puzzle. This can be represented using a flowchart. You can then write down individual steps that the computer needs to perform in order to complete each individual task. 3. ##### CODE EACH STEP Each of the steps needs to be written in a programming language that the computer understands.

-Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically.
-To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task ( a flowchart can help)


B. ***How do computers fit in with the world around them? ***
Objects: In computer programming, each physical thing in the world can be represented as an object.
Each object can have its own:
Properties: Programmers call characteristics the properties of an object. Each property has a name and a value.
Events: happen when something interacts with objects. These interactions can change the values of the properties in these objects.
Methods: represent things people need to do with objects. They can retrieve or update the values of an object's properties.

-The events, methods, and properties of an object all relate to each other.
-The document object represents an HTML page.

***How does a browser see a web page? ***
In order to understand how you can change the content of an HTML page using JavaScript, you need to know how a browser interprets the HTML code and apply styling to it.
Receive a page as html code
Create a model of the page and store it in memory
Use a rendering engine to show the page on screen
Computers create models of the world using data.

The models use objects to represent physical things.
Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with the computer. -Programmers can write code to say "When this event occurs, run that code."
Web browsers use HTML markup to create a model of the web page. Each element creates its own node (which is a kind of object),

C. How do I write a script for a web page?
1. : CONTENT LAYER
2. {CSS} : PRESENTATION LAYER
3. javascript () : BEHAVIOR LAYER
These three layers form the basis of a popular approach to building web pages called progressive enhancement.
JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.
When you want to use JavaScript with a web page, you use the HTML <script> element to tell the browser it is coming across a script. Its src attribute tells people where the JavaScript file is stored.
You may see JavaScript in the HTML between opening <script> and closing </script> tags, but it is recommended to put scripts in their own files.