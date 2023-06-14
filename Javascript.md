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
