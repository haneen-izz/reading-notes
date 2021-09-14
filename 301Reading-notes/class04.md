#  React and Forms

![Image](https://s1.o7planning.com/en/12145/images/25726059.gif)



## forms 
HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

The `<FormControl>` component renders a form control with Bootstrap styling. The `<FormGroup>` component wraps a form control with proper spacing, along with support for a label, help text, and validation state. To ensure accessibility, set controlId on `<FormGroup>`, and use `<FormLabel>` for the label.

example:


```
<form>
  <label>
    Name:
    <input type="text" name="name" />
  </label>
  <input type="submit" value="Submit" />
</form>
```

---
**questions**

1. What is a ‘Controlled Component’?

 form controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a `controlled component`.
    
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
 update the React state, the displayed value will update as the user types, Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth.

3. How do we target what the user is entering if we have an event handler on an input field?
by declaring a new function inside of our React component for the onChange handler to pass a value to and We will call it handleChange.


---
## JavaScript — The Conditional (Ternary) Operator Explained

![Image](https://miro.medium.com/max/2000/1*z2KBmBJYD3_4-lfKjhO_DQ.png)


---
**questions**


+ Why would we use a ternary operator?
 allows you to assign one value to the variable if the condition is true, and another value if the condition is false.

+ Rewrite the following statement using a ternary statement:

```
if (x===y) {
  value if true;
} else {
  value if false;
}
```
 

---


click here to read more :
[link](https://react-bootstrap.github.io/components/forms/)
