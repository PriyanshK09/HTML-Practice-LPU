
Array :
◾ A variable with multiple values of same type.
◾ Use the len() method to return the length of an array (the number of elements in an array).

CSS :
CSS is of 3 types :-
1,) In-line CSS : CSS Styling done inside a HTML tag in the .html file itself.
e,g - Style Tag Editing

2.) Internal CSS : Desiging of CSS inside the Head Tag of HTML File.
e.g - 
<head>
        <style>
              p*{
                    color: blue
               }
         </style>
</head>

*intead of "p" you need to enter the area you want to edit with css (such as p for paragraph, h1 for h1 heading, etc)

CSS Desiging will be done inside the Style Tag written under the Head Tag

3.) External CSS : CSS done outside the HTML File and Linked for styling.
--------------------------

Priority Rating of CSS Types for index.html :

Inline CSS has the top-most Priority for the HTML File.
Internal and External CSS Priority can be set by the order of writing in HTML File.
e.g : 
Internal CSS above External = External CSS has more priority.
External CSS above Internal = Internal CSS has more priority.
---------------------------