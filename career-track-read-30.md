## 02-07-21

### Hooks API
- useState (State Hook) is similar to this.setState in a class but doesn't merge the new and old state
- useState takes an argument of the initial state
- State Hook can be used more than once in a single component
- Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes.
- useState is a built in hook but you can also create your own
- Effect Hook (useEffect) adds ability to do side effects, i.e. data fetching, subscriptions, changing the DOM
- Effect Hook serves same purpose as componentDidMount
- When you call useEffect, you’re telling React to run your “effect” function after flushing changes to the DOM
- Rules: only call Hooks at the top level, do not call them in loops or nested functions, only call Hooks from React function components
- Custom hooks let you reuse stateful logic between components
- Ehhh custom hooks feel fuzzy to me

### State Hook
- Hooks go in the cool zone between const/function and return
- Hooks don't go inside classes
- You write a function component and need to add some state to it
- Declare a state variable between the function calls to preserve some values
- The only argument to pass useState() is the initial state

### Effect Hook
- useEffect tells React that your component needs to do something after render
- Runs after first render and every update
- Bookmarked for reference, seems like there were a lot of tips and special use cases

### Hooks API Reference
- Skimmed and bookmarked this. Thought it was a great summary of the other articles we read + more
