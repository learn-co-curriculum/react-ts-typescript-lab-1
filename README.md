# TypeScript Lab 1: Basic Typing

## Learning Goals

- Write a function with TypeScript 
- Use TypeScript type annotation 

## Introductions to Labs 

Welcome to your first lab in this course! Throughout this course, you will work 
on various assignments as you learn new concepts. 

All assignments are hosted on GitHub. In order to work on them, however, you 
will need to complete work on your local machine. The general process is:

- Click the blue "Fork" button in Canvas (found in the top right corner of the
  assignment)
- Create a personal copy (a 'fork') of the assignment in GitHub
- Download your personal copy (referred to as 'cloning') to your computer
- Complete the required work
- Submit your completed work to Canvas

This process should feel familiar from the prework. With that refresher, let's
get started on your first TypeScript lab. 

## The Activity 

Write a TypeScript function called `prepend` that takes in two parameters, a 
number and a string. The function should add the provided number amount of 
spaces in front of the provided string and console log the result. 

**Example output**:

```js
prepend(5, "The quick fox jumps over the lazy dog")
// => "     The quick fox jumps over the lazy dog"
```

Additionally, ensure that the parameters are correctly typed. The first parameter
should be of type `number` while the second should be type `string`. 

If you've typed your parameters correctly, the following example should throw
an error: 

```js
prepend("5", "The quick fox jumps over the lazy dog") 
```

## Instructions 

We've provided a starter file for you to work in: `src/index.ts`. It contains the 
base function already set up for you. Complete your work for this lab there.

Whenever you're ready to run your code, remember the steps to compiling `.ts` to `.js`
before you can the resulting `.js` file: 

1. Compile your TypeScript code with `tsc <TS filename>`. For this lab, it would be
`tsc src/index.ts`. 
2. Run the compiled JavaScript file with Node.js: `node <JS filename>`. For this lab,
it would be `tsc src/index.js`. 

Remember to do this each time you make a change you want to test.

> **Note**: This process doesn't seem very efficient, does it? Don't worry, we'll 
> learn how to streamline it in the next lesson! 