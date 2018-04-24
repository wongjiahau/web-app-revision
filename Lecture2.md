# Lecture 2
Memorize the following code

## Headings
Used to create headings. `<h1>` is the biggest and `<h6>` is the smallest.  

|Code|Example|  
|--|--|  
| `<h1>Heading 1</h1>` | <h1>Heading 1</h1>
| `<h2>Heading 2</h2>` | <h2>Heading 2</h2>
| `<h3>Heading 3</h3>` | <h3>Heading 3</h3>
| `<h4>Heading 4</h4>` | <h4>Heading 4</h4>
| `<h5>Heading 5</h5>` | <h5>Heading 5</h5>
| `<h6>Heading 6</h6>` | <h6>Heading 6</h6>

## Paragraph
- `<p>` is used to identify blocks of paragraph text.  
- `<br>` is linebreak
```html
<p>This is a paragraph</p>
<br/>
```

## Formatting
|Code|Explanation|Example|
|--|--|--|
|`<b>I'm bold</b>`| Bold  | <b>I'm bold</b>
|`<strong> I'm strong </strong>` | Important  | <strong>I'm strong</strong>
|`<i> I'm italic </i>` | Italic  | <i>I'm italic</i>
| `<em> I'm emphasized </em>` | Emphasized  | <em>I'm emphasized</em>
| `<mark>I'm marked</mark>` | Highlight  | <mark>I'm marked</mark>
| `<del>I'm marked</del>` | Strikethrough | <del>I'm marked</del>
| `<ins>I'm underlined</ins>` | Underline | <ins>I'm underlined</ins>
| `Hello <sub>subscript</sub>` | Subscript | Hello <sub>subscript</sub>
| `Bye <sup>superscript</sup>` | Superscript | Bye <sup>superscript</sup>


## Anchor
Used to create a hyperlink to another webpage or another location within the same webpage.

- `href` is used to define the link address.  
- `target` is used to define where to open the link
- `<img>` element (inside `<a>`) to use an image as link


|Code|Example|  
|-|-|  
|`<a href="https://www.google.com">Click me!</a>`|<a href="https://www.google.com">Click me!</a>

By default, a link will appear like this (in all browsers):  
- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red

You can use CSS to change the color, for example:
```css

a:visited { 
    color: pink;
    font-weight: bold;
}
```
This will make visited link to be <b><a style="color:pink;" href="">pink and bold</a></b>.

## List
- `<ul>` to define an unordered list
- `<ol>` to define an ordered list
- `<li>` a list item (must be inside `<ul>` or `<ol>`)

- `<dl>` to define a definition list
- `<dt>` to define a definition term
- `<dd>` to define definition description

---

### Example(1): Unordered list

```html
<ul>
    <li>Coffee</li>
    <li>Teh</li>
    <li>Juice</li>
</ul>
```
<ul>
    <li>Coffee</li>
    <li>Teh</li>
    <li>Juice</li>
</ul>

---

### Example (2): Ordered list

```html
<ol>
    <li>Ali</li>
    <li>Benjamin</li>
    <li>Coco</li>
</ol>
```

<ol>
    <li>Ali</li>
    <li>Benjamin</li>
    <li>Coco</li>
</ol>

---

### Example(3): Definition list
```html
<dl>
    <dt>Apple</dt>
    <dd>A type of sweet fruit</dd>
    <dt>Banana</dt>
    <dd>A kind of yellow fruit</dd>
    <dt>Coconut</dt>
    <dd>Outside chocolate inside white</dd>
</dl>
```

<dl>
    <dt>Apple</dt>
    <dd>A type of sweet fruit</dd>
    <dt>Banana</dt>
    <dd>A kind of yellow fruit</dd>
    <dt>Coconut</dt>
    <dd>Outside chocolate inside white</dd>
</dl>

---

### Example(4): Nested list
```html
<ol type="A">
  <li>Coffee
    <ol type="I">
      <li>Mocha</li>
      <li>Expresso</li>
    </ol>
  <li> Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ol>
```

<ol type="A">
    <li>Coffee
        <ol type="I">
            <li>Mocha</li>
            <li>Expresso</li>
        </ol>
    <li> Tea
        <ul>
            <li>Black tea</li>
            <li>Green tea</li>
        </ul>
    </li>
    <li>Milk</li>
</ol>

--- 

## Blockquote
`<blockquote>` or `<quote>` is used to define a section for quotation.

### Example
```html
<p>Here is a quote from XXX</p>
<blockquote>
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
</blockquote>
```

<p>Here is a quote from XXX</p>
<blockquote>
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
bla bla bla bla bla bla bla bla bla
</blockquote>


## Horizontal rule

`<hr>` is used to represent a thematic break between paragraph-level elements. It is typically rendered as a horizontal line.

### Example  
```
<hr>
```
<hr>

The horizontal line above and below  is rendered by `<hr>`.  

<hr>


## Image
Used to insert image into a document.
### Example

```html
<img src="https://pbs.twimg.com/profile_images/972154872261853184/RnOg6UyU_400x400.jpg">
```
<img src="https://pbs.twimg.com/profile_images/972154872261853184/RnOg6UyU_400x400.jpg">



## Style
### Example

```html
<div style="background-color:yellow">
<p style="color:red">This is red</p>
<p style="font-family:courier">I'm courier</p>
<p style="text-align:center">I'm at center</p>
</div>
```

![image](https://user-images.githubusercontent.com/23183656/39173261-da543368-47d6-11e8-82b9-7585beeae06b.png)


## Table
```html
<table>
  <caption>This is a table</caption>
  <thead> 
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Wong</td>
      <td>22</td>
    </tr>
    <tr>
      <td>Lee</td>
      <td>19</td>
    </tr>
  </tbody>
</table>
```
<table>
  <caption>This is a table</caption>
  <thead> 
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Wong</td>
      <td>22</td>
    </tr>
    <tr>
      <td>Lee</td>
      <td>19</td>
    </tr>
  </tbody>
</table>