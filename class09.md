## FORMS
![](blob:https://imgur.com/edfb426a-192d-4667-aec2-34d3467f47cc)
### Forms structures

~~~ 
 <form action="http://www.example.com/subscribe.php"
method="get">
<p>This is where the form controls will appear.
 </p>
</form>
 ~~~ 
` <form> ` element always has the **action** , **method**  **id** attribute.
~~~
<form action="http://www.example.com/login.php">
<p>Username:
 <input type="text" name="username" size="15"
 maxlength="30" />
</p>
</form> 
~~~

` type="text"` : to create single line text input.
` name ` : to make the server know what type of input.
` size ` : used in older codes, now we use css.
` maxlength ` : to limit the number of charecters the user use.
- for **passwords** , ` type="password" ` will make it look as black dots.
- Text area :
~~~
 <form action="http://www.example.com/comments.php">
<p>What did you think of this gig?</p>
 <textarea name="comments" cols="20" rows="4">Enter
 your comments...</textarea>
</form> 
~~~

is used to create multiline input.
**radio button** is used to make the user choose one option.
~~~
 <form action="http://www.example.com/profile.php">
<p>Please select your favorite genre:
 <br />
 <input type="radio" name="genre" value="rock"
 checked="checked" /> Rock
 <input type="radio" name="genre" value="pop" />
 Pop
 <input type="radio" name="genre" value="jazz" />
 Jazz
</p>
</form> 
~~~ 
`checked` is used in the input only once to indicate which value is selected.
`type="checkbox"`
Checkboxes allow users to select
(and unselect) one or more
options in answer to a question.
**Drop down list box**

~~~ 
<form action="http://www.example.com/profile.php">
<p>What device do you listen to music on?</p>
<select name="devices">
 <option value="ipod">iPod</option>
 <option value="radio">Radio</option>
 <option value="computer">Computer</option>
 </select>
</form> 
~~~

**File input box**

~~~ <form action="http://www.example.com/upload.php"
method="post">
<p>Upload your song in MP3 format:</p>
<input type="file" name="user-song" /><br />
<input type="submit" value="Upload" />
</form> 
~~~

## Events 
- Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
- Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
- When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
- You can use event delegation to monitor for events
that happen on all of the children of an element.
- The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 