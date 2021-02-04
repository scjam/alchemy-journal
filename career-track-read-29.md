## 02-03-21

### MVC
- Software design pattern
- Model: the central component, the app's dynamic data structure, manages data, logic, and rules
- View: any representation of information
- Controller: accepts input and coverts it to commands

### Architecting Single Page Applications
- View: presentational and container components
- Application Services: interpret state
- Store: holds state and publishes
- Domain (Services)
- Immutability makes tracking changes cheap
- Bookmarked for reference later

### React MVC
- The echo chamber soft dev boi computer science thing that's happening at the beginning of this article is annoying me, so I'll bookmark and revisit if I actually need to

### Reconciliation
1. Two elements of different types will produce different trees.
2. The developer can hint at which child elements may be stable across different renders with a key prop.
- React will do a full rebuild when root elements have different types
- React will update what it needs to in DOM elements of the same type
- Keys help react match children and make tree conversion efficient
