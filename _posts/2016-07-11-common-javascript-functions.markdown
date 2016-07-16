---
layout: post
title:  "Common JavaScript Functions"
date:   2016-07-11 23:11:20 -0700
categories: javascript
---

Below is a small list of common JavaScript functions I use on regular basis

# String
**String.split(" ")**
- split a string (separated by space) into an array.

    var s= "My name's rattanak";
    var a = s.split(" ");
    console.log(a);  // ["My", "name's", "rattanak"']

**String.split("")**
- split a string by character ("" is empty) into an array.

    var s= "hello";
    var a = s.split("");
    console.log(a);  // ["h", "e", "l", "l", "o"]

# Array
Array is one of the most used data structure and a lot of time we deal with it by using loops to obtain/work on each element in the array.

**Array.join(separator)**
- converting an array into a string


    var fruits = ["Banana", "Orange", "Apple"];
    var fruitString = fruits.join("-");
    console.log(fruitString);  //Banana-Orange-Apple

# Utilities

```
Math.random();
- return a random number [0, 1), 1 is excluded
```

```
Math.floor(Math.random() * (max - min)) + min;
- return a random integer [min, max), max is excluded
```