# introduction-to-react-and-components

#### What is a “component”?

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities.

#### What are the characteristics of a component?

- Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
- Replaceable − Components may be freely substituted with other similar components.
- Not context specific − Components are designed to operate in different environments and contexts.
- Extensible − A component can be extended from existing components to provide new behavior.
- Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
- Independent − Components are designed to have minimal dependencies on other components.

#### What are the advantages of using component-based architecture?

- Ease of deployment
- Reduced cost
- Ease of development
- Reusable
- Modification of technical complexity
- Reliability
- System maintenance and evolution is easy
- Independent

#### What is “props” short for?

Properties!

#### How are props used in React?

Props is used for passing data from one component to another, in a uni-directional flow (one way from parent to child). Props data is read-only, which means that data coming from the parent should not be changed by child components.

#### What is the flow of props?

1. Define an attribute and its value/data
2. Pass it to child component(s) by using Props
3. Render the Props Data
