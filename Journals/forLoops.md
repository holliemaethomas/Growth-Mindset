# Learning Journal 1.9
## Reading and discussion
### topic: for loops

## A quick look at some for loop examples. 

I like to think of it as "Do this(task) until this is met (condition)

### For example if I am trying to get my 4 year old to pick up his room I might say >Pick up all shoes until there are no more shoes on the floor.

Here are some examples of how to write for loops. 


```var ourArray = [];
var i = 0;
while (i < 5) {
  ourArray.push(i);
  i++;
}

// Count Backwards With a For Loop
var ourArray = [];
for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Iterate Through an Array
var arr = [10, 9, 8, 7, 6];
for (var i = 0; i < arr.length; i++) {
  console.log(arr[i]);
}

// Nested for loops
var arr = [[1, 2], [3, 4], [5, 6]];
for (var i = 0; i < arr.length; i++) {
  for (var j = 0; j < arr[i].length; j++) {
    console.log(arr[i][j]);
  }
}```
