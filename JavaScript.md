
## Variable declaration.

Use `camelCase` convention over `snake_case`.

```js
// Bad example.
var stars_counter = 10;

// Good example.
var starsCounter = 10;
```

## Function declaration.

Add a space after function closing parenthesis.


```js
// Bad example.
function baz(fum, bar){
    // Do stuff...
}

// Good example.
function baz(fum, bar) {
    // Do stuff...
}
```

Use `this` within jQuery callbacks to reffer to current element.

```js
// Bad example.
$('a').click(function(e) {
    $(e.target).hide();
});

// Good example.
$('a').click(function(e) {
    $(this).hide();
});

```

