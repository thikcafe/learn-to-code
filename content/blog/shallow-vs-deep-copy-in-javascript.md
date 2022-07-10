---
title: Shallow vs Deep copy in Javascript
date: 2022-07-10T13:41:50.338Z
tags: Javascript,
---
[How to differentiate between deep and shallow copies in JavaScript](https://www.freecodecamp.org/news/copying-stuff-in-javascript-how-to-differentiate-between-deep-and-shallow-copies-b6d8c1ef09cd/)

[Shallow Copy (MDN)](https://developer.mozilla.org/en-US/docs/Glossary/Shallow_copy)

[Deep Copy (MDN)](https://developer.mozilla.org/en-US/docs/Glossary/Deep_copy)

**Notes**:

*Double danger* => Nested (array & object) is dangerous (**almost data in real application is nested**), AND in JavaScript, all standard built-in object-copy operations create shallow copies rather than deep copies (**some does not look like etc Array.prototype.concat()**).  

