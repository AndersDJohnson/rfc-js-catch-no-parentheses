# rfc-js-catch-no-parentheses
A proposal for JS `catch` without parentheses.

Related to https://github.com/tc39/proposal-optional-catch-binding.

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
