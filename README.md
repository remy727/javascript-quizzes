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

What is the output of the following code snippet?
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

What is the output of the following code snippet?
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

#### Question 8

What is the output of the following code snippet?

```js
const nums =[1,2,3]
console.log(nums.length - -1)
```

- [x] 4
- [ ] 2
- [ ] error

#### Question 9

See the below function. What will be the alert?

```js
for (var i = 0; i < 3; i++) {
  setTimeout(function() { alert(i); }, 1000 + i);
}
```

- [ ] 1,2,3 will alert
- [ ] 3 will alert 3 times
- [ ] Only 3 will alert
- [ ] 2,3 will alert

#### Question 10

What is the output of the following code snippet?
```js
console.log(2+(5*2)-6*5&&"false"!=="false">2&&7>=16||true>=1||4)
```

- [ ] false
- [ ] 4
- [ ] NaN
- [x] true

#### Question 11

In JavaScript, the value of the this keyword is determined by:
(In below option T refers to function)

- [ ] Scope where the T is defined.
- [ ] Scope where the T is called.
- [ ] Object on which T is defined.
- [x] Object on which T is called.