# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram designed to perform a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle, Open  Closed Principle, Liskov Substitution Principle, Interface Segregation Principle, and Dependency Inversion Principle.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, because index begins at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
You can put them.push into the array itself.
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if, else, else if, switch statements are all conditionals.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
It's the incrementor. You would put i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The document object model. The first file called is the html.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
number, boolean, undefined, bigint, string, symbol, null, object, and function.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is what a function asks for when it is called and the argumant is what the user passes into the function. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primiitive values stored are fixed and javascript stores it on the stack and reference values are more dynamic and stores it on the heap. When you work on a primitive value you work on its actual value wheras on reference you are working on an object so you reference the object before you work on it.
```