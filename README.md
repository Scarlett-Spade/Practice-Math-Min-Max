# Practice Math.min, Math.max, spread operator, createElement, classList, innerHTML, append, template literals

This is [Skillcrush](https://skillcrush.com/) course practice.
<br></br>
# Instructions

Write a function expression called showMinMax which accepts the expenses array as a parameter.

In the function body, create a variable called min and assign it to the smallest number in the array: const min = Math.min(...expenses);.

Declare a variable called max to find the largest number in the array.

Create two new list items for the smallest and largest array elements. Set their inner text to:

`Min: $ ${min}` and `Max: $ ${max}`

Append the new list items to the results unordered list. Then remove the "hide" class from the results list.

Create an event listener for clicking the button. The event listener should call the showMinMax function (don’t forget to pass it your array!) and disable the button.
