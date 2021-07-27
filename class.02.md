# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

## summary 

### Chapter 2: text  (pp.40-61)

- ***structural markup***

#### Headings
 HTML has six levels of **headings** 


### paragraphs 
If you want to creat a _parahraph_, you should surrond it by an opeing tag and closing tag: <p></p>

### Bold & Italic
- By enclosing words in the tags '<'b>' and '<'/b>' we can make characters appear bold.
- By enclosing words in the tags '<'i>' and '<'/i>' we can make characters appear italic.

### Superscript & Subscript
- '<'sup>': This element is used to contain characters that should be superscript such as the suffixes.
- '<'sub>: This element is used to contain characters that should be subscript.


- ***Semantic Markup***

### Strong & Emphasis
- The use of the '<'strong> element indicates that its content has strong importancen (bold).
- The '<'em> element indicates emphasis that subtly changes the meaning of a sentence (italic).

### Quotations
- The '<'blockquote> element is used for longer quotes that take up an entire paragraph.
- The element is used for '<'q> shorter quotes that sit within a paragraph.

### Abbreviations & Acronyms
- The <'abbr> element can be used for an abbreviation or an acronym.
- A title attribute on the opening tag is used to specify the full term.

### Citations & Definitions
- The <'cite> element can be used to indicate where the citation is from when you are referencing a piece of work.
Browsers will render the content of a <'cite> element in italics.

- The <'dfn> element is used to indicate the defining instance of a new term.


# chapter 10: Introducing CSS (pp.226-245)

## BLOCK & INLINE ELEMENTS:

_Block level_ elements look like they start on a new line. 

_Inline elements_ flow within the text and do not start on a new line. Examples include <'b>, <'i>, <'img>, <'em> and <'span>.


***Example Styles***

|boxes|style|
|-----|-----|
|Width and height| Typeface|
|Borders:color-width-style| Size|


## ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML

### innerHTML 
- When getting HTML from an element, the i nnerHTML property will get the content of an element and return it as one long string, including any markup that the element contains.


# Chapter 2: Basic JavaScript Instructions
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon

## DATA TYPES:
1. NUMERIC DATA TYPE (1)
2. STRING DATA TYPE ('Hi')
3. BOOLEAN DATA TYPE (true)



***CHANGING THE VALUE OF A VARIABLE***

Once you have assigned a value to a variable, you can then  change what is stored in the  variable later in the same script. 

- For example, the value of a shipping variable might start out as being false. Then  something in the code might change the ability to ship the 
item and you could therefore change the value to true.




# Chapter 4: “Decisions and Loops”  (pp.145-162)


_Comparison operators: Evaluating conditions_

- == is equal to
(This operator compares two values (numbers, strings, or Booleans) to see if they are the same.)\

- != is not equal to
(This operator compares two values (numbers, strings, or Booleans) to see if they are not the same.)

- === strict equal to
(This operator compares two values to check that both the data type and value are the same.)

-!== strict not equal to
(This operator compares two values to check that both the data type and value are not the same.)

## If Statements

The if statement evaluates (or checks) a condition. 

- If the condition evaluates to true, the code block is executed.
- If the condition resolves to false,the statements in that code block are not run.

IF...ELSE STATEMENTS
The **if.. else** statement checks a condition. If it resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead.


