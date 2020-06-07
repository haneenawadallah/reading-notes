![reading notes](https://i.imgur.com/ySvG8Rd.jpg)
# Read 2 Notes

![cheat sheet](https://websitesetup.org/wp-content/uploads/2019/10/HTML-Cheat-Sheet-PDF-1024x555.jpg)
- to write headings in html we use < h1 > < h2 > < h3 > < h4 > < h5 > < h6 > the number shows the level.
- we use < p > to write a paragraph.
- < b> is used for bold and < i > is used for italic.
- < sup > is used for suffixes of dates and powers of numbers
- < sub > is used with chemical formulas.
- < br  / > to create a line break.
- < hr  / > to create break between themes.
- < strong > is ised to show importance
- < em > is used to emphasis.
- < blockquote > is used for long qoutes.
- < q > is used for short qoutes.
- < abbr > is used to show the full term if we use shortcut for it.
- < cite > used for citation >
- < dfn > is used to define new concepts.
- < address > used for the address of the page outhor physical or email address.
- < ins > is used fot the inserted content, while < del > shows the deleted ones.
- < s > for the content that are no longer true but dont need to be deleted.
- HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
- They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

## CSS
![CSS rules](https://i.imgur.com/2CghTsm.jpg)
- CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
- Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
- Different types of selectors allow you to target your
rules at different elements.
- Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document,
although they may appear within an HTML page.

![js](https://miro.medium.com/max/1200/1*QDmeWi-xnFxzfwbsTrxunQ.jpeg)
JS
- A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
- Statements should end with a semicolon. 
- A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in **variables**. 
- Array example : `var cars = ["Saab", "Volvo", "BMW"];`
- JavaScript variables are containers for storing data values.

In this example, x, y, and z, are variables:

Example
`var x = 5;`
`var y = 6;`
`var z = x + y;`
- Arithmetic operators are used to perform arithmetic on numbers:

| Operator	| Description |
| --------  | ----------  |
|`+`	| Addition | 
| `-`	| Subtraction | 
| `*`	| Multiplication| 
| `**`	| Exponentiation (ES2016) | 
| `/`	| Division | 
| `%`	|  Modulus (Division Remainder) | 
| `++`	| Increment | 
| `--` | 	Decrement | 

- Loops are handy, if you want to run the same code over and over again, each time with a different value.

Often this is the case when working with arrays:

Instead of writing:
`text += cars[0] + "< br >";`
`text += cars[1] + "< br >";`
`text += cars[2] + "< br > ";`
`text += cars[3] + "<br>";`
`text += cars[4] + "<br>";`
`text += cars[5] + "<br>";`
You can write:
`var i;`
`for (i = 0; i < cars.length; i++) {`
 ` text += cars[i] + "<br>";`
`}`

- JavaScript supports different kinds of loops:

**for** - loops through a block of code a number of times
**for/in** - loops through the properties of an object
**for/of** - loops through the values of an iterable object
**while** - loops through a block of code while a specified condition is true
**do/while** - also loops through a block of code while a specified condition is true.