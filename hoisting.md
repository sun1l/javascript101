# JavaScript Hoisting

## What is Hoisting in JavaScript?

Let's start with some basic code, most of the time I use this to start convertation on hoisting during interviews.

```
var bar = 10;
function foo() {
    console.log(bar);
    var bar = 20;
}
foo();
```

**What will be the console output?**

If your answer is _undefined_ and you know **why** it is undefined - Hey! you know what is Hoistig in JavaScript, you can skip the rest of the article. 
Otherwise stick around and we will dig deep to figure out why output of _foo_ is not 10 or 20.

To really understand the concepts like Hoisting or Clousures, let's take a step back and undersatnd how JavaScript works.


## JavaScript Compilation
## Function Hoisting
## Hoisting in ES2015



