# React Native MCQs
### Basic
**1. Which language is primarily used to build React Native apps?**\
A) Java\
B) Swift\
C) JavaScript\
D) Kotlin\
**Answer:** C) JavaScript

**2. What is the main difference between ReactJS and React Native?**\
A) ReactJS is used for web, React Native for mobile\
B) ReactJS uses HTML, React Native uses native components\
C) React Native can access device APIs\
D) All of the above\
**Answer:** D) All of the above

**4. Which component is used to display scrollable content in React Native?**\
A) `<ListView>`\
B) `<ScrollView>`\
C) `<FlatList>`\
D) `<SectionList>`\
**Answer:** B) `<ScrollView>`

**5. In React Native, which of the following is used instead of HTML `<div>`?**\
A) `<View>`\
B) `<Container>`\
C) `<Box>`\
D) `<Layout>`\
**Answer:** A) `<View>`

**6. Which of the following is true about React Native styling?**\
A) Uses inline styles only\
B) Uses CSS directly\
C) Uses JavaScript objects to define styles\
D) Doesn’t support styling\
**Answer:** C) Uses JavaScript objects to define styles

**7. What is the purpose of the TouchableOpacity component?**\
A) To create animations\
B) To handle touch events with opacity feedback\
C) To add navigation between screens\
D) To create modals\
**Answer:** B) To handle touch events with opacity feedback

**8. Which hook is commonly used to manage state in React Native functional components?**\
A) useEffect\
B) useReducer\
C) useState\
D) useContext\
**Answer:** C) useState

**9. Which navigation library is most widely used in React Native?**\
A) React Router\
B) React Native Navigator\
C) React Navigation\
D) Native Router\
**Answer:** C) React Navigation

**10. What is the default thread used to run JavaScript code in React Native?**\
A) Main UI Thread\
B) JS Thread\
C) Native Module Thread\
D) Worker Thread\
**Answer:** B) JS Thread

**11. Which command runs a React Native app on an Android emulator?**\
A) npm start android\
B) npx react-native android\
C) npx react-native run-android\
D) expo run android\
**Answer:** C) npx react-native run-android

**12. Which component is best suited for rendering a long list of data efficiently?**\
A) `<ScrollView>`\
B) `<FlatList>`\
C) `<View>`\
D) `<List>`\
**Answer:** B) `<FlatList>`

**13. In React Native, text must always be wrapped inside which component?**\
A) `<Label>`\
B) `<Text>`\
C) `<Paragraph>`\
D) `<View>`\
**Answer:** B) `<Text>`

**14. How do you apply multiple styles in React Native?**\
A) `style={style1 + style2}`\
B) `style={[style1, style2]}`\
C) `style={merge(style1, style2)}`\
D) `style={style1, style2}`\
**Answer:** B) `style={[style1, style2]}`

**15. Which of the following is true about Expo?**\
A) It simplifies building React Native apps\
B) It requires Android Studio or Xcode for basic setup\
C) It doesn’t support over-the-air updates\
D) It is not open-source\
**Answer:** A) It simplifies building React Native apps

**16. Which lifecycle method is used in React Native class components to perform side effects after the first render?**\
A) `componentDidMount()`\
B) `componentWillMount()`\
C) `componentWillUnmount()`\
D) `componentDidUpdate()`\
**Answer:** A) componentDidMount()

**17. What is the default flex direction in React Native?**\
A) `row`\
B) `column`\
C) `row-reverse`\
D) `inherit`\
**Answer:** B) `column`

**18. Which command starts the Metro bundler?**\
A) `npm start`\
B) `npx react-native start`\
C) `expo start`\
D) All of the above (depending on setup)\
**Answer:** D) All of the above (depending on setup)

**19. How do you debug a React Native app?**\
A) Using Chrome DevTools\
B) Using React Native Debugger\
C) Using Flipper\
D) All of the above\
**Answer:** D) All of the above

**20. Which of the following is NOT a core React Native component?**\
A) `<Image>`\
B) `<View>`\
C) `<ScrollView>`\
D) `<Fragment>`\
**Answer:** D) `<Fragment>`

### Advanced
**1. In React Native, how are native modules typically connected to JavaScript code?**\
A) Using Redux\
B) Using the Native Bridge\
C) Using Context API\
D) Using WebSockets\
**Answer:** B) Using the Native Bridge

**2. What is the purpose of the `useEffect` hook’s dependency array?**\
A) To define styles\
B) To control when the effect runs\
C) To declare state variables\
D) To prevent re-renders\
**Answer:** B) To control when the effect runs

**3. Which React Native component provides a performant way to render large grouped lists?**\
A) `<FlatList>`\
B) `<ScrollView>`\
C) `<SectionList>`\
D) `<ListView>`\
**Answer:** C) `<SectionList>`

**4. What is the primary purpose of `React.memo`?**\
A) To prevent component unmounting\
B) To memoize expensive calculations\
C) To prevent unnecessary re-renders of functional components\
D) To store global state\
**Answer:** C) To prevent unnecessary re-renders of functional components

**5. How does React Native handle styling differently from React (web)?**\
A) Inline styles are not supported\
B) It uses JavaScript objects instead of CSS\
C) It requires external libraries for styling\
D) It has built-in CSS support\
**Answer:** B) It uses JavaScript objects instead of CSS

**6. Which hook would you use for performance optimization when passing functions as props?**\
A) `useState`\
B) `useEffect`\
C) `useCallback`\
D) `useMemo`\
**Answer:** C) `useCallback`

**7. How does `useMemo` differ from `useCallback`?**\
A) `useMemo` memoizes values, `useCallback` memoizes functions\
B) `useMemo` works with arrays, `useCallback` works with objects\
C) `useMemo` is for class components, `useCallback` for functional\
D) They are identical in functionality\
**Answer:** A) `useMemo` memoizes values, `useCallback` memoizes functions

**8. Which navigation type is best for tab-based navigation?**\
A) Stack Navigator\
B) Drawer Navigator\
C) Bottom Tab Navigator\
D) Switch Navigator\
**Answer:** C) Bottom Tab Navigator

**9. What is the role of Metro bundler in React Native?**\
A) Handles navigation\
B) Compiles JavaScript and bundles assets\
C) Manages database connections\
D) Provides UI components\
**Answer:** B) Compiles JavaScript and bundles assets

**10. In React Native, how are images bundled by default?**\
A) As inline base64 strings\
B) As separate assets packaged with the app\
C) As CDN links\
D) They are not bundled automatically\
**Answer:** B) As separate assets packaged with the app

**11. Which hook replaces `componentDidMount` and `componentWillUnmount` in functional components?**\
A) `useState`\
B) `useEffect`\
C) `useReducer`\
D) `useLayoutEffect`\
**Answer:** B) `useEffect`

**12. What is the purpose of `useRef` in React Native?**\
A) To store global state\
B) To reference DOM/native elements or persist values across renders\
C) To trigger re-renders\
D) To memoize functions\
**Answer:** B) To reference DOM/native elements or persist values across renders

**13. How can you improve FlatList performance in React Native?**\
A) Use `keyExtractor`\
B) Use `getItemLayout`\
C) Use `initialNumToRender`\
D) All of the above\
**Answer:** D) All of the above

**14. What is the difference between `useLayoutEffect` and `useEffect`?**\
A) `useLayoutEffect` runs asynchronously, `useEffect` synchronously\
B) `useLayoutEffect` runs before the screen paints, `useEffect` after\
C) `useEffect` can only be used in class components\
D) There is no difference\
**Answer:** B) `useLayoutEffect` runs before the screen paints, `useEffect` after

**15. What does `Hermes` do in React Native?**\
A) Provides navigation\
B) Optimizes JavaScript execution\
C) Manages app state\
D) Provides animations\
**Answer:** B) Optimizes JavaScript execution

**16. Which of the following libraries is commonly used for animations in React Native?**\
A) Lodash\
B) React Native Reanimated\
C) Redux Toolkit\
D) Axios\
**Answer:** B) React Native Reanimated

**17. What is the primary advantage of Redux Toolkit over plain Redux?**\
A) It is slower but simpler\
B) It eliminates the need for reducers\
C) It reduces boilerplate and simplifies store setup\
D) It only works with React Native\
**Answer:** C) It reduces boilerplate and simplifies store setup

**18. Which of the following APIs allows direct communication between React Native and device hardware?**\
A) AsyncStorage\
B) Native Modules\
C) Context API\
D) JSX\
**Answer:** B) Native Modules

**19. What happens if you don’t provide a unique `key` prop in a list?**\
A) App crashes\
B) Items may not render correctly and cause performance issues\
C) Nothing happens\
D) FlatList won’t render\
**Answer:** B) Items may not render correctly and cause performance issues

**20. Which thread is responsible for rendering UI updates in React Native?**\
A) JS Thread\
B) UI (Main) Thread\
C) Native Module Thread\
D) Worker Thread\
**Answer:** B) UI (Main) Thread

# React MCQs
### Basic
**1. What is JSX in React?**\
A) A CSS framework\
B) A syntax extension for JavaScript to write UI elements\
C) A JSON format\
D) A templating engine\
**Answer:** B) A syntax extension for JavaScript to write UI elements

**2. What is the purpose of `props` in React?**\
A) To store internal component state\
B) To pass data from parent to child components\
C) To manage global state\
D) To apply styles\
**Answer:** B) To pass data from parent to child components

**3. Which hook is used to declare state in functional components?**\
A) `useEffect`\
B) `useContext`\
C) `useState`\
D) `useReducer`\
**Answer:** C) `useState`

**4. What happens when you update state using `setState` (or `useState`)?**\
A) The state updates immediately without re-rendering\
B) The component re-renders with the new state\
C) The state does not change\
D) It clears all props\
**Answer:** B) The component re-renders with the new state

**5. Which React hook is used for side effects like API calls or subscriptions?**\
A) `useEffect`\
B) `useMemo`\
C) `useReducer`\
D) `useCallback`\
**Answer:** A) `useEffect`

**6. In React, what must you provide when rendering a list of elements?**\
A) A `ref`\
B) A `className`\
C) A `key` prop\
D) A `style`\
**Answer:** C) A `key` prop

**7. What is the difference between props and state?**\
A) Props are mutable, state is immutable\
B) Props are for parent-to-child data, state is managed inside a component\
C) Both are used only in class components\
D) They are identical\
**Answer:** B) Props are for parent-to-child data, state is managed inside a component

**8. Which hook is used for sharing data without passing props through every level of the component tree?**\
A) `useMemo`\
B) `useReducer`\
C) `useContext`\
D) `useEffect`\
**Answer:** C) `useContext`

**9. What is the default behavior of React components when state or props change?**\
A) They unmount\
B) They re-render\
C) They stay the same\
D) They reset all state\
**Answer:** B) They re-render

**10. What is the correct way to update state in React?**\
A) `state.count = 5`\
B) `setCount(count + 1)`\
C) `this.count++`\
D) `count = count + 1`\
**Answer:** B) `setCount(count + 1)`

**11. Which hook is used to access the previous state values or persist mutable values?**\
A) `useReducer`\
B) `useRef`\
C) `useMemo`\
D) `useEffect`\
**Answer:** B) `useRef`

**12. What is React.Fragment (`<>...</>`) used for?**\
A) Wrapping multiple elements without adding extra nodes to the DOM tree\
B) Styling components\
C) Handling errors\
D) Managing state\
**Answer:** A) Wrapping multiple elements without adding extra nodes to the DOM tree

**13. Which hook is best for expensive calculations that should not run on every render?**\
A) `useEffect`\
B) `useMemo`\
C) `useRef`\
D) `useState`\
**Answer:** B) `useMemo`

**14. In class components, which method is similar to `useEffect` with an empty dependency array?**\
A) `componentDidUpdate`\
B) `componentDidMount`\
C) `componentWillUnmount`\
D) `render`\
**Answer:** B) `componentDidMount`

**15. What is the purpose of `React.StrictMode`?**\
A) To prevent re-renders\
B) To highlight potential problems in an app during development\
C) To enforce TypeScript types\
D) To optimize performance automatically\
**Answer:** B) To highlight potential problems in an app during development

**16. What does `useReducer` provide compared to `useState`?**\
A) A way to manage complex state logic with actions and reducers\
B) A faster alternative to `useState`\
C) A replacement for `useEffect`\
D) A way to manage props\
**Answer:** A) A way to manage complex state logic with actions and reducers

**17. What is the correct way to conditionally render elements in React?**\
A) Using `if` statements inside JSX\
B) Using ternary operators or logical AND (`&&`)\
C) Using `while` loops in JSX\
D) Rendering everything and hiding with CSS\
**Answer:** B) Using ternary operators or logical AND (`&&`)

**18. What is the return value of `useState`?**\
A) The state value and a function to update it\
B) Only the state value\
C) Only the setter function\
D) An object with `state` and `setState` keys\
**Answer:** A) The state value and a function to update it

**19. Which hook should you use for cleanup (like removing event listeners)?**\
A) `useReducer`\
B) `useEffect` with a cleanup function\
C) `useState`\
D) `useMemo`\
**Answer:** B) `useEffect` with a cleanup function

**20. In React, why should keys in a list be unique?**\
A) To avoid duplicate props\
B) To help React identify which items changed, added, or removed\
C) To improve styling\
D) To prevent re-renders completely\
**Answer:** B) To help React identify which items changed, added, or removed
