1️⃣ What is the difference between var, let, and const?
answer:
var, let and const are JavaScript variables. Before ES6, only var was used. Later, let and const were introduced.

Features of var i. Var is the old JavaScript variable. ii. Var can be accessed anywhere, but not outside the function scope. iii. Var is hoisted. iv. Var can be redeclared. v. Var can be reassigned.

Features of let i. Let is used in modern JavaScript. ii. Let has block scope. It cannot be accessed outside {}. iii. Let is hoisted but stays in the Temporal Dead Zone (TDZ) until declared. iv. Let cannot be redeclared. v. Let can be reassigned.

Features of const i. Const is used in modern JavaScript. ii. Const has block scope. It cannot be accessed outside {}. iii. Const is hoisted but stays in the Temporal Dead Zone (TDZ) until declared. iv. Const cannot be redeclared. v. Const cannot be reassigned, but values inside objects and arrays can be changed.
2️⃣ What is the spread operator (...)?
answer:
In modern JavaScript, the spread operator is used to spread out the elements of an object or array. It is also used as the rest operator. Depending on the use case, it is called spread operator or rest operator.

Why do we use it?

To merge two arrays into a new array.
To copy an array and create a new array.
To separate an object and create a new object.
To create two new objects.
In a function, when parameters are fixed but arguments are more, the extra arguments can be passed using the rest operator.
3️⃣ What is the difference between map(), filter(), and forEach()?
answer:
map(), filter(), and forEach() are JavaScript array methods.

<---1: map()--> The purpose of map() is to work on each element of an array and return a new array.

Why do we use map()?

To modify the data of an array and create a new array.
To modify the data of objects and create a new array.
<---2: filter()--> The purpose of filter() is to select elements from an array based on a specific condition and create a new array.

Advantages of filter():

It allows easy selection of elements according to a condition.
The original array does not change.
The code is short and readable.
<---3: forEach()--> forEach() is mainly used for looping through an array.

It works on each element of the array.
It does not create a new array
It can update the values of the array.
4️⃣ What is an arrow function?
answer:
Arrow function is the new and modern syntax of JavaScript. It is mainly used to write less code.

Old syntax: function add(x, y){ return x + y; } console.log(add(5, 6));

New syntax: const add = () => { return a + b; } console.log(add(7, 9));

Two arguments Note: If written in a single line, return is not needed. const add = (a, b) => a + b; console.log(add(7, 3));

One argument const divide = s => s / 3; console.log(divide(9));

5️⃣ What are template literals?
answer:
Template literals are the modern syntax of JavaScript. Their sign is ``(backticks). Writing code with old strings ('' or "") was very troublesome. If spaces were not correct, the code would not display properly in the output. Later, template literals solved this problem.

Advantages of template literals:

Variables or expressions can be written inside ${variable}.
Multiple lines of strings can be written easily.
Code becomes shorter and cleaner.
Works well for dynamically creating HTML.
