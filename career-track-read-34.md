## 02-15-21

### Composition vs Inheritance
- Sometimes you might need multiple "holes" in a component
- Components can be "special cases" of other components
- Do not recommend component inheritance hierarchies

### useReducer
- Alternative (preferable when you have complex state logic) to useState
- Accepts a reducer of type (state, action) => newState, and returns the current state with a dispatch method
- Initialize by passing the initial state as the second argument or pass an init function as the third argument

### Three Principles Redux
- Single source of truth: global state of your app is stored in an object tree within a single store
- State is read-only: only way to change state is to emit an action
- Changes are made with pure functions: to specify how the state tree is transformed by actions, you write pure reducers

### Core Concepts Redux
- Like that it looks like models
- Redux seems pretty straightforward so far
