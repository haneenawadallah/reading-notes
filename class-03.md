![reading notes](https://i.imgur.com/ySvG8Rd.jpg)
# Read 3 notes
### Lists
- there are three types of lists in HTML which are :
1. Ordered List.
1. Unordered list.
1. definition lists.
![LISTS](https://www.oreilly.com/library/view/beginning-css3/9781430244738/images/9781430244738_Fig10-01.jpg)
### nested lists
![nested list](https://s3.amazonaws.com/webucator-how-tos/419.png)
### Boxes
- we can control the width and height of a box in CSS
- min-width, max-width, max-height and min-height are used to make the box fit to the screen if it is small or big.
- there are two stylings overflow :
1. hidden : to make the content that doesnt fit the box hidden.
1. scroll : to add a scroll bar to show the not fitted content in the box.
- **Border** sperates the boxes
- **Margin** the outside of the border, the gab between boxes.
- **Padding** the space between the border and the content, it is used to increase readabilty of the content.
![](https://i.stack.imgur.com/UHD7W.gif)
- Border width by these values :
``` thin
medium
thick
```
- each side of the box can be sized
```border-top-width
border-right-width
border-bottom-width
border-left-width
```
- border style
![boxes](https://i.imgur.com/bjVsQa9.jpg)
- each side of the box can have different color.
- you can use all properties together.
- padding and margin values can be specified like this :
```
margin-top
margin-right
margin-bottom
margin-left
```
```
padding-top
padding-right
padding-bottom
padding-left
```
- we can center a text in a box by using
` text-align: center; `
- display values are inline, block, inline-block and none.
- an image can be a border by using : 
``` -moz-border-image: url("images/dots.gif")  ``` and it can be stretch, repeat and round.
- box shadows
- rounded corners.

## Javascript “Decisions and Loops” from switch statements 
![if](https://i.imgur.com/X1ywSe4.jpg)
- IF ... ELSE
1. There is no need to provide an el se
option. (You can just use an if
statement.)
1. With a series of if statements, they are
all checked even if a match has been found
(so it performs more slowly than switch). 
- SWITCH
1. You have a default option that is run if
none of the cases match.
1. If a match is found, that code is run; then
the break statement stops the rest of
the switch statement running (providing
better performance than multiple i f
statements). 
 **loops**
- For , while, do while

- Conditional statements allow your code to make
decisions about what to do next.
Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
- Logical operators allow you to combine more than one
set of comparison operators.
- if ... else statements allow you to run one set of code
- if a condition is true, and another if it is false.
- switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
- Data types can be coerced from one type to another.
- All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and
do ... while. Each repeats a set of statements. 