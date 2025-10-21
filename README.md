# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN, a function is a block of code that performs a specific task. A function can take input values called parameters and can send back an output called a `return` value.

You can think of a function like a recipe. The ingredients of are like the inputs, the cooking steps are like the lines of code inside the function and the finished dish is like the output returned at the end. 

### Example

```js
const makeCurry = (masala, chicken) => {
    return masala + " " + chicken;
};

console.log(makeCurry("masala", "chicken"));
```

### Explanation of the Syntax

- `const makeCurry = (masala, chicken) => { ... }` defines an ***arrow function*** called makeCurry.

- `(masala, chicken)` are the ***parameters***, representing the inputs to the function — like ingredients in a recipe.

- The `{ ... }` part is the code block, where the steps of the recipe happen.

- The ***return*** statement sends back the result the “finished dish.”

- Finally, `makeCurry("masala", "chicken")` is how we ***invoke*** the function so that it runs and produces an output.

Just like following a recipe, a function takes inputs, processes them through a set of steps, and produces a final result.
