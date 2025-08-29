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

***

### Intermediate

**How does updating state trigger a re-render?**\
**Answer:** React compares the new state with the previous one. If it’s different, React schedules a re-render to update the UI.

***

**What’s the difference between multiple setState calls in class components vs functional components?**\
**Answer:** **Class components** → setState calls are batched into a single update → one re-render.\
**Functional components (with hooks)** → each useState setter is independent, but React may still batch multiple updates within the same event → fewer re-renders than expected.

***

**How do you update state based on the previous state safely?**\
**Answer:** Pass a function to the state setter to ensure the latest value is used:
```jsx
const [counter, setCounter] = useState(0);
setCounter(prev => prev + 1);
```

***

**What problems can arise from asynchronous state updates?**\
**Answer:** The new state isn’t immediately available after calling setState/setter. Relying on the current value may give stale data if you don’t use the functional update form.

***
