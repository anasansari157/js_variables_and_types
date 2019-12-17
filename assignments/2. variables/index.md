1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";

'name' is a variable.
```

2. Find the error if any
```js
  var product cost = 3.45;

Space between 'product' and 'cost' in variable "product cost".
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"  -Right
  'Hello World"  -Wrong
  "Hello World'  -Wrong
  'Hello World'  -Right
```


## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;  -`VALID`
var 1girl;  -`INVALID`
var woman3; -`VALID`
var -girl;  -`INVALID`
var blackDog; -`INVALID`
var 42; -`INVALID`
var $42;  `VALID`
var userName; `VALID`
var x, y, z;  `INVALID`
var x = 5, y = 6, z = 7;  `INVALID`
var x = 5 + 10 + 2; `INVALID`
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
let less80 = amount - 80;
// Define a new variable and store the value that is 200 more then the value of amount.
let more200 = amount + 200;
// Define a new variable and store the value that is 4 times the value of amount.
let times4 = amount * 4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
let divide = amount / 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if (johnAge < markAge) {
  console.log("Mark");
}
else if (johnAge > markAge){
  console.log("John");
}
else {
  console.log("Both ages are equal");
}

// Check who is younger
if (johnAge > markAge) {
  console.log("Mark");
}
else if (johnAge < markAge){
  console.log("John");
}
else {
  console.log("Both ages are equal");
}

// Check if their age is equal
if (johnAge === markAge) {
  console.log("Their age is equal");
}
else {
  console.log("Their age is not equal");
}

// Create a new variable and assign the age of john to new variable.
let newAge = johnAge;

// Check if john is equal to or greater then mark.
if (johnAge > markAge) {
  console.log("John's age is greater than Mark's age");
}
else if (johnAge === markAge) {
  console.log("Their age is equal");
}
else {
  console.log("john is neither equal to nor greater then mark")
}

// Check if john is less then or equal to mark.
if (johnAge < markAge) {
  console.log("John's age is less than Mark's age");
}
else if (johnAge === markAge) {
  console.log("Their age is equal");
}
else {
  console.log("john is neither equal to nor less then mark")
}

// Calculate the average age of john and mark and assign to a new variable.
let avg = (johnAge + markAge) / 2; 
