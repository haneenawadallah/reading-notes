# Read07
## Domain Modeling

**Domain modeling** is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

***

tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.

***

## TABLES
- `<table>`  element is used
to create a table. The contents
of the table are written out row
by row.

- `<tr>` table row to store data 

- `<td>` the data stored 

- `<th>` is used for table heading

- `<thead>` for the heading of a long table

- `<tbody>` for the body

- `<tfoot>` for the footer 

- You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
~~~

 <html>
<head>
 <title>Tables</title>
</head>
<body>
 <table>
 <thead>
 <tr>
 <th></th>
 <th scope="col">Home starter hosting</th>
 <th scope="col">Premium business hosting</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <th scope="row">Disk space</th>
 <td>250mb</td>
 <td>1gb</td>
 </tr>
 <tr>
 <th scope="row">Bandwidth</th>
 <td>5gb per month</td>
 <td>50gb per month</td>
 </tr>
 <!-- more rows like the two above here -->
 </tbody>
 <tfoot>
 <tr>
 <td></td>
 <td colspan="2">Sign up now and save 10%!</td>
 </tr>
 </tfoot>
 </table>
</body>
</html>
~~~ 

*** 

## Functions, Methods, and Objects

- Functions allow you to group a set of related
statements together that represent a single task.
- Functions can take parameters (informatiorJ required
to do their job) and may return a value.
- An object is a series of variables and functions that
represent something from the world around you.
- In an object, variables are known as properties of the
object; functions are known as methods of the object.
- Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
- JavaScript also has several built-in objects such as
- String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
- Arrays and objects can be used to create complex data
sets (and both can contain the other). 

 *** 