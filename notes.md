# Variables

- var
- let
- const

## let

```javascript
let num1 = 10;
num1 = 20;
console.log("num1 (let):", num1);
```

## const

```javascript
const num2 = 30;
// num2 = 40; // This will throw an error because num2 is declared with const
console.log("num2 (const):", num2);
```

## var

```javascript
var num3 = 50;
num3 = 60; // This is allowed because num3 is declared with var
console.log("num3 (var):", num3);
```

## Mainly We Differentiate it in Scopes

```javascript
{
  let x = 10;
  var y = 20;
  const z = 30;
}

// console.log(x); // This will throw an error because x is declared with let and its scope is limited to the block
console.log("y (var):", y); // This will work because y is declared with var and its scope is not limited to the block
// console.log(z); // This will throw an error because z is declared with const and its scope is limited to the block
```

# Conditions

```javascript
const userLoggedIn = true;

if (userLoggedIn) {
  console.log("Login successful");
} else {
  console.log("User Not Logged In");
}

userLoggedIn
  ? console.log("Login successful")
  : console.log("User Not Logged In");

userLoggedIn && console.log("Login successful");
```

# Looping 

```javascript
let arr = [1, 2, 34, "santhosh", true];

for (let i = 0; i < arr.length; i++) {
  console.log(arr[i]);
}

arr.map((data) => {
  console.log(data);
});

var i = 0;

while(true){
    if(i == arr.length) break;
    console.log(arr[i])
    i++
}


```
