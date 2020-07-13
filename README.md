# Intro

1. Copy + paste each of the code segments below into a new file whose filename ends with `.js`, e.g., `example1.js`, `example2.js`
1. Make a prediction about what the code will print out when run
1. Use `node` to run it, e.g., `node example1.js`
1. Modify the code to isolate the parts that don't make sense of you and run little scientific experiments to learn

```js
console.log('Hello, world!');
console.log('This is your first JavaScript program.');
console.log(''); // A blank line
console.log('We\'re going to learn about five core concepts:');
console.log('1. Variables & Data Types');
console.log('2. Branching / Conditionals');
console.log('3. Iteration / Looping');
console.log('4. Collections');
console.log('5. Functions');
```

```js
console.log('1. Hello! Here are some facts about me.');

firstName = 'Jesse';
age = 36;

console.log(`2. My name is ${firstName} and I am ${age} years old.`);
```

```js
console.log('1. Hello! Here are some facts about me.');

firstName = 'Jesse';
age = 36;

school = 'University of Chicago';
major = 'mathematics';
graduationYear = 2006;

console.log(`2. My name is ${firstName} and I am ${age} years old.`);
console.log(`3. I am graduating from ${school} in ${graduationYear}.`);
console.log(`4. I am studying ${major}.`);
```

```js
console.log('1. Hello! Let\'s play with variables.');
console.log(); // Blank line

count = 47;
message = 'Waffles are great';

console.log(`2. At first, the value of count is: ${count}`);
console.log(`3. At first, the value of message is: ${message}`);
console.log(); // Blank line

count = 923;

console.log(`4. After 1st change, the value of count is: ${count}`);
console.log(`5. After 1st change, the value of message is: ${message}`);
console.log(); // Blank line

message = 'Beep beep I am a jeep';

console.log(`6. After 2nd change, the value of count is: ${count}`);
console.log(`7. After 2nd change, the value of message is: ${message}`);
console.log('8. Bye!');
```

```js
console.log('1. Hello! Let\'s play with variables (again).');
console.log(); // Blank line

count = 47;

console.log(`2. At first, the value of count is: ${count}`);

count = count + 1;
console.log(`3. After, the value of count is: ${count}`);

count = count + 1;
console.log(`4. Now, the value of count is: ${count}`);

count = count - 11;
console.log(`4. Now, the value of count is: ${count}`);
```
