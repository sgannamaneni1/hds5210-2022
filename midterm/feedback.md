# Notes on the Midterm

* _Correctness    (out of 40):_ 29
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 0

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._


You forgot to include docstrings and tests for your functions, though.  I've deducted 10 points from the _Docs / Testing_ section.

Generally, please use variable names that provide some context to what a variable represents. `a`, `x`, `y` don't provide much information.  I've deducted 1 point from _Good Practices_ for this.

## Step 1
* What was the variable `count` supposed to be for? That confused me a little bit.
* In general, using variable names that have some context to them is helpful.  Your variables `x` and `y` don't help anyone understand what your code is doing.

## Step 2
For the notes below, I've deducted 1 point from the _Correctness_ section.
* One of the conditions you're supposed to cover is if no match is found, return None.  I don't see that provided for in your `get_rate()` function.
* You have leftover variables like `x`, `count`, and `count1` from Step 1 that aren't needed. Those should be cleaned up.

## Step 3
Exception handling is generally a good way to handle unexpected situations. However, in this function, I think you're using it to handle one specific condition -- where the rate is not found for the provided billing and service code. If the situation is well known, you should handle it directly or through a specific exception type.

## Step 4
I don't see a solution submitted for step 4 and deducted 10 points from _Correctness_ but do see something in the error messages that suggests you did try this.