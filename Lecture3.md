# Lecture 3 : CSS
## Where to put style?
Inside `<head>`.
```html
<html>
  <head>
    <style>
      p {
        color: red;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>

```


## Selectors
There are 3 selectors: 
- By element
- By ID
- By class
```html
<html>
  <head>
    <style>
      div { /* by element*/
        color: red;
        text-align: center;
      }

      #p2 { /* by ID */
        color: blue;
      }

      .banana { /* by class */
        color: yellow;
      }

      h1, h2, p { /* Grouping*/
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <div>Hello world!</div>
    <p id="p2">Hello world!</p>
    <p class="banana">Hello world!</p>
  </body>
</html>
```


## How to import CSS from another file? (External style)
```html
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
```

## How to use inline css?
```html
<p style="color:red;text-align:center;">Hello world!</p>
```

## Colors in CSS
Colors in CSS can be specified by : 
|Type|Example1|Example2|
|--|--|--|
|name|`red`|`green`|
|RGB value|`rgb(0,0,0)`|`rgb(255,255,255)`|
|Hex value|`000000`|`FFFFFF`|

### Example 
```css
#div1 {
  color: red;
}

#div2 {
  color: rgb(233,100,0);
}

#div3 {
  color: A2BCE3;
}
```
## Background properties
```css
div {
  background-color: blue;
  background-image: url("hello.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```
