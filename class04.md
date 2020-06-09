
# Links
![links](https://i.imgur.com/N2cPqhb.jpg)
● Links from one website to another.
``` <p>Movie Reviews:
<ul>
 <li><a href="http://www.empireonline.com">
 Empire</a></li>
 <li><a href="http://www.metacritic.com">
 Metacritic</a></li>
 <li><a href="http://www.rottentomatoes.com">
 Rotten Tomatoes</a></li>
 <li><a href="http://www.variety.com">
 Variety</a></li>
</ul>
</p> ```
● Links from one page to another on the same website.
``` <p>
<ul>
 <li><a href="index.html">Home</a></li>
 <li><a href="about-us.html">About</a></li>
 <li><a href="movies.html">Movies</a></li>
 <li><a href="contact.html">Contact</a></li>
</ul>
</p>
```
● Links from one part of a web page to another part of the same page.
``` <h1 id="top">Film-Making Terms</h1>
<a href="#arc_shot">Arc Shot</a><br />
<a href="#interlude">Interlude</a><br />
<a href="#prologue">Prologue</a><br /><br />
<h2 id="arc_shot">Arc Shot</h2>
<p>A shot in which the subject is photographed by an
 encircling or moving camera</p>
<h2 id="interlude">Interlude</h2>
<p>A brief, intervening film scene or sequence, not
 specifically tied to the plot, that appears
 within a film</p>
<h2 id="prologue">Prologue</h2>
<p>A speech, preface, introduction, or brief scene
 preceding the the main action or plot of a film;
 contrast to epilogue</p>
<p><a href="#top">Top</a></p> ```
● Links that open in a new browser window.
``` <a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```
● Links that start up your email program and address a new email to someone.
` <a href="mailto:jon@example.org">Email Jon</a> `



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
- **Function** is a block of code designed to perform a particular task.
``` function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
} ```

**calling a function**
` sayHi(); `
**declaring functions that need information**
**calling functions that need information**
- arguments as values ` getArea(3, 5); `
- arguments as variables ``` wallWidth =4;
wallHeight = 9;
getArea(wallWidth, wallHeight); ```
**getting a single value of a function**
![single value](https://i.imgur.com/xoFc6Hp.jpg)
**multiple values**
``` function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1]; ```
