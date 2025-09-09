

1) What is the difference between var, let, and const?
Ans:var is the old way of declaring variables and is function-scoped, which can cause unexpected bugs. let is block-scoped and doesn’t allow redeclaration, making it safer. const is also block-scoped, but once a value is assigned you cannot reassign it (though arrays/objects can still be modified). In modern JavaScript, let and const are preferred, and var is mostly avoided.

2) What is the difference between map(), forEach(), and filter()?
Ans:All three of these methods loop through arrays, but they serve different purposes.
forEach() is simple: it just goes through each item in the array and runs your function. It doesn’t return anything useful, just executes side effects like printing values.
map() is used when you want to transform an array into a new array. For example, doubling every number in an array and returning the new set of numbers. The important thing is map() always returns a new array of the same length.
filter() is used when you want to pick certain elements from an array that match a condition. For example, from a list of numbers, you might filter out only the even ones. It also returns a new array, but the length may be shorter depending on the condition.

3) What are arrow functions in ES6?
Ans:Arrow functions are a shorter way to write functions. For example, (a, b) => a + b is the same as a normal function that returns a + b. They also don’t have their own this, which makes them easier to use in callbacks and object methods.

4) How does destructuring assignment work in ES6?
Ans:Destructuring lets you unpack values from arrays or objects into separate variables in a single line. For example, const {name, age} = person; pulls out both properties without writing them one by one. It makes code shorter and cleaner.

5) Explain template literals in ES6. How are they different from string concatenation?
Ans:Template literals use backticks (`) instead of quotes and let you insert variables with ${}. For example: Hello, ${name} is simpler than "Hello " + name. They also support multi-line strings, which makes them more powerful than regular string concatenation.