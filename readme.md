## JavaScript Loops ##

- Loops in JavaScript are used to reduce repetitive tasks by repeatedly executing a block of code as long as a specified condition is true. This makes code more concise and efficient.

- Suppose we want to print ‘Hello World’ five times. Instead of manually writing the print statement repeatedly, we can use a loop to automate the task and execute it based on the given condition.

```
 for (let i = 0; i<5; i++) {
    console.log("Hello world!");
} 

```
### 1. JavaScript for Loop
- The for loop repeats a block of code a specific number of times. It contains initialization, condition, and increment/decrement in one line.

**Syntax**

``` 
for (initialization; condition; increment/decrement) {
    // Code to execute
}

```
### 2. JavaScript while Loop
- The while loop executes as long as the condition is true. It can be thought of as a repeating if statement. 

**Syntax**

```
while (condition) {
    // Code to execute
 }
```
```
 let i = 0;
 while (i < 3) {
    console.log("Number:", i);
    i++;
}
```
### 3. JavaScript do-while Loop
- The do-while loop is similar to while loop except it executes the code block at least once before checking the condition.

**Syntax**
```
do {
    // Code to execute
} while (condition);
```
```
let i = 0;
do {
    console.log("Iteration:", i);
    i++;
} while (i < 3);
```
### 4. JavaScript for-in Loop
- The for…in loop is used to iterate over the properties of an object. It only iterate over keys of an object which have their enumerable property set to “true”.

**Syntax**
```
for (let key in object) {
    // Code to execute
}
```
```
const obj = { name: "Ashish", age: 25 };
for (let key in obj) {
    console.log(key, ":", obj[key]);
}
````
### 5. JavaScript for-of Loop
- The for…of loop is used to iterate over iterable objects like arrays, strings, or sets. It directly iterate the value and has more concise syntax than for loop.

**Syntax**
```
for (let value of iterable) {
    // Code to execute
}
```
```
let a = [1, 2, 3, 4, 5];
for (let val of a) {
    console.log(val);
}
```
