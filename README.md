# Html-CheatSheet
## Structure
This is the basic template or barebone structure of HTML.

### Boilerplate

```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```
# Headings
There are six headings available in HTML, H1 is the largest among all, and H6 is the smallest.

# h1  Tag 

```
<h1>Heading 1</h1>
```
## h2 Tag 
```
<h2>Heading 2</h2>
```
### h3 Tag
```
<h3>Heading 3</h3>
```
#### h4 Tag 
```
<h4>Heading 4</h4>
```
##### h5 Tag 
```
<h5>Heading 5</h5>
```
###### h6 Tag 
```
<h6>Heading 6</h6>
```

## Container

Container tags are the tags that contain some data such as text, image, etc. 
There are several container tags in HTML.

## div tag
div tag or division tag is used to make blocks or divisions in the document.
```
<div> This is div block </div>
```
### span tag
span is a container for inline content
```
<span> This is span block </span>
```
### p tag
paragraph
```
<p> This is a paragraph </p>
```
### pre tag
pre tag represents pre-formatted text 
```
<pre> Hello World </pre>
```

### code tag
code tag is used to represent source codes
```
<code>
import python
</code>
```
## Text Formatting
Text formatting tags are used to format text or data of HTML documents. You can do certain
things like creating italic, bold, strong text to make your document look more attractive and
understandable.
### b tag
```
<b>I'm bold text</b>
```
### strong tag 
```
<strong>I'm important text</strong>
```
### i tag
```
<i>I'm italic text</i>
```
### em tag
```
<em>Emphasized text</em>
```
### sub tag
```
<sub>Subscript</sub>
```
### sup tag
```
<sup>Superscript</sup>
```
## Lists
Lists can be either numerical, alphabetic, bullet, or other symbols. You can specify list type and
list items in HTML for the clean document.

### ol tag
Ordered list starts with < ol > tag and each list item starts with < li > tag
```
<ol>
<li>Data 1</li>
<li>Data 2</li>
<li>Data 3</li>
</ol>
```
### ul tag
```
<ul>
<li>Your Data</li>
<li>Your Data</li>
</ul>
```
## Media
Media is anything that is present in digital form such as image, video, audio, etc.

### audio tag
It is used to embed sound content in the document.
```
<audio controls>
<source src="demo.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```
### img tag
It is used to embed or import image in a webpage.
```
<img src="Source_of_image" alt="Alternate text">
```
### video tag
It is used to embed video in the webpage.
```
<video width="480" height="320" controls>
<source src="demo_move.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
```
## Table
A table is a collection of rows and columns. It is used to represent data in tabular form.

**Table Structure**
```
<table>
<caption>Demo Table</caption>
<thead>
<tr>
<th>Column1</th>
<th colspan="2">Column2</th>
</tr>
</thead>
<tbody>
<tr>
<td>Data1</td>
<td>Data2</td>
<td>Data2</td>
</tr>
<tr>
<td>Data1</td>
<td>Data2</td>
<td>Data2</td>
</tr>
</tbody>
<tfoot>
<tr>
<td>&nbsp;</td>
<td>Data</td>
<td>Data</td>
</tr>
</tfoot>
</table>
```

## Links
Links are clickable text that can redirect you to some other page.

### a tag
< a > or anchor tag defines a hyperlink.
```
<a href="https://google.com/">Visit Google.com!</a>
```
## Form
**Sample Form**

Form is used to collect user's input, generally user's data is sent to server for further processing.
```
<form action="/action.php" method="post">
Name: <input name="name" type="text" /> <br />
Age: <input max="90" min="1" name="age" step="1" type="number" value="18" />
<select name="gender">
<option selected="selected" value="male">Male</option>
<option value="female">Female</option>
</select><br />
<input checked="checked" name="newsletter" type="radio" value="daily" /> Dai
type="radio" value="weekly" /> Weekly<br />
<textarea cols="20" name="comments" rows="5">Comment</textarea><br />
<label><input name="terms" type="checkbox" value="tandc" />Accept terms</lab
<input type="submit" value="Submit" />
</form>
```
## Characters & Symbols
Some symbols are not directly present on the keyboard, but there are some ways to use them in
HTML documents. We can display them either by entity name, decimal, or hexadecimal value.

**Copyright Symbol (©)**
```
&copy;
```
### Less than (<)
```
&lt; 
```
### Greater than (>)
```
&gt;
```
### Ampersand (&)
``` 
&amp;
```
### Dollar ($)
```
&dollar;
```
## Random Text
**Lorem**
```
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, quo.
```
## Semantic Elements
Semantic elements are those elements that are self describable, i.e., from their name itself, you
can understand their meaning.

### section tag
It defines a section in the document
```
<section>This is a section</section>
```
### article tag 
It represents self-contained content
```
<article> Enter your data here </article>
```
### aside tag
It is used to place content in the sidebar
```
<aside> Your data </aside>
```
