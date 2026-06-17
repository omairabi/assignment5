1️⃣ What is the difference between var, let, and const?
answer:
var, let and const are JavaScript variables. Before ES6, only var was used. Later, let and const were introduced.
1:var i. Var is the old JavaScript variable. ii. Var can be reassigned.
2:let i. Let is used in modern JavaScript. ii. Let can be reassigned.
3:const i. Const is used in modern JavaScript. ii. Const is hoisted but stays in the Temporal Dead Zone (TDZ) until declared.

2️⃣ What is the spread operator (...)?
answer:
In modern JavaScript, the spread operator is used to spread out the elements of an object or array. It is also used as the rest operator. Depending on the use case, it is called spread operator or rest operator.

3️⃣ What is the difference between map(), filter(), and forEach()?
answer:
map(), filter(), and forEach() are JavaScript array methods.

1: map()--> The purpose of map() is to work on each element of an array and return a new array.
2: filter()--> The purpose of filter() is to select elements from an array based on a specific condition and create a new array.
3: forEach()--> forEach() is mainly used for looping through an array.

4️⃣ What is an arrow function?
answer:
Arrow function is the new and modern syntax of JavaScript. It is mainly used to write less code.
Old syntax: function add(x, y){ return x + y; } console.log(add(5, 6));
New syntax: const add = () => { return a + b; } console.log(add(7, 9));
Two arguments Note: If written in a single line, return is not needed. const add = (a, b) => a + b; console.log(add(7, 3));

5️⃣ What are template literals?
answer:
Template literals are the modern syntax of JavaScript. Their sign is ``(backticks). Writing code with old strings ('' or "") was very troublesome. If spaces were not correct, the code would not display properly in the output. Later, template literals solved this problem.
