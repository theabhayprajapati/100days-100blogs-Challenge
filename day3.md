
```javascript
console.time('time')
console.log('Hello World')
console.timeEnd('time')
// Hello World
// time: 7.991ms
```

Here in JavaScript we are having cool method called as `console.time` and `console.timeEnd` which is used to measure the time taken to execute a piece of code.

<!-- list the process to use it. -->
1. start with writing the code in **`console.time('time')`**, here are **"time"** is the name of the variable which we will use to store the time taken to execute the code
1. Start writing your **complex** code in **`console.log('Hello World')`**
2. Now I'll end the code with **`console.timeEnd('time')`** and we will get the time taken to execute the code

> **Note:** `console.time` and `console.timeEnd()` must have same **"string"** name, which is **`time`** here.


> It is really handy when you are learning **Algorithums** and you want to measure the time taken to execute the code.

# Let's try it out.

```javascript
let nums = [];
// it's empty array.
for (let i = 0; i < 1000000; i++) {
    // making a loop over 1 million times; and pushing it.
    nums.push(Math.floor(Math.random() * 1000000));
}
// sorting the arrray
nums.sort(function (a, b) { return a - b });
```


### Solving by Linear Search Algo:
```javascript
let LinearSearch = function (nums, target) {
    console.time("linear")
    for (let i = 0; i < nums.length; i++) {
        if (nums[i] === target) {
            console.timeEnd("linear")
            return i;
        }
    }
    console.timeEnd("linear")
    return -1;
}
// find million and 1
LinearSearch(nums, 1000001);
console.log(LinearSearch(nums, 1000001));
// linear: 10.044ms
// -1
```

### Example with Binary Search Algo:
```javascript
// Make a function of binary search
let nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
let target = 5;


let BinarySearch = function (nums, target) {
    console.time("binary")
    let start = 0;
    let end = nums.length - 1;
    while (start <= end) {
        let mid = Math.floor((start + end) / 2);
        if (nums[mid] === target) {
            console.timeEnd("binary")
            return mid;
        }
        else if (nums[mid] < target) {
            start = mid + 1;
        }
        else {
            end = mid - 1;
        }
    }
    console.timeEnd("binary")
    return -1;
}
console.log(BinarySearch(nums, 1000001))
// binary: 0.129ms
// -1
```
## See it's become so handy far a beginner to understand the concept of time taken by a function.



## 🫂 Thanks for reading.

### If you have any questions, please feel free to contact me; comment on the post below or reach on me on

### Twitter : [`@Abhayprajapati_`](https://twitter.com/Abhayprajapati)

### Github : [`@theabhayprajapati`](https://github.com/theabhayprajapati)
