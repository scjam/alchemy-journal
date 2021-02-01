## 01-31-21

### Intro to Webpack
- Necessity is the mother of invention
- Websites got bulky with javascript files and developers started outcoding what browsers could understand
- "Webpack is a static module bundler."
- Webpack makes a graph that lets the browser know the LCD of what's needed to execute the code
- create-react-app
- React uses ES6 classes and import statements
- Entry property is the file that webpack should start with
- Also need an output property to specify where the bundle should be generated
- Webpacks initially only understand JavaScript and JSON

### Webpack Concepts
- Static module bundler
- Internally builds a dependency graph which maps every module your site needs
- Entry: the entry point is the module the webpack starts in
- Output: tells webpack where to emit the bundles it creates
- Loaders: allow webpack to process file types other than JS and JSON
- Plugins: leverage to perform a wider range of tasks
- Mode: development, production, or none

### Rendering Elements
- React elements are plain objects
- React DOM updates the DOM to match the react elements
- So far this seems more complicated, not less
- React elements are immutable, once created, children and attributes can't be changed

### Introducing JSX
- JSX is a syntax extension to JavaScript
- HTML but fancy like JS
- Is HTML forever forever? Like is it the latin of internet language? Not the first, but the most permeable to other languages?
- Instead of seperating technologies, React seperates concerns with components
