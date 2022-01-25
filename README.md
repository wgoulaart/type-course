# type-course

Mini-curso de Typescript @willianjusten

This repo is a playground about details and exercises of Typescript that i learn :)

## Why use?

Because typescript fix and warning problems on your code, improving your DX(Developer Experience)

```javascript
function sum(number1, number2) {
  return number1 + number2;
}

sum(1, 2); // return 3
sum('1', '2'); // return 12
```

When using TS (TypeScript) on runtime code, the compiler return an error similar this:

```javascript
Errors in code
Parameter 'number1' implicitly has an 'any' type.
Parameter 'number2' implicitly has an 'any' type.
```
