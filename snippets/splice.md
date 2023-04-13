---
title: Splice method
tags: array
cover: stawberry
firstSeen: 2021-06-13T05:00:00-04:00
---

Changes the content of an array

- The splice method change the array by removing and adding the element.


```js
const ChangeArray = (arr,start,end) =>
  {
    arr = arr.splice(start,end)
    return arr
  }
```

```js
console.log(ChangeArray([1,2,3,4,5,6],1,4));