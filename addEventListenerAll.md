---
title: Add event listener to all targets
tags: browser,event
expertise: intermediate
author: chalarangelo
cover: blog_images/red-mountain.jpg
firstSeen: 2021-04-22T08:53:29+03:00
lastUpdated: 2021-04-22T08:53:29+03:00
---

Attaches an event listener to all the provided targets.

- Use `Array.prototype.forEach()` and `EventTarget.addEventListener()` to attach the provided `listener` for the given event `type` to all `targets`.

```js
const addEventListenerAll = (targets, type, listener, options, useCapture) => {
  targets.forEach(target =>
    target.addEventListener(type, listener, options, useCapture)
  );
};
```

```js
addEventListenerAll(document.querySelectorAll('a'), 'click', () =>
  console.log('Clicked a link')
);
// Logs 'Clicked a link' whenever any anchor element is clicked
```
