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
