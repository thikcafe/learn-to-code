---
title: My Notes
date: 2022-07-10T14:05:17.316Z
tags: "# notes, keywords,"
---
![]()

## Type & Value:

* string vs array => string is immutable, and array is mutable (so are their functions, respectively). Moreover, string can "borrow" immutable functions from array.

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

* array vs object => array is numeric & ordered, object is key(string only) - value pair & unordered (**using them that way**) 
* object vs map => object is key(string only) - value pair & unordered, [map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)'s keys could be any value
* value vs ref => the only way to control is using **types** of value

> value: using *wrapper* object
>
> ref: creating *new* value 

## Storage:

> <https://learning.oreilly.com/library/view/html5-cookbook/9781449318444/ch10.html#application_caching>

local & session storage: data stored in these containers must be strings

*The localStorage and sessionStorage APIs are synchronous in design, which makes them easier to use but can result in slower performance. Be careful using these APIs in performance-sensitive code.*

![](/assets/screen-shot-2022-07-12-at-11.29.13.png)