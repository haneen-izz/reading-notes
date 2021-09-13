## State and Props


![Image](https://i.stack.imgur.com/wqvF2.png)
## What are component lifecycle events?

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.



## phases of the component lifecycle:

![Image](https://miro.medium.com/max/1400/1*fdGC22mqWBAQ7jOFPPAvIg.png)

+ Mounting

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

+ Updating

 Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

+ Unmounting
The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

```
ReactDOM.render(

<FishTable fishes= {fishData}/>,
 document.getElementById(‘app’)

 );
 ```

**getSnapshotBeforeUpdate()**

This is another rarely used method that allows you to capture a picture of the DOM to check it before actually changing anything on the DOM.

**componentDidUpdate()**
This method is useful for performing network requests after a change has occurred.

*React State Vs Props*

react is its ability to manage your data and properly rerender your application when your data changes but there are two main ways in react to think about data there's props and their state and it can be a bit confusing to understand when you should use props and when you should be using state also initial count to be zero so we're gonna pass that through in the props something else that you can think of where you might need props. 

**render()**

Render is the only required method in a class component. It will examine this.props and this.state when called.

## Adding Local State to a Class

```
class Clock extends React.Component {
  render() {
    return (
      <div>
        <h1>Hello, world!</h1>
        <h2>It is {this.state.date.toLocaleTimeString()}.</h2>  
     </div>
    );
  }
}
```

**Handling Events**

- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.


## questions

    1. What types of things can you pass in the props?
    react allows us to pass values from a parent component down to a child component.

    2. What is the big difference between props and state?
    state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

    3. When do we re-render our application?
     automatically re-render whenever there is a change in their state or props.
  

click here to read more :
   [link](https://www.freecodecamp.org/news/react-js-for-beginners-props-state-explained/)



