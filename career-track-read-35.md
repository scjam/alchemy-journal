## 02-15-21

### Redux Motivation
- Javascript code must manage a lot of state, i.e. routes, tabs, spinners, pagination, controls, etc.
- Mixing the concepts of mutation and asynchronicity
- Redux is for managing the state of your data but making state mutations predictable

### Three Principles/Core Concepts
- Repeats of yesterday, but I really like how easy to read the Redux documentation is

### Actions
- State, view, and actions in a one-way data flow
- Immutability: can never be changed
- Action is a plain JS object that has a type field, describes something that happened in the app
- Type field should be a string that gives the action a descriptive name
- Reducer is a function that receives the current state and action and decides how to update the state if necessary
- Redux application state lives in an object called the store
