### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
    React is a javascript library. It allowsa developer to create fast user interfaces for websites and applications.
- What is Babel?
    A toolchain code that we use to convert ECMAScript 2015+ code into a compatible version of javascript.
- What is JSX?
    JSX stands for Javascript XML. It allows us to use html in react.
- How is a Component created in React?
    We create a component in a separate js file so it can be reusable throughout the app. You need to use extends React.Component so it has access to react functions.
- What are some difference between state and props?
    Props are used to pass data from a parent component, while state is used to manage date within that component.
- What does "downward data flow" refer to in React?
    The passing of data or functions via props from parent to child components.
- What is a controlled component?
    Components that have their state and behavior controlled by their parent components.
- What is an uncontrolled component?
    Components that manage their own state internally.
- What is the purpose of the `key` prop when rendering a list of components?
    To help react differentiate between the items and perform updated more efficiently.
- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
    It would not be stable since the array can mutate and indices can shift around.
- Describe useEffect.  What use cases is it used for in React components?
    Allows you to perform side effects in your components. Tells react that your components needs to do something after render.
- What does useRef do?  Does a change to a ref value cause a rerender of a component?
    Is a hook that allows you to persist values between renders. No its does not.
- When would you use a ref? When wouldn't you use one?
    To pass an argument to a method by reference. When you can does someing declaratively.
- What is a custom hook in React? When would you want to write one?
    They are basically reusable functions. When you have an app that is bg enoiugh to reuse code. allows for the app to keep pages small and organized.