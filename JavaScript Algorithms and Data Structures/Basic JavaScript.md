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


## Testing Objects for Properties

We can use **.hasOwnProperty(propname)** method of objects to determine if that object has the given property name.

```
function checkObj(obj, checkProp) {
  // Only change code below this line
  if (obj.hasOwnProperty(checkProp) ==true){
    return obj[checkProp];
  } else {
    return "Not Found";
  }

  return "Change Me!";
  // Only change code above this line
}


```

Notes:
+ Use return obj[checkProp] rather than obj.checkProp because checkProp here is already string.

```
var myObj = {top: "hat", bottom:"pants"};
myObj["top"]   
myObj.top

```


## Record Colletion
```
function updateRecords(object, id, prop, value) {
  if(prop !== 'tracks' && value !== ""){
    object[id][prop] = value;}
   else if (prop === 'tracks' && !object[id].hasOwnProperty('tracks')){
    object[id][prop] = [value];
  } else if (prop === 'tracks' && value !== ''){
    object[id][prop].push(value);
  } else if (value === ""){
    delete object[id][prop];
  }
  return object;
}

updateRecords(collection, 5439, 'artist', 'ABBA');

```

when check whether it's an empty string, just use !="", there is no space between two double quotes!
