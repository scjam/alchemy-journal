## 02-01-21

### setState Explained
- React components can have state
- setState() is the only way to update the initial state
- reconciliation is the way React updates the DOM

### Lists and Keys
- This is like relearning a more complicated version of Pug

### Typechecking Props
- React has built in typechecking (can still use with Typescript)
- propTypes property
- Also seems more complicated than just using Typescript

### Components and Props
- Wow, again something that Pug has made better
- A component must never modify its own props
- "Pure" functions do not attempt to change their inputs

### Handling Events
- React events are named using camelCase
- Pass a function as the event handler
- To prevent default behavior you must call preventDefault() explicitly
- what the heck is a synthetic event

### Snapshot Testing
- Treat snapshots as code
- Tests should be deterministic
- Use descriptive snapshot names

### React Testing Library
- what the heck is this goat
- react-testing-library solution for testing components
- Test is written in a way that resembles user experience
- I feel like I'll have to use this before I understand it
