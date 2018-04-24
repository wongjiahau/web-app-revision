# Lecture 4 : Javascript  

## How to find elements?
```js

//By id
var div1 = document.getElementById("div1");

//By tag name
var allDivs = document.getElementsByTagName("div");

//By class name
var pinkDivs = document.getElementsByClassName("pink");

//Using css selector
var x = document.querySelectorAll("p.intro");
```


## Changing content of HTML elements
### 1. Changing inner HTML
```js
element.innerHTML = "<p>Example</p>";
```

### 2. Change attribute value
```js
var myImg = document.getElementsByTagName("img")[0];

//Method 1
myImg.src = "xxx";

//Method 2
myImg.setAttribute("src", "xxx");
```

### 3. Changing style
```js
element.style.property = "newvalue";
```

