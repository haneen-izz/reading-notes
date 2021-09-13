# Introduction to React and Components

![Image](https://cdn.evilmartians.com/front/posts/optimizing-react-virtual-dom-explained/cover-a1d5b40.png)

- What is a component?
- What are the charactistics of a component?
- What are the advantages of using component based architecture?

## component 

![Image](https://cdn-media-1.freecodecamp.org/images/1*N2KU7pOcwZwKeOi3B-YBLQ.png)


A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

## Characteristics of Components:

| Characteristics     | Description |
| ----------- | ----------- |
| Reusability    | Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task. |
|  Replaceable | Components may be freely substituted with other similar components.|
|  Not context specific |Components are designed to operate in different environments and contexts.  |

## advantages of using component:

1. Reliability: The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

2. Reusable: The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

3. Modification of technical complexity: A component modifies the complexity through the use of a component container and its services.

## What is Props?

React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

## Using Props in React

 + Firstly, define an attribute and its value
 + Then pass it to child components by using Props
 + Finally, render the Props Data

**example**
```
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
```

*The smallest React example looks like this:*

```
ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```


## Things I want to know more about
