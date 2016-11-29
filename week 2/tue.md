# TUESDAY, NOVEMBER 29TH, 2016



###**OBJECTIVES**
---------------------------------------
+ Introduce Objects
+ Learn about arrays
+ Explore array methods
+ Discuss looping through arrays
+ Learn to use newer array methods


###**ARRAYS**
---------------------------------------
+ Arrays are list-like data types containing comma separated values
+ Useful for storing a sequence of data
+ Delcare arrays with brackets  `[]`
`let friends = ['barry', 'joe', 'riley']`
+ Elements are stored inside an array
+ `arrName[index]`
+ `arrName.indexOf` returns the index of the first occurence of element, or -1 if not found 
+ `myArray.pop()` 
+ [Reference](http://www.w3schools.com/jsref/jsref_obj_array.asp)
+ `array.forEach(function)` executes function for each element in array
+ pass param op
+ callback functions take params
+ map, filter, reduce return new arrays when called
+ `map` method applies a function to each element in array, does not mutate
+ `filter` method returns a new array with elements that have returned to `true` based on certain params
+ `reduce` reduces the array to a single value and execites a provided function for each val of the array (from left to right). The return value of the function is stored in an accumulator(result/total).


###**OBJECTS**
---------------------------------------
+ `let obj1 = {a: 1};`
+ Function values of an object are called object _methods_
+ You can access properties of an object via dot or bracket notation
+ bracket notation: `Math['PI']`
+

Example Object
```
let myObject = {
    x: 4,
    y: 'matata', 
    isMonday: true,
    logHello: function() {
        console.log('hello');
    }
}
```


