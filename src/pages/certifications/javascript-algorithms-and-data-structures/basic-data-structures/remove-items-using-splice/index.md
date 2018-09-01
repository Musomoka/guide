---
title: Remove Items Using splice()
---
## Remove Items Using splice()

<p>The solution requires that you remove an item at a time.
  <br/>
1. use splice to remove one of the numbers within the array
<br/>
2. Use either splice or pop or shift to remove any number to result in the reduce method returning a sum of 10.
</p>
<h3>solution</h3>
<code>
 function sumOfTen(arr) {
  // change code below this line
  arr.splice(1,1);
  arr.pop();
  // change code above this line
  return arr.reduce((a, b) => a + b);
}

// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1])); 
 </code>
