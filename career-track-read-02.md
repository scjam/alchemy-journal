## 11-30-20

### Array Methods
- forEach() to loop over an array's items
- includes() to see if an array includes the item passed
- filter() to create a new array with only the elements that pass the condition
- map() to create a new array while changing each item by what is passed
- reduce() applies a function against an accumulator and each item in the array, reduces it to a single value
- some() checks if at least one item passes the condition
- every() checks if all items pass a condition
- sort() arranges the items in asc/desc order
- Array.from() changes something that is "array-like" into an actual array
- Array.of() creates an array from the arguments passed

### Array Method Cheat Sheet
- I like this goofball's stuff, I subscribed to get the cheat sheet

### TDD, Where Did It All Go Wrong
- The Problem: TDD can be expensive to own and maintain
- We often write more test code than implementation code
- Writing TDD is slower
- If tests break your code when you add new code, they might be impeding good code
- Developers start ignoring red results
- TDD rebooted:
- Kent Beck
- API... what is the contract your software has with the world?
- Do not write tests for implementation details
- There's a behavior that I need to prove through code
- Tests should not be in isolation
- For red-green-refactor... refactor is the KEY step
- Clean code is also key
- TDD does not have to be slow, only test the necessary
- Avoid mocking and leave your implementation details free of tests
- Don't get pattern-happy
- 

### TDD red-green-refactor
- Read this in prep work...
- Just a simple three-step process to think about when applying TDD.
1. What do you want to develop?
2. How do you make your tests pass?
3. How do you improve your existing code?

### Cycles of TDD
- Also read this for prep...
- There's actually several cycles happening while you are writing code. On a small level you applying the three laws of TDD, on a larger level the red-green-refactor, and the overarching one is the specific/generic cycle.
