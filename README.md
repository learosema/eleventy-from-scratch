# Learning Eleventy from Scratch

I'm taking the course [Learn Eleventy from scratch](https://piccalil.li/course/learn-eleventy-from-scratch) by [Andy Bell](@hankchizljaw)

## Progress

I finished lesson 27.

## Remarks

In lesson 19, I made changes to gulp-tasks/sass.js to make it run on Windows:

```js
// top of the file
const path = require('path');

//...

// Get everything after the last slash
const sourceFileName = path.basename(history[0]);
```

In order to run `npm run production` on Windows, you may need to tell NPM to use a unix-like shell (I'm using git bash):
(Or use `cross-env`)

```sh
npm config set script-shell "C:\\Program Files\\Git\\bin\\bash.exe"
```
