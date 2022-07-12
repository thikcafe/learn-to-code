---
title: My Notes
date: 2022-07-10T14:05:17.316Z
tags: "# notes, keywords,"
---
## Type & Value:

- string vs array => string is immutable, and array is mutable (so are their functions, respectively). Moreover, string can "borrow" immutable functions from array.

```
    Array.prototype.*join*.call(str, '-')

    var c = a
    // split `a` into an array of characters
    .split( "" )
    // reverse the array of characters
    .reverse()
    // join the array of characters back to a string
    .join( "" );

    // code above not working with unicode (see in Types & Grammars chapter 2 for solutions)
    // another way is to store string as array
```

- array vs object => array is numeric & ordered, object is key(string only) - value pair & unordered (**using them that way**) 

- object vs map => object is key(string only) - value pair & unordered, [map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)'s keys could be any value

- value vs ref => the only way to control is using **types** of value

> value: using *wrapper* object

> ref: creating *new* value 

