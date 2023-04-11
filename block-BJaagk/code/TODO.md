1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage=(marks,total)=>{
  (marks*100)/total;
}

let percentage = function(marks,total){
  return (marks*100)/total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let percentage = (marks,total)=>{
  (marks*100)/total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); //5(Valid)
five = add; // five becomes function reference of add(valid)
five = five(10, 11); // 21(valid)
five = function () {
  return 'Hello';
}; // this is function reference(valid)
```

6. What is the difference between function definition and function call? Explain with an example.
<!-- Function definition is a structure of a working function while function calling is actually providing necessary parameters to run the function -->
7. What is the similarities between function definition and function call?
<!-- function call is made using parameters provided in function definition. So the necessary factors to run a function are same in function call and function definition -->
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.
<!-- Higher order functions are those which perform operations on other functions
    Example:
    const numbers=[1,2,3,4];
    function addOne(array){
      for(let i=0;i<array.length;i++){
        console.log(array[i] + 1);
      }
    }
    addOne(numbers);
     -->

10. Explain what is callback function. Why you can pass a function inside a function?
<!-- Callback functions are passed as argument to another function.
      When a function is finished then callbacks are passed to follow up.
       -->