# React Topics

### Props (short for Properties)

* Think of props as inputs to a component.
* They are passed from parent to child (like arguments to a function).
* Read-only → A component cannot change its own props.
* Used when data needs to be displayed or reused.

**Example**

```
const Greeting = ({ name }) => {
  return <Text>Hello, {name}!</Text>;
};

// Usage
<Greeting name="Hamid" />
```
Here, `name` is a prop passed down.

* * *

### State

* State is data managed inside a component.
* It can change over time (usually due to user actions or events).
* Changes in state trigger re-render of that component.

**Example**

```
const Counter = () => {
  const [count, setCount] = useState(0);

  return (
    <View>
      <Text>{count}</Text>
      <Button title="Increase" onPress={() => setCount(count + 1)} />
    </View>
  );
};
```
Here, count is local state. Updating it re-renders the UI.

* * *

### **JSX (JavaScript XML)**

*   A **syntax extension** for JavaScript.
*   Looks like **HTML inside JS**, but it’s not HTML.
*   React uses it to **describe what the UI should look like**.
*   Gets **compiled to plain JS** (`React.createElement`) behind the scenes.

**Example**

```jsx
const App = () => {
  return (
    <View>
      <Text>Hello, Hamid!</Text>
    </View>
  );
};
```

* * *

### **Component**

*   A **component** is a **reusable piece of UI**.    
*   Think of it as a **function or class** that returns some JSX (UI code).
*   Components can be **small (Button, Input)** or **big (Dashboard, ProfileScreen)**.
*   React apps are built by **combining components like Lego blocks**.

* * *

### **Types of Components**

1.  **Functional Component (modern, preferred)**
    *   Just a JS function that returns JSX.        
    *   Can use **hooks** (like `useState`, `useEffect`).

    **Example**
    ```jsx
    const Welcome = () => {
      return <Text>Welcome to my app!</Text>;
    };
    ```
    
2.  **Class Component (older)**    
    *   Uses ES6 classes.        
    *   Has lifecycle methods (`componentDidMount`, etc.).

    **Example**
    ```jsx
    class Welcome extends React.Component {
      render() {
        return <Text>Welcome to my app!</Text>;
      }
    }
    ```

* * *

### **Key Points**

*   **State** is Internal, mutable, controlled by the component itself.
*   **Props** are External, immutable, given by parent.
*   **State** → Internal data of a component.
*   **Props** → Input to a component.
*   **JSX** → Output of a component.
