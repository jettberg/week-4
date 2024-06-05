# Tier 1 Week 4

This week we'll be pulling together all of the Javascript techniques you've learned thus far:

- variables
- arrays
- conditionals
- functions

**REMINDER:** Make sure to answer the Slack discussion question for this week!

## Part 1 - Practice with Functions 
Complete the `1-function-practice.js` file. 

In this file you will *__fill in__* the missing code to complete the function as described in the comments. (Think of it as similar to fill in the blanks, but we don't show you where the blanks are.) To do this, you may need to add input parameters, return values and/or logic to the function body. For the last few, you'll need to write it all!

After completing each function. Make sure to call (or use) the function in your code (as shown in the example) to test it and make sure it works correctly. For more complex functions, test multiple outcomes to ensure it works correctly in all scenarios. 

> Note that the first problem is completed for you as an example.

## Part 2 - Styling with `CSS` 

Now let's practice some CSS! For this, you will update the index.html file and create a new CSS Stylesheet. 

Requirements:
- Place the existing `<h1>` and `<p>` inside of a `header` element and add a background-color to that header.
- Create a stylesheet.css file and import it into the index.html file.
- Add a new div with a class name of "info". Inside that div add an `<h2> My name is YOUR NAME </h2>` Add a background-color and a text color of your choice.
- Add an image tag `<img>` and source an image of your main mode of transportation (you car, bus, scooter, bike, feet, etc)
- Add an `<h3>` that explains your mode of transportation. Add a background-color and a text color of your choice.

The style should look something like this (image shown has a little more CSS - feel free to try some new things!)
<img src="./example.png" />


## Part 3 - Cart System 

In this section we will write some functions that might be used in a simple cart system for a store. 

### Required Features
Update the `2-cart.js` file to do the following:

- Create a global variable named `basket` and set it to an empty array.

- Create a function called `addItem`. It should:
  - take an input parameter for a string `item`
  - add the new item to the global array `basket`. 
  - return `true` indicating the item was added

- Create a function called `listItems`. It should:
  - loop over the items in the `basket` array
  - console.log each individual item on a new line

- Create a function called `empty`. It should:
  - reset the `basket` to an empty array

> __IMPORTANT__
> Make sure that you are writing code *in the file* to test every function that you write!

For example, to test `addItem`:
```
console.log(`Basket is ${basket}`);
console.log('Adding apples (expect true)', addItem('apples'));
console.log(`Basket is now ${basket}`);
```

### Stretch Goals 
Remember that Stretch Goals are not required, but will help you to further develop concepts from the skills we have covered.

__Using functions in other functions!__

1. Add a global `const` named `maxItems` and set it to 5.

2. Create a function called isFull(). It should:
  - return `false` if the basket contains *less* than max number of items
  - return `true` otherwise (equal or more than maxItems)

3. Update the required `addItem` function to:
  - Use the `isFull` function to prevent more than `maxItems` from being added to the basket. 
  - If an item was added to the array, return `true`
  - If there was no room and the item could not be added return `false`

__Using Array built-in functions!__

4. Create a function called `removeItem`. It should:
  - Take an input parameter for a string `item`
  - Use [Array.indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf) to find the index of the first matching item in the basket.
  - Use [Array.splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) to remove the first matching item from the basket.
  - Return the item removed or `null` if the item was not found# week-3
# week-3
