# Layout
## Positioning Elements
- **Building blocks** CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
- **Block-level elements** start on a new line.
- **Inline elements** flow in between
surrounding text.
- **Containing Elements** If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
**Controlling the Position of Elements**
1. Normal flow Every block-level element appears on a new line.
1. Relative Positioning This moves an element from the position it would be in normal flow.
1.Absolute positioning This positions the element in relation to its containing element.
![position](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)
- **Box offset** To indicate where a box should be positioned,and to tell the browser how far from the top or bottom and left or right it should be placed.
- **Floating Elements** allowsyou to take that element out of normal flow and position it to the far left or right of a
containing box.
# Functions
- **Function**
 is a block of code designed to perform a particular task.
 ~~~
 function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
} 
~~~
**calling** a **function**
` sayHi(); `
**declaring functions that need information**
**calling functions that need information**
- arguments as values ` getArea(3, 5); `
- arguments as variables ``` wallWidth =4;
wallHeight = 9;
getArea(wallWidth, wallHeight); ```
**getting a single value of a function**
![single value](https://i.imgur.com/xoFc6Hp.jpg)

**multiple** **values**
~~~
function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1];
 ~~~
- `<div>` elements are often used as containing elements
to group together sections of a page.
-  Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.