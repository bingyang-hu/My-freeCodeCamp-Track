## Understanding Uninitialized Variables
When JS variables are declared, they have an initial value of **undefined**.




## Use Bracket Notation to Find the First Character in a String

**Zero-based indexing**

```
var firstLetterOfLastName = "";
var lastName = "Lovelace";

firstLetterOfLastName = lastName[0];


```

## Manipulate Arrays With push()

**.push()** takes one or more parameters and pushes them onto the end of the array.
```
var arr2 = ["Stimpson","J","cat"];

arr2.push(["happy","joy"]);

// arr2 now: ["Stimpson","J","cat",["happy","joy"]];

var myArray = [["John", 23], ["cat", 2]];

myArray.push(["dog",3]);


```

## Manipulate Arrays With pop()
**.pop()** removes the last eement from an array and returns that element.

## Manipulate Arrays with Shift()

It works just like **.pop()** except it removes the first element instead of the last one.

## Manipulate Arrays with unshift()


## Global Scope and Functions

Variables which are defined outside of a function block have **Global** scope.

Variables which are used without the **var** keyword are automatically created in the global scope.
