# **State and Props.**

## **React: Component Lifecycle Events.**

* React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

## **phases of the component lifecycle:**

1. **Mounting:** When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.
2. **Updating:** Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
3. **Unmounting:** The final phase of the lifecycle if called when a component is being removed from the DOM.

## **Questions**

### Component lifecycle:

* Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

  - `render`

* What is the very first thing to happen in the lifecycle of React?

  - `Mounting`

* Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates:

  1. `constructor`
  2. `render`
  3. `componentDidMount`
  4. `React Updates`
  5. `componentWillUnmount`

* What does componentDidMount do?

  - `If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.`

### Props & States:

1. What types of things can you pass in the props?
    - Things you want to render
    - Displays of titles of sub-titles
    - Displays information

2. What is the big difference between props and state?
   - States are handled inside of the component while props are handled outside of and passed into the component
   - States are using when you handling dynamic, just like the data coming from users for instance. Props are using when you handling static data.

3. When do we re-render our application?
    - When the states is changing in our application.

4. What are some examples of things that we could store in state?
    - Incrimentation or Decrimentation **(counter)**.
    - Forms, checkbox, button, or any input element.


