# JavaScript

## Low-Level debugging
* When in doubt, you can always add an **alert()** to your JavaScript
* The **alert()** function takes a string as a parameter and pauses the JavaScript execution until you press OK.

## Including JavaScript

There are 3 patterns:

* Inline within the document:

```html
<script type="text/javascript">
    alert("Hello, World!");
</script>
```

* As a part of an event in a HTML tag
```html
<button onclick="alert('You clicked the button!');">Click me</button>
```

* From a file
```html
<script src="your_file.js"></script>
```

## Comments
```javascript
// One line

/* 
    Multi-line
*/
```

## Statements
* Ends with a semicolon (;)
* Indentation doesn´t matter

## Arithmetic Operators
```javascript
j = 1
1

j = j + 1
2

j = j - 5
-3

j = j * 3
-9

j = j / 2
-4.5

j = 45
45

k = j % 7
3

k++
4

--k
3

//We also have += , -=, *=, /=
```
## Comparison operators
```javascript
// Most common: ==, !=, <, <=, >=
// === comparison without conversion type
```
## Logical operators
&& -> AND
|| -> OR
! -> NOT

## Concatenation 
You use (+)
example: "hi " **+** "my friend"






