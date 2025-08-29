# React State

## Beginner

**What is state in React?**\
**Answer:** State is a special variable that React uses to store data that changes over time. When state changes, the component automatically re-renders to reflect the update.

***

**How is state different from props?**\
**Answer:**
* **State** → belongs to a component, can change (mutable).
* **Props** → passed from parent to child, cannot be changed by the child (immutable).

***

**How do you update state in a functional component?**\
**Answer:** By using the `useState` hook’s setter function:
```jsx
const [counter, setCounter] = useState(0);
setCounter(5); // updates state and triggers re-render
```

***

**What happens when you directly mutate state instead of using `setState/useState` setter?**\
**Answer:** The variable may change in memory, but React won’t know → no re-render happens → UI doesn’t update.

***

## Intermediate

**How does updating state trigger a re-render?**\
**Answer:** React compares the new state with the previous one. If it’s different, React schedules a re-render to update the UI.

***

**What’s the difference between multiple setState calls in class components vs functional components?**\
**Answer:**
* **Class components** → setState calls are batched into a single update → one re-render.
* **Functional components (with hooks)** → each useState setter is independent, but React may still batch multiple updates within the same event → fewer re-renders than expected.

***

**How do you update state based on the previous state safely?**\
**Answer:** Pass a function to the state setter to ensure the latest value is used:
```jsx
const [counter, setCounter] = useState(0);
setCounter(prev => prev + 1);
```

***

**What problems can arise from asynchronous state updates?**\
**Answer:** The new state isn’t immediately available after calling `setState/setter`. Relying on the current value may give stale data if you don’t use the functional update form.

***

## Advanced

**How does React batch state updates, and why?**\
**Answer:** React batches multiple state updates in the same event loop into a single re-render.\
**Why?**
* To keep state updates predictable within a render cycle.
* To improve performance by reducing unnecessary re-renders.

***

**Explain the difference between local component state and global state management.**\
**Answer:**
* **Local state** → managed inside a component using `useState/useReducer`. It’s isolated to that component.
* **Global state** → shared across the app, usually via Context API, Redux, or Zustand. Accessible through selectors/hooks and updated by dispatching actions.

***

**How do hooks like useReducer improve complex state handling?**\
**Answer:** `useReducer` centralizes state updates into a reducer function, making complex state logic more structured, testable, and easier to debug compared to multiple scattered `useState` calls.

***

**How does state persist (or not) during navigation or unmounting in RN?**\
**Answer:**
* State is tied to a component’s lifecycle. When a component unmounts, its state is cleared.
* With navigation, inactive screens may stay in memory (depending on the navigator config), so their state is preserved when you go back. If the screen is unmounted (e.g., removed from stack), the state is lost.

***
