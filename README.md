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
