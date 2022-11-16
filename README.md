# 1. Flat()

### 1. What are the Parameters it accepts:
- The flat function accepts only the depth parameter.

### 2. What it will return:
- It returns a new array with all the sub-array elements merged into it.

### 3. Example:
<!-- 3 nested arrays --> 
```
let numbers = [1, 2, [3, 4, [5, 6, [7, 8]]]];\
let flattenArray = numbers.flat(2);\
console.log(flattenArray);\
Output: [ 1, 2, 3, 4, 5, 6, [ 7, 8 ] ]
```
### 4. Meaning:
- The flat() method returns an array after concatenating all the subarray elements at the specified depth. By default, the Flat method goes only one level deep,means it will not flat nested of nested array.
### 5. Does it mutate the original array:
- NO



# 2. Concat()

### 1. What are the Parameters it accepts:
- Concat accepts any number of parameters, which can be of any type.

### 2. What it will return:
- It will return New Array.

### 3. Example:

```
var str1 = "Example of ";
var str2 = "Javascript ";
var str3 = "String Concatenation";
var res = str1.concat(str2, str3);
console.log(res); 
```
### 4. Meaning:
- It simply adds the values we gave to the initial array or merges two arrays and provides a new array.
### 5. Does it mutate the original array:
- No




# 3. Push()

### 1. What are the Parameters it accepts:
- Push accepts any number of parameters, which can be of any type.

### 2. What it will return:
- The push() method adds one or more elements to the end of an array and returns the new length of the array.

### 3. Example:
```
const box = ['pen', 'paper', 'scale'];
box.push('pencil');
console.log(box);
output: ["pen", "paper", "scale", "pencil"]
```
### 4. Meaning:
- It adds one or more elements to the end of an array and returns the new length of the array.
### 5. Does it mutate the original array:
- Yes




# 4. Pop()

### 1. What are the Parameters it accepts:
- It accepts a single parameter, which is index (optional): The pop() function accepts only one parameter: the item's index to be popped out from the list. If the index is not mentioned, it removes the last item from the list.

### 2. What it will return:
- It returns the last element which is popped out of the original array.

### 3. Example:
```
let arr = [1,2,3];
console.log(arr.pop());
console.log(arr); 
// [1,2]
```

### 4. Meaning:
- It pops out the last element from the given array.
### 5. Does it mutate the original array:
- Yes.


# 5. Shift()

### 1. What are the Parameters it accepts:
- This method does not accept any parameter.

### 2. What it will return:
- It returns the first element that has been removed from the array.


### 3. Example:
```
let arr = [2,3,4]
console.log(arr.shift()); 
// 2
```
### 4. Meaning:
- It removes the first element from the given array.
### 5. Does it mutate the original array:
- Yes




# 6. Unshift()

### 1. What are the Parameters it accepts:
- It accepts any number of parameters.

### 2. What it will return:
- It return the length of the updated array.

### 3. Example:
```
let arr = [1,2,3];
arr.unshift(4,5,6,7,8)
console.log(arr.unshift(4,5,6,7,8)); // 8
console.log(arr) = [4,5,6,7,8,1,2,3];
```
### 4. Meaning:
- This method updating the array by adding the given values at the beginning of the array.
### 5. Does it mutate the original array:
- Yes

# 7. IndexOf()

### 1. What are the Parameters it accepts:
It accepts two parameters - 
- substring - It is the substring that you want to find within string.
- start_position (Optional) - It is the position in string where the search will start. The first position in string is 0. If this parameter is not provided, the search will start at the beginning of string and the full string will be searched.

### 2. What it will return:
- The indexOf() method returns the position of the first occurrence of substring in string. The first position in the string is 0. If the indexOf() method does not find the substring in string, it will return -1.

### 3. Example:
```
let arr = [1,2,3];
console.log(arr.indexOf(3)); // 2
```
### 4. Meaning:
- IndexOf() is a string method that is used to find the location of a substring in a string
### 5. Does it mutate the original array:
- No

# 8. LastIndexOf()

### 1. What are the Parameters it accepts:
It accepts two parameters
- substring - It is the substring that you want to find within string.
- start_position (Optional) - It is the position in string where the search will start. The first position in string is 0 and the last position in string is string.length-1. If this parameter is not provided, the search for substring begins at the end of string and the full string is searched.


### 2. What it will return:
- The lastIndexOf() method returns the position of the first occurrence of substring in string when searching the string backwards. The first position in the string is 0.

If the lastIndexOf() method does not find the substring in string, it will return -1.

### 3. Example:
```
var string = 'Internet';
console.log(string.lastIndexOf('t'));
// 7
```
### 4. Meaning:
- LastIndexOf() is a string method that is used to find the location of a substring in a string, searching the string backwards.
### 5. Does it mutate the original array:
- No.



# 9. Includes()
### 1. What are the Parameters it accepts:
It accepts two parameters.
- substring
It is the substring that you want to search for within string.
- start_position (Optional) - It is the position in string where the search will start. The first position in string is 0. If this parameter is not provided, the search will start at the beginning of string.

### 2. What it will return:
- It returns either true or false.

### 3. Example:
```
var string = 'internet';
console.log(string.includes('e'));
// true
```
### 4. Meaning:
- This method searches the array for given value if the array contains that value it will return true either false.
### 5. Does it mutate the original array:
- No


# 10. Reverse()
### 1. What are the Parameters it accepts:
- It does not have any parameters.

### 2. What it will return:
- It will reverses the entire array and returns it.

### 3. Example:
<!--  --> 
```
let arr = [7,8,6];
console.log(arr.reverse()); 
// [6,8,7];
```
### 4. Meaning:
- It reverses the entire array in place.
### 5. Does it mutate the original array:
- Yes.


# 11. Splice()
### 1. What are the Parameters it accepts:
- It conclude start parameter, delete count parameter and the elements that we want to add on start index.

### 2. What it will return:
- It return an array containing the deleted elements.

### 3. Example: 
```
let colors = ['red', 'green', 'blue'];
colors.splice(2, 0, 'purple');
console.log(colors); 
// ["red", "green", "purple", "blue"]
```
### 4. Meaning:
- splice() method use to delete existing elements, insert new elements, and replace elements in an array.
### 5. Does it mutate the original array:
- Yes


# 12. Slice()
### 1. What are the Parameters it accepts:
- The slice() method has two optional parameters start and end.

### 2. What it will return:
- It returns a new array which has all the elements extracted from the start to end.

### 3. Example:
```
const str = 'Hello';
const substr = str.slice(-3);
console.log({ substr });
// { substr: 'llo' }
```
### 4. Meaning:
- This method slice the given array at the start and at the end and returns that part as a new array.
### 5. Does it mutate the original array:
- No.


# 13. ForEach()
### 1. What are the Parameters it accepts:
- The forEach() method takes a parameter callback, which is a function that JavaScript will execute on every element in the array.

### 2. What it will return:
- Undefined.

### 3. Example:
```
const arr = [1, 'two',];
arr.forEach(item => console.log(item));

// Expected output:
// 1 
// two
```
### 4. Meaning:
- It iterates through the entire array passing each element to the function.
### 5. Does it mutate the original array:
- No.



# 14. Map()

### 1. What are the Parameters it accepts:
- This method takes one essential parameter which is callback function and an optional parameter where we can pass 'this'.

### 2. What it will return:
- A new array where each element is obtained by passing the elements of the original array to the function.


### 3. Example:
```
const numbers = [1, 2, 3, 4, 5]
const squared = numbers.map(num => num * num)

console.log(squared)

// [1, 4, 9, 16, 25]
```
### 4. Meaning:
- The map() method use to make your code shorter and more concise. It iterates through the array passes the elements to the callback function and puts the return value into a new array.
### 5. Does it mutate the original array:
- No.


# 15. Filter()

### 1. What are the Parameters it accepts:
callbackFunction is a predicate, to test each element of the array. Return true to keep the element, otherwise false. It accepts three arguments- 
- element - The current element being processed in the array.

- index(Optional) - The index of the current element being processed in the array.

- array(Optional) -  The array filter was called upon.

- thisArg(Optional) - Value to use as this when executing callback.

### 2. What it will return:
- A new array with the elements that pass the test. If no elements pass the test, an empty array will be returned.

### 3. Example:
```
const numbers = [2, 4, 6, 8, 32, 100]
const functionToFilterNumbers = function(number){
 return number > 5;
}
const filtered = numbers.filter(functionToFilterNumbers)
console.log(filtered)
// Output: [6,8,32,100]
```
### 4. Meaning:
- It will take a test function and returns a new array containing the elements that matches the set test. Either returns an empty array if there are no matches.
### 5. Does it mutate the original array:
- No.

# 16. Find()
### 1. What are the Parameters it accepts:
- It accepts a callback function as a parameter.

### 2. What it will return:
- The first element in the array which results in true when passed to the callback function. If no element returns true it return undefined.

### 3. Example:
```
const colors = [
  "blue",
  "grey",
  "pink",
  "violet"
];

console.log(colors.find(color => color.startsWith("g")));

// OUTPUT: grey
```
### 4. Meaning:
- The find() method returns the value of the first element that passes a test. The find() method executes a function for each array element. The find() method returns undefined if no elements are found. The find() method does not execute the function for empty elements.
### 5. Does it mutate the original array:
- No.


# 17. FindIndex()

### 1. What are the Parameters it accepts:
- It accepts a callback function as a parameter.

### 2. What it will return:
- The findIndex() method returns the index of the first element in an array that satisfies the provided testing function. If no elements satisfy the testing function, -1 is returned.

### 3. Example:
```
var arr = [ -10, -5, 0, 5, 10 ];

function greater_than_zero(ele) {
   return ele > 0;
}
console.log(arr.findIndex(greater_than_zero));
// Output = 3
```
### 4. Meaning:
- The findIndex() method executes a function for each array element. It returns the index (position) of the first element that passes a test and it returns -1 if no match is found. It does not execute the function for empty array elements.
### 5. Does it mutate the original array:
- No.


# 18. Some()

### 1. What are the Parameters it accepts:
- This method accept the callback function as its first parameter and this as an optional parameter.


### 2. What it will return:
- This method returns true if atleast one element passes in the given condition otherwise it will return false.

### 3. Example:
```
function isEven(element) {
  return element % 2 === 0;
}
let numbers = [1, 3, 2, 5, 4];
console.log(numbers.some(isEven));

// Output: true 
```
### 4. Meaning:
- The some() method checks if any array elements pass a test (provided as a callback function).
### 5. Does it mutate the original array:
- No.



# 19. Every()

### 1. What are the Parameters it accepts:
- callback - It represents the function that test the condition.

- currentvalue - The current element of array.
Play Video

- index - It is optional. The index of current element.

- arr - It is optional. The array on which every() operated.

- thisArg - It is optional. The value to use as this while executing callback.

### 2. What it will return:
- A boolean value.
It returns true if every element returns true when passed to the callback function otherwise false.

### 3. Example:
```
let numbers = [1, 3, 5];
let result = numbers.every(function (e) {
    return e > 0;
});

console.log(result);
// Output: true
```
### 4. Meaning:
- The every() method executes a function for each array element. The every() method returns true if the function returns true for all elements. The every() method returns false if the function returns false for one element.
### 5. Does it mutate the original array:
- No.


# 20. Sort()

### 1. What are the Parameters it accepts:
- It takes an optional comparision function as a parameter.

### 2. What it will return:
- Returns the array after sorting the elements of the array in place (meaning that it changes the original array and no copy is made).

### 3. Example:
```
let city = ["Ajmer", "Delhi", "Bengaluru", "Mumbai"];

let sortedArray = city.sort();
console.log(sortedArray);

// Output: [ 'Ajmer', 'Bengaluru', 'Delhi', 'Mumbai' ]
```
### 4. Meaning:
- The sort() sorts the elements of an array. The sort() overwrites the original array. The sort() sorts the elements as strings in alphabetical and ascending order. Means the default sort order is ascending, built upon converting the elements into strings, then comparing their sequences of UTF-16 code units values.

### 5. Does it mutate the original array:
- Yes.


# 21. Reduce()

### 1. What are the Parameters it accepts:
- It takes two parameters one is callback function and the other is accumulator value.

### 2. What it will return:
- The reduce() method returns a single value: the function's accumulated result. It does not execute the function for empty array elements and it does not change the original array also.

### 3. Example:
```
const message = ["Mountblue ", "is ", "Awesome."];

// function to join each string elements
function joinStrings(accumulator, currentValue) {
  return accumulator + currentValue;
}
// reduce join each element of the string
let joinedString = message.reduce(joinStrings);
console.log(joinedString);

// Output: Mountblue is Awesome.
```
### 4. Meaning:
- This method is used to reduce the array to a single value and executes a provided function for each value of the array (from left-to-right) and the return value of the function is stored in an accumulator.

### 5. Does it mutate the original array:
- No.
