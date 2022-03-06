## What is CSS?

### CSS it's mean stands for Cascading Style Sheets

### CSS it's used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

![CSS picture](https://www.ekramy.net/sites/default/files/2021-01/css-illustration.png)

### CSS Syntax

- ### Syntax in programing is mean the set of rules that defines the combinations of symbols that are considered to be correctly structured statements or expressions in that language. 

### *For example if you want the main heading on your page to be shown as large red text The following code shows a very simple CSS rule that would achieve the styling described above:*

````
h1 {
    color: red;
    font-size: 5em;
}
````

- ### We can add Style for our web page by three way in CSS 

![Operators types picture](https://drbnee.com/image/catalog/767/1606694683_7242_767.jpg)

1. ### Inline CSS:

- Inline styles are defined within the "style" attribute of the relevant element:

### Example:
````
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
````

2. ### Internal CSS:

- Internal styles are defined within the `<style>` element, inside the `<head>` section of an HTML page:

### Example:

````
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
````


3. ### External CSS:

- External styles are defined within the `<link>` element, inside the `<head>` section of an HTML page:

### Example:

````
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
````
- #### Remember each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section.

- An external style sheet can be written in any text editor, and must be saved with a .css extension.

- The external .css file should not contain any HTML tags.

### Example for an external css file "style.css":

````
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
````

### CSS color

#### We can add color to css file in a simple way:

### For example:

````
body {
  background-color: black;
}
````

#### There are many ways to add more colors for example:

- ##### using HEX value:

````
body {color: #92a8d1;}
````

- ##### using RGB value:

````
body {color: rgb(201, 76, 76);}
````

- ##### using RGBA value:

````
body {color: rgba(201, 76, 76, 0.6);}
````

- ##### using HSL value:

````
body {color: hsl(89, 43%, 51%);}
````

- ##### using HSLA value:

````
body {color: hsla(89, 43%, 51%, 0.6);}
````

### All those way using to set color for body of HTML file

![Coding picture](https://speckyboy.com/wp-content/uploads/2021/06/pagination-thumb-750x500.jpg)

[More about CSS in wikipedia.](https://en.wikipedia.org/wiki/CSS)