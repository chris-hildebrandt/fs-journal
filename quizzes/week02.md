# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
"var", "const", and "let".
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID stands for:

S - Single-responsibility Principle: A class should have one and only one reason to change, meaning that a class should have only one job.

O - Open-closed Principle: Objects or entities should be open for extension but closed for modification.

L - Liskov Substitution Principle: Every subclass or derived class should be substitutable for their base or parent class.

I - Interface Segregation Principle: A client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use.

D - Dependency Inversion Principle: Entities must depend on abstractions, not on concretions. It states that the high-level module must not depend on the low-level module, but they should depend on abstractions.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
the current position is 2 because arrays begin at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
them.friends.forEach(friend => {
  you.friends.push(friend)
}

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark (?), then an expression to execute if the condition is truthy followed by a colon (:), and finally the expression to execute if the condition is falsy. This operator is frequently used as an alternative to an if...else statement.

function getFee(isMember) {
  return (isMember ? '$2.00' : '$10.00');
}

console.log(getFee(true));
// expected output: "$2.00"

console.log(getFee(false));
// expected output: "$10.00"

console.log(getFee(null));
// expected output: "$10.00"
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the blank space should contain the "iterator" or "iteration" and should be i++ to increase by one each iteration.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, and the first file to be accessed is the index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
the parameter describes the input that a function is looking for.
the argument is the information we supply when we call the function, in essence it is the information going into the function while the parameter is assigned to the function directly.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are "simple" in that they do not have properties, just values, they include:
"strings"
numbers
booleans
undefined
null

objects and arrays are collections of data

arrays store information by index or position and the data is stored in order

objects store information by key/value pairs and information is unordered
```