## Add Items to an Array with push() and unshift()
**push()** method adds elements (one or more) to the end of an array.
**unshift()** method adds elements to the beginning.

```
function mixedNumbers(arr) {
  // Only change code below this line
arr.push(7,'VIII',9);
arr.unshift('I',2,'three');
  // Only change code above this line
  return arr;
}

console.log(mixedNumbers(['IV', 5, 'six']));

```

## Remove Items from an Array with pop() and shift()

```
function popShift(arr) {
  let popped = arr.pop(); // Change this line
  let shifted = arr.shift(); // Change this line
  return [shifted, popped];
}

console.log(popShift(['challenge', 'is', 'not', 'complete']));


```




## Remove Items Using splice()

**splice()**'s first parameter repsetns the index on the array from which to begin removing elements while the second parameter indicates the number of elements to delete.

```
let array = ['today','was','not','so','great'];

array.splice(2,2);

```

splice() returns a new array containing the value of the removed elements.


## Add Items Using splice()

The third parameter can be used to add elements (one or more) to the array.

```
function htmlColorNames(arr) {
  // Only change code below this line
arr.splice(0,2,'DarkSalmon','BlanchedAlmond');
  // Only change code above this line
  return arr;
}

console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurquoise', 'FireBrick']));``


```

Note there can be any number of elements to be added. Not just one.

## Copy Array Items Using slice()

**slice()** copies or extracts a given number of elements to a new array, leaving the array it is called upon untouched.
```
function forecast(arr) {
  // Only change code below this line
 var new_arr = arr.slice(2,4);
  return new_arr;
}

// Only change code above this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));





```

## Check For The Presence of an Element With indexOf()

## Iterate Through All an Array's Items Using For Loops

```
function filteredArray(arr, elem) {
  let newArr = [];
  // Only change code below this line
  for(var i = 0; i<arr.length ; i++){

      if(arr[i].indexOf(elem)== -1){
        newArr.push(arr[i]);
      }


  }
  // Only change code above this line
  return newArr;
}

console.log(filteredArray([[3, 2, 3], [1, 6, 3], [3, 13, 26], [19, 3, 9]], 3));


```
