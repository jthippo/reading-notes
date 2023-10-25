# state-and-props

#### Based off the lifecycle of React, what happens first, the ‘render’ or the ‘componentDidMount’?

Render occurs first; componentDidMount is the final action.

#### What is the very first thing to happen in the lifecycle of React?

Mounting, or constructor() to be specific.

#### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1. constructor
2. render
3. componentDidMount
4. React Updates
5. componentWillUnmount

#### What does componentDidMount do?

Loading anything using a network request or that initialises the DOM.

#### What types of things can you pass in the props?

Any JavaScript value, e.g. objects, arrays, functions.

#### What is the big difference between props and state?

Props are used to pass data from a parent component to a child component, while state is used to manage data within a component. Props are immutable and cannot be changed within a component, while state is mutable and can be updated using the setState function.

#### When do we re-render our application?

Whenever there is a change in their state or prop

#### What are some examples of things that we could store in state?

Light and dark mode themes, any kind of user management.
