## 02-02-21

### Architectural Styles and Patterns
- Recurring solutions to recurring problems
- Style is given to recurrent design, not to solve a problem
- Patterns > Styles > Single Architecture
- Idiom is a low-level pattern specific to a language
- Layers: Presentation, application, business logic, data access

### Container and Presentation Pattern
- Containers: how things work and contain business login
- Presentations: how things look, present your data

### Container Details
- Initialize state via class properties or inside a constructor
- this.setState
- Then comes componentDidMount to fetch data
- Hooks...lets do this

### Presentation Details
- Functional components, they return the markup
- Often will need to pass props in order to make them reusable

### Functional vs Class Components
- Functional is just plain JS
- Class requires extend from React.Component

### Conditional Rendering
- Works the same way in React
- Use variable to store elemetns
