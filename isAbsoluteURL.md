---
title: Check if absolute URL
tags: string,browser,regexp
expertise: intermediate
cover: blog_images/coffee-phone-tray-2.jpg
firstSeen: 2017-12-31T14:42:45+02:00
lastUpdated: 2020-10-20T23:02:01+03:00
---

Checks if the given string is an absolute URL.

- Use `RegExp.prototype.test()` to test if the string is an absolute URL.

```js
const isAbsoluteURL = str => /^[a-z][a-z0-9+.-]*:/.test(str);
```

```js
isAbsoluteURL('https://google.com'); // true
isAbsoluteURL('ftp://www.myserver.net'); // true
isAbsoluteURL('/foo/bar'); // false
```
