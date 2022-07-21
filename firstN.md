---
title: First n elements
tags: array
expertise: beginner
author: chalarangelo
cover: blog_images/digital-nomad-16.jpg
firstSeen: 2022-07-22T05:00:00-04:00
---

Gets the first `n` elements of an array.

- Use `Array.prototype.slice()` with a start value of `0` and an end value of `n` to get the first `n` elements of `arr`.

```js
const firstN = (arr, n) => arr.slice(0, n);
```

```js
firstN(['a', 'b', 'c', 'd'], 2); // ['a', 'b']
```
