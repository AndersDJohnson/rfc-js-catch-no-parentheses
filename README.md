# rfc-js-catch-no-parentheses
A proposal for JS `catch` without parentheses.

Similar to the JavaScript arrow function syntax where a function accepting a single argument does not require wrapping parentheses, but for the `catch` keyword:

```js
try {
  // ...
} catch err {
  // ...
}
```

Equivalent to:

```js
try {
  // ...
} catch (err) {
  // ...
}
```
