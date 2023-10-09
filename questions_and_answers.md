<div align="center">
  <img height="60" src="https://edurev.gumlet.io/AllImages/original/ApplicationImages/CourseImages/944e5d47-8c55-4a89-91e5-22ab5f2798fc_CI.png">
  <h1>MCQ TEST</h1>
</div>

###### 1. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let greeting;
greetign = {};
console.log(greetign);
```

- A: `{}`
- B: `ReferenceError: greetign is not defined`
- C: `undefined`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

<i>there's a typographical error in the variable name. It's declared as greeting, but it's assigned as greetign. This will result in a ReferenceError because JavaScript cannot find a variable named greetign.</i>

</p>
</details>

###### 2. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sum(a, b) {
  return a + b;
}

sum(1, "2");
```

- A: `NaN`
- B: `TypeError`
- C: `"12"`
- D: `3`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: C

<i>the sum function takes two parameters a and b and performs addition on them. When you call sum(1, "2"), JavaScript will perform type coercion and convert the number 1 to a string to match the data type of b, which is "2". As a result, the + operator concatenates the two strings, resulting in "12".</i>

</p>
</details>

###### 3. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
const food = ["🍕", "🍫", "🥑", "🍔"];
const info = { favoriteFood: food[0] };

info.favoriteFood = "🍝";

console.log(food);
```

- A: `['🍕', '🍫', '🥑', '🍔']`
- B: `['🍝', '🍫', '🥑', '🍔']`
- C: `['🍝', '🍕', '🍫', '🥑', '🍔']`
- D: `ReferenceError`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

<i>an array food is defined with four emoji elements. Then, an object info is created with a property favoriteFood assigned to the first element of the food array, which is "🍕". However, later in the code, the info.favoriteFood property is reassigned to "🍝". This does not modify the food array. So, when console.log(food) is executed, it will output the original food array, which remains unchanged except for the modification of the info object.</i>

</p>
</details>

###### 4. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sayHi(name) {
  return `Hi there, ${name}`;
}

console.log(sayHi());
```

- A: `Hi there,`
- B: `Hi there, undefined`
- C: `Hi there, null`
- D: `ReferenceError`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

<i>In the sayHi function, there is a parameter name that is expected to be passed when calling the function. However, when you call sayHi() without providing any argument, name is undefined within the function. Therefore, ${name} in the template literal results in "Hi there, undefined" when logged to the console.</i>

</p>
</details>

###### 5. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let count = 0;
const nums = [0, 1, 2, 3];

nums.forEach((num) => {
  if (num) count += 1;
});

console.log(count);
```

- A: 1
- B: 2
- C: 3
- D: 4

<details><summary><b>Answer</b></summary>
<p>

#### Answer: C

<i>The code initializes a variable count to 0 and iterates over the nums array using the forEach method. It checks if each element num is truthy (i.e., not equal to 0), and if it is, it increments the count by 1. Since there are three truthy elements (1, 2, and 3) in the array, the count variable becomes 3, which is logged to the console.</i>

</p>
</details>
