# Learning Eleventy from Scratch

I'm taking the course [Learn Eleventy from scratch](https://piccalil.li/course/learn-eleventy-from-scratch) by [Andy Bell](@hankchizljaw)

## Progress

I finished lesson 19.

## Remarks

In lesson 19, I made changes to gulp-tasks/sass.js to make it run on Windows:

```js
// top of the file
const path = require('path');

//...

// Get everything after the last slash
const sourceFileName = path.basename(history[0]);
```
