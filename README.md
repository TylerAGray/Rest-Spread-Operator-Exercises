# Rest-Spread-Operator-Exercises
## **Given this function:**

```jsx
function filterOutOdds() {
  var nums = Array.prototype.slice.call(arguments);
  return nums.filter(function(num) {
    return num % 2 === 0
  });
}
```

## **Refactor it to use the rest operator & an arrow function:**

## **findMin**

Write a function called findMin that accepts a variable number of arguments and returns the smallest argument.

## **mergeObjects**

Write a function called ***mergeObjects*** that accepts two objects and returns a new object which contains all the keys and values of the first object and second object.

## **doubleAndReturnArgs**

Write a function called ***doubleAndReturnArgs*** which accepts an array and a variable number of arguments. The function should return a new array with the original array values and all of additional arguments doubled.

## **Slice and Dice!**

For this section, write the following functions using rest, spread and refactor these functions to be arrow functions!

Make sure that you are always returning a new array or object and not modifying the existing inputs.
