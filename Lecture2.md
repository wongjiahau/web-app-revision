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
|`<b>`| Bold  | <b>I'm bold</b>
|`<strong>` | Important  | <strong>I'm strong</strong>
|`<i>` | Italic  | <i>I'm italic</i>
| `<em>` | Emphasized  | <em>I'm emphasized</em>
| `<mark>` | Highlight  | <mark>I'm marked</mark>
| `<del>` | Strikethrough | <del>I'm marked</del>
| `<ins>` | Underline | <ins>I'm underlined</ins>
| `<sub>` | Subscript | X <sub>subscript</sub>
| `<sup>` | Superscript | X <sup>superscript</sup>


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

### Code(1): Unordered list

```html
<ul>
    <li>Coffee</li>
    <li>Teh</li>
    <li>Juice</li>
</ul>
```

### Real look (1)

<ul>
    <li>Coffee</li>
    <li>Teh</li>
    <li>Juice</li>
</ul>

---

### Code (2): Ordered list

```html
<ol>
    <li>Ali</li>
    <li>Benjamin</li>
    <li>Coco</li>
</ol>
```

### Real look (2)

<ol>
    <li>Ali</li>
    <li>Benjamin</li>
    <li>Coco</li>
</ol>

---

### Code(3): Definition list
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

### Real look(3)

<dl>
    <dt>Apple</dt>
    <dd>A type of sweet fruit</dd>
    <dt>Banana</dt>
    <dd>A kind of yellow fruit</dd>
    <dt>Coconut</dt>
    <dd>Outside chocolate inside white</dd>
</dl>