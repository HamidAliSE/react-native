# React State

### Beginner

**What is state in React?**\
**Answer:** State is a special variable that React uses to store data that changes over time. When state changes, the component automatically re-renders to reflect the update.

***

**How is state different from props?**\
**Answer:**
**State** → belongs to a component, can change (mutable).\
**Props** → passed from parent to child, cannot be changed by the child (immutable).

***

**How do you update state in a functional component?**\
**Answer:** By using the `useState` hook’s setter function:
```jsx
const [counter, setCounter] = useState(0);
setCounter(5); // updates state and triggers re-render
```

***

**What happens when you directly mutate state instead of using setState / useState setter?**\
**Answer:** The variable may change in memory, but React won’t know → no re-render happens → UI doesn’t update.
