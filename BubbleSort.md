---
title: BubbleSort
tags: Sorting,array
---

Explain briefly what the snippet does.

- This snippet sort the given array in ascending order.
- Comparison based algorithm.
- Repedately swap the largest element and bubble it up to last index.

```js
const BubbleSort =( int nums[], int n) =>
  { 
  for(int i = 0; i<n-1 ;i ++){
  for(int j = 0; j < n-1-i; j++){
  if(nums[j+1]>nums[j]){
  int temp = a[j+1];
  a[j+1] = a[j];
  a[j] = temp;
  }
```

```js
int nums[] = {7,3,9,5,8}
int n = sizeof(nums)/4;
BubbleSort(nums,n); // '3,5,7,9,8'
```
