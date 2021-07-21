
ECMAScript is a standardized version of JavaScript with the goal of unifying the language's specifications and features.

## Explore Differences Between the var and let

A new keyword called **let** was introduced in ES6. When using let, a variable with the same name can only be **decalred** once.


##Declare a Read-Only Variable with the const Keyword

Variables declared using **const** are read-only, which means that once a variable is assigned with **const**,it cannot be reassigned.


## Use Destrucring Assignment to Extract Values from Objects

```ES5
const user = { name: 'John Doe', age: 34 };

const name = user.name;
const age = user.age;

```

```ES6
const { name, age } = user;


```

##Use Destructuring Assignment to Assign Variables from Objects

 How to assign a new variable name when extracting values:

```ES6
const{name:userName, age:userAge} = user;
```
Read it as 'get the value of **user.name** and assign it to a new variable named **userName**'.
