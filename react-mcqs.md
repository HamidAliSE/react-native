# React MCQs

### Core Concepts

**What is the main purpose of the Virtual DOM in React?**\
A) To style UI elements\
B) To provide a lightweight copy of the DOM for efficient re-renders\
C) To manage navigation\
D) To handle API calls\
**Answer:** B) To provide a lightweight copy of the DOM for efficient re-renders

**What does `React.StrictMode` NOT do?**\
A) Highlight unsafe lifecycles\
B) Double-invoke functions in dev mode for testing\
C) Optimize performance in production\
D) Warn about deprecated APIs\
**Answer:** C) Optimize performance in production

**Why should you avoid using array indexes as keys in lists?**\
A) They reduce performance\
B) They can cause incorrect re-renders if list items change order\
C) They are not valid in JSX\
D) React does not allow them\
**Answer:** B) They can cause incorrect re-renders if list items change order

**What is the advantage of `lazy()` and `Suspense` in React?**\
A) They preload all components at startup\
B) They allow code-splitting and lazy loading of components\
C) They replace `useEffect`\
D) They memoize props\
**Answer:** B) They allow code-splitting and lazy loading of components

**What is the purpose of `key` in a list?**\
A) To optimize rendering by uniquely identifying list items\
B) To apply styles\
C) To act as a ref\
D) To pass props\
**Answer:** A) To optimize rendering by uniquely identifying list items

**Why should you use a stable function reference with `FlatList`’s `renderItem`?**\
A) To prevent unnecessary re-renders of list items\
B) To improve styling consistency\
C) To avoid crashes\
D) To reduce bundle size\
**Answer:** A) To prevent unnecessary re-renders of list items

**What is the purpose of `React.memo`?**\
A) To skip rendering a component if props have not changed\
B) To store state globally\
C) To replace `useEffect`\
D) To batch state updates\
**Answer:** A) To skip rendering a component if props have not changed

**In React, why should keys in a list be unique?**\
A) To avoid duplicate props\
B) To help React identify which items changed, added, or removed\
C) To improve styling\
D) To prevent re-renders completely\
**Answer:** B) To help React identify which items changed, added, or removed

**What is the correct way to conditionally render elements in React?**\
A) Using `if` statements inside JSX\
B) Using ternary operators or logical AND (`&&`)\
C) Using `while` loops in JSX\
D) Rendering everything and hiding with CSS\
**Answer:** B) Using ternary operators or logical AND (`&&`)

**What is the purpose of `React.StrictMode`?**\
A) To prevent re-renders\
B) To highlight potential problems in an app during development\
C) To enforce TypeScript types\
D) To optimize performance automatically\
**Answer:** B) To highlight potential problems in an app during development

**What is React.Fragment (`<>...</>`) used for?**\
A) Wrapping multiple elements without adding extra nodes to the DOM tree\
B) Styling components\
C) Handling errors\
D) Managing state\
**Answer:** A) Wrapping multiple elements without adding extra nodes to the DOM tree

**What is the default behavior of React components when state or props change?**\
A) They unmount\
B) They re-render\
C) They stay the same\
D) They reset all state\
**Answer:** B) They re-render

**What is the difference between props and state?**\
A) Props are mutable, state is immutable\
B) Props are for parent-to-child data, state is managed inside a component\
C) Both are used only in class components\
D) They are identical\
**Answer:** B) Props are for parent-to-child data, state is managed inside a component

**What is JSX in React?**\
A) A CSS framework\
B) A syntax extension for JavaScript to write UI elements\
C) A JSON format\
D) A templating engine\
**Answer:** B) A syntax extension for JavaScript to write UI elements

**What is the purpose of `props` in React?**\
A) To store internal component state\
B) To pass data from parent to child components\
C) To manage global state\
D) To apply styles\
**Answer:** B) To pass data from parent to child components

**In React, what must you provide when rendering a list of elements?**\
A) A `ref`\
B) A `className`\
C) A `key` prop\
D) A `style`\
**Answer:** C) A `key` prop

### Hooks

**Which hook is used to declare state in functional components?**\
A) `useEffect`\
B) `useContext`\
C) `useState`\
D) `useReducer`\
**Answer:** C) `useState`

**What happens when you update state using `setState` (or `useState`)?**\
A) The state updates immediately without re-rendering\
B) The component re-renders with the new state\
C) The state does not change\
D) It clears all props\
**Answer:** B) The component re-renders with the new state

**Which React hook is used for side effects like API calls or subscriptions?**\
A) `useEffect`\
B) `useMemo`\
C) `useReducer`\
D) `useCallback`\
**Answer:** A) `useEffect`

**Which hook is used for sharing data without passing props through every level of the component tree?**\
A) `useMemo`\
B) `useReducer`\
C) `useContext`\
D) `useEffect`\
**Answer:** C) `useContext`

**What is the correct way to update state in React?**\
A) `state.count = 5`\
B) `setCount(count + 1)`\
C) `this.count++`\
D) `count = count + 1`\
**Answer:** B) `setCount(count + 1)`

**Which hook is used to access the previous state values or persist mutable values?**\
A) `useReducer`\
B) `useRef`\
C) `useMemo`\
D) `useEffect`\
**Answer:** B) `useRef`

**Which hook is best for expensive calculations that should not run on every render?**\
A) `useEffect`\
B) `useMemo`\
C) `useRef`\
D) `useState`\
**Answer:** B) `useMemo`

**In class components, which method is similar to `useEffect` with an empty dependency array?**\
A) `componentDidUpdate`\
B) `componentDidMount`\
C) `componentWillUnmount`\
D) `render`\
**Answer:** B) `componentDidMount`

**What does `useReducer` provide compared to `useState`?**\
A) A way to manage complex state logic with actions and reducers\
B) A faster alternative to `useState`\
C) A replacement for `useEffect`\
D) A way to manage props\
**Answer:** A) A way to manage complex state logic with actions and reducers

**What is the return value of `useState`?**\
A) The state value and a function to update it\
B) Only the state value\
C) Only the setter function\
D) An object with `state` and `setState` keys\
**Answer:** A) The state value and a function to update it

**Which hook should you use for cleanup (like removing event listeners)?**\
A) `useReducer`\
B) `useEffect` with a cleanup function\
C) `useState`\
D) `useMemo`\
**Answer:** B) `useEffect` with a cleanup function

**Why should you avoid updating state directly in React?**\
A) It slows down performance\
B) React won’t detect the change and won’t re-render\
C) It clears props\
D) It causes memory leaks\
**Answer:** B) React won’t detect the change and won’t re-render

**What is the purpose of `useCallback`?**\
A) To memoize values\
B) To memoize functions to prevent re-creation on every render\
C) To execute functions only once\
D) To replace `useEffect`\
**Answer:** B) To memoize functions to prevent re-creation on every render

**When does `useMemo` recompute a value?**\
A) On every render\
B) Only when one of its dependencies changes\
C) Only once during the initial render\
D) When `useEffect` is called\
**Answer:** B) Only when one of its dependencies changes

**Which hook is best for synchronously reading layout or measuring elements?**\
A) `useEffect`\
B) `useLayoutEffect`\
C) `useMemo`\
D) `useReducer`\
**Answer:** B) `useLayoutEffect`

**What is the difference between `useRef` and `useState`?**\
A) `useRef` persists values without causing re-renders, `useState` triggers re-renders when updated\
B) `useRef` works only in class components\
C) `useState` stores DOM references, `useRef` stores values\
D) They are identical\
**Answer:** A) `useRef` persists values without causing re-renders, `useState` triggers re-renders when updated

**Which hook allows you to build your own reusable logic across components?**\
A) `useReducer`\
B) `useEffect`\
C) Custom hooks (functions starting with “use”)\
D) `useRef`\
**Answer:** C) Custom hooks (functions starting with “use”)

**Why can updating state in a loop cause unexpected results?**\
A) Because React batches state updates asynchronously\
B) Because React prevents loops\
C) Because state can only be updated once per render\
D) Because props reset\
**Answer:** A) Because React batches state updates asynchronously

**What does the Context API solve?**\
A) Re-renders\
B) Passing props through deeply nested components (prop drilling)\
C) Global error handling\
D) Navigation\
**Answer:** B) Passing props through deeply nested components (prop drilling)

**What happens if you call a hook inside a loop or condition?**\
A) It works normally\
B) It breaks the Rules of Hooks and may cause errors\
C) It optimizes performance\
D) It runs only once\
**Answer:** B) It breaks the Rules of Hooks and may cause errors

**Which React feature batches multiple state updates into a single render cycle?**\
A) Virtual DOM\
B) Concurrent Mode\
C) Automatic batching\
D) Context API\
**Answer:** C) Automatic batching

**Which hook is best for handling complex state transitions with actions?**\
A) `useState`\
B) `useEffect`\
C) `useReducer`\
D) `useMemo`\
**Answer:** C) `useReducer`

**Why would you use `useImperativeHandle` with `forwardRef`?**\
A) To expose custom methods from a child component to a parent\
B) To style refs\
C) To replace `useRef`\
D) To batch renders\
**Answer:** A) To expose custom methods from a child component to a parent

**Which hook should be used to listen to state or prop changes and run side effects accordingly?**\
A) `useEffect`\
B) `useMemo`\
C) `useReducer`\
D) `useCallback`\
**Answer:** A) `useEffect`
