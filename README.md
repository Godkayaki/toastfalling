# toastfalling
Just a neverending falling toast.

## What is this
As the title and description says, this is a counter for how many times the toast has fallen.

## How it works
```javascript
var number = 0;

function increment() {
    number++;
    showNumber(number);
}

function showNumber(num) {
    document.getElementById("displayDiv").innerHTML = num;
}

window.onload = function() {
    setInterval("increment()", 5000);
    showNumber(number);
}

```

## Webpage
https://godkayaki.github.io/toastfalling/
