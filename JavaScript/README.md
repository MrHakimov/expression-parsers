# Expression parser with Exceptions
Implement classes `Const`, `Variable`, `Add`, `Subtract`, `Multiply`, `Divide` and `Negate` to represent expressions with a single variable. For example the description of the expression `2 * x - 3` should be:
```js
let expr = new Subtract(
    new Multiply(
        new Const(2),
        new Variable("x")
    ),
    new Const(3)
);
```

Also implement methods `toString` and `evaluate`. Add to this classes exceptions processing:
- parsing errors;
- evaluation errors.
