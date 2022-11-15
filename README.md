# flat


### 1. What are the Parameters it accepts:
- The flat function accepts only the depth parameter.

### 2. What it will return:
- It returns a new array with all the sub-array elements merged into it.

### 3. Example:
<! 3 nested arrays >
let numbers = [1, 2, [3, 4, [5, 6, [7, 8]]]];

reducing nesting by flattening the array to depth 2 
let flattenArray = numbers.flat(2);

 new flatten array
console.log(flattenArray);

Output:
[ 1, 2, 3, 4, 5, 6, [ 7, 8 ] ]
### 4. Meaning:
-
### 5. Does it mutate the original array:
-

