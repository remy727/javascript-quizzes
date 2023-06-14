# JavaScript Quizzes

#### Question 1

What is the output of the following code snippet?
```js
const person = { name: "John" };
const proxy = new Proxy(person, {
  get(target, property) {
    return "Hello";
  }
});
console.log(proxy.name);
```

- [ ] John
- [x] Hello
- [ ] `undefined`
- [ ] Error


#### Question 2

What is the output of the following code snippet?
```js
let x = 5;

function updateX(value) {
  x = value;
}

updateX(10);
console.log(x);
```

- [ ] 5
- [x] 10
- [ ] `undefined`
- [ ] Error

#### Question 3

What is the design pattern used to create objects from a base class and provide different implementations?

- [ ] Singleton Pattern
- [ ] Observer Pattern
- [x] Constructor Pattern
- [ ] Strategy Pattern

#### Question 4

Which JavaScript performance optimization technique is used to reduce the number of reflows and repaints?

- [ ] Debouncing
- [ ] Throttling
- [ ] Memoization
- [x] Virtual DOM

#### Question 5

What is the output of the following code in JavaScript?
```js
var x = 1;
function foo() {
  console.log(x);
  var x = 2;
}
foo();
```

- [ ] 1
- [ ] 2
- [x] undefined
- [ ] ReferenceError

#### Question 6

What is the output of the following code?
```js
print(2 * 3 ** 3 / 6)
```

- [ ] 6.0
- [ ] 4.5
- [x] 9.0
- [ ] 18.0

#### Question 7

Which keyword is used to set a breakpoint in JavaScript code?

- [x] debugger
- [ ] console
- [ ] trace
- [ ] break