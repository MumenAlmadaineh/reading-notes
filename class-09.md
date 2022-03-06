# HTML Forms: -

HTML form is used to collect user input to sent it to server for processing.

We can add form to web page in HTML by using `<form>` example:

```
<form>
.
form elements
.
</form>
```

![HTML5 layout elements Picture](https://3.bp.blogspot.com/-7kklNHI15s8/WJ38zQeRtRI/AAAAAAAAQdE/W3l78lupSfQh2wAdII29BxSZt4il8rBqgCLcB/s1600/tforms.png)

# Lists in HTML

![# Lists in HTML photo](https://media.gcflearnfree.org/content/5e46ef60397c182fec255f32_02_14_2020/lists.png)

### How many numbers of lists are on HTML?

- There are three types of lists in HTML

1. Ordered lists: ordered lists in HTML used to create a list of items and all item inside it has number, example:

```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol> 
```

2. Unordered lists: Like ordered list unordered lists are used to create a list of items but the item inside it has not number, example:

- #### The result will be like this

1. Coffee
2. Tea
3. Milk

```
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  
```

#### The result will be like this

- Coffee
- Tea
- Milk

3. Definition lists: definition lists in HTML are used to create a list of items and each item inside it has description, example:

```
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

#### The result will be like this

<pre>
Coffee
    Black hot drink <br />
Milk
    White cold drink
</pre>

## **Tables in HTML**

Table is used to creating rows and columns on a Web page to arrange data into it.

![# Tables in HTML photo](https://cf2.ppt-online.org/files2/slide/x/x03e9GTk5pRrMdEywnDSZbjBHJ2zoYaFmfuKsh/slide-10.jpg)

The `<table>` tag defines an HTML table for example:

```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

- Text in `<th>` elements are bold and centered by default.

- Text in `<td>` elements are regular and left-aligned by default.

# Event in JavaScript

![# Event in JavaScript photo](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

Event it is like something the browser does, or something a user does.

>(W3 school) HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

- With single quotes:

-`<element event='some JavaScript'>`

- With double quotes:

`<element event="some JavaScript">`

onclick attribute (with code), is added to a `<button>` element for example:

`<button onclick="document.getElementById('City').innerHTML = Date()">The name of city is?</button>`

>(W3 school) What can JavaScript Do?
Event handlers can be used to handle and verify user input, user actions, and browser actions:

- Things that should be done every time a page loads
- Things that should be done when the page is closed
- Action that should be performed when a user clicks a button
- Content that should be verified when a user inputs data
And more ...
- Many different methods can be used to let JavaScript work with events:

- HTML event attributes can execute JavaScript code directly
- HTML event attributes can call JavaScript functions
- We can assign your own event handler functions to HTML elements
- We can prevent events from being sent or being handled
And more ...


[If you want more about event see this video](https://www.youtube.com/watch?v=YiOlaiscqDY)
