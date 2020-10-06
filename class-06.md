## 10-05-20

### Problem Domain Article

- Making the problem domain easy to understand helps both the teacher and the student
- Writing code = putting a jigsaw together, without the picture it becomes very hard
- "Understanding the problem is the most critical piece to the equation."
- Either understand the problem before you write the code or begin with the easy part you understand and progress to more difficult parts


### JS Book, Chapters 3 (p. 100-105) & 5

- Variables that are part of an object are called properties
- Functions that are part of an object are called methods
- Keys cannot have the same name
- Access properties or methods of an object with dot notation
- DOM = Document Object Model, not part of HTML or JavaScript
- DOM tree is the family tree for the web page:
  - Document Node
    - Element Nodes, Attribute Nodes, Text Nodes
  1. Access The Elements
    - Select individual elements : getElementById(), querySelector()
    - Select multiple elements : getElementsByClassName(), getElementsByTagName(), querySelectorAll()
    - Traversing between element nodes : parentNode, previous/nextSibling, firstChild / lastChild
  2. Work With Those Elements
    - Access or update text nodes : nodeValue
    - Work with HTML content : innerHTML, textContent, createElement(), appendChild()
    - Access or update attribute values : className / id, getAttribute, setAttribute
- When you need to work with an element more than once, use a variable to store the result of the query
- 
