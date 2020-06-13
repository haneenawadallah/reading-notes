# Read06 
## The problem domain is the hardest in programming
- programming is like a puzzile, when you see the big picture the implemntation will be easy.
- It is much more expensive and time consuming to do things over than it is to do them right the first time.

*** 

# objects
- Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
- variables at object are called **property**
- functions are called **methods**
- the name of an object is **key**
- HTML uses attribute names and values.
- CSS uses property names and values. 
***
# Document object model
- THE DOM TREE IS A MODEL OF A WEB PAGE 
- Dom tree consists of four main types of nodes (the document node, element nodes, attribute nodes and tect nodes). 
- The terms elements and element nodes are used interchangeably
but when people say the DOM is working with an element,
it is actually working with a node that represents that element. 
## Caching Dom queries
- METHODS THAT RETURN A SINGLE ELEMENT NODE: 
1. getElementByld('id')
1. querySel ector( 'css selector')
- METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
1. getEl ementsByClassName( 'class')
1. getEl ementsByTagName( 'tagname')
1. querySelectorAll ( 'css selector')
***
- Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
- From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and
child elements that are siblings of each other.
In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree . 
