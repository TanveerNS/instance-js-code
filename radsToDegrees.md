---
title: Radians to degrees
tags: math
expertise: beginner
cover: blog_images/flower-portrait-6.jpg
firstSeen: 2018-02-14T12:24:50+02:00
lastUpdated: 2020-09-15T16:28:04+03:00
---

Converts an angle from radians to degrees.

- Use `Math.PI` and the radian to degree formula to convert the angle from radians to degrees.

```js
const radsToDegrees = rad => (rad * 180.0) / Math.PI;
```

```js
radsToDegrees(Math.PI / 2); // 90
```
