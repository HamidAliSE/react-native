# React Native MCQs
### Core Concepts
**Which language is primarily used to build React Native apps?**\
A) Java\
B) Swift\
C) JavaScript\
D) Kotlin\
**Answer:** C) JavaScript

**What is the main difference between ReactJS and React Native?**\
A) ReactJS is used for web, React Native for mobile\
B) ReactJS uses HTML, React Native uses native components\
C) React Native can access device APIs\
D) All of the above\
**Answer:** D) All of the above

### Core Components
**Which of the following is NOT a core React Native component?**\
A) `<Image>`\
B) `<View>`\
C) `<ScrollView>`\
D) `<Fragment>`\
**Answer:** D) `<Fragment>`

**In React Native, text must always be wrapped inside which component?**\
A) `<Label>`\
B) `<Text>`\
C) `<Paragraph>`\
D) `<View>`\
**Answer:** B) `<Text>`

**Which component is used to display scrollable content in React Native?**\
A) `<ListView>`\
B) `<ScrollView>`\
C) `<FlatList>`\
D) `<SectionList>`\
**Answer:** B) `<ScrollView>`

**In React Native, which of the following is used instead of HTML `<div>`?**\
A) `<View>`\
B) `<Container>`\
C) `<Box>`\
D) `<Layout>`\
**Answer:** A) `<View>`

**What is the purpose of the TouchableOpacity component?**\
A) To create animations\
B) To handle touch events with opacity feedback\
C) To add navigation between screens\
D) To create modals\
**Answer:** B) To handle touch events with opacity feedback

**Which component is best suited for rendering a long list of data efficiently?**\
A) `<ScrollView>`\
B) `<FlatList>`\
C) `<View>`\
D) `<List>`\
**Answer:** B) `<FlatList>`

### Styling
**Which of the following is true about React Native styling?**\
A) Uses inline styles only\
B) Uses CSS directly\
C) Uses JavaScript objects to define styles\
D) Doesn’t support styling\
**Answer:** C) Uses JavaScript objects to define styles

**How do you apply multiple styles in React Native?**\
A) `style={style1 + style2}`\
B) `style={[style1, style2]}`\
C) `style={merge(style1, style2)}`\
D) `style={style1, style2}`\
**Answer:** B) `style={[style1, style2]}`

### Hooks
**Which hook is commonly used to manage state in React Native functional components?**\
A) useEffect\
B) useReducer\
C) useState\
D) useContext\
**Answer:** C) useState

### Navigation
**Which navigation library is most widely used in React Native?**\
A) React Router\
B) React Native Navigator\
C) React Navigation\
D) Native Router\
**Answer:** C) React Navigation

### Threads
**What is the default thread used to run JavaScript code in React Native?**\
A) Main UI Thread\
B) JS Thread\
C) Native Module Thread\
D) Worker Thread\
**Answer:** B) JS Thread

### Development
**Which command runs a React Native app on an Android emulator?**\
A) npm start android\
B) npx react-native android\
C) npx react-native run-android\
D) expo run android\
**Answer:** C) npx react-native run-android

### Expo
**Which of the following is true about Expo?**\
A) It simplifies building React Native apps\
B) It requires Android Studio or Xcode for basic setup\
C) It doesn’t support over-the-air updates\
D) It is not open-source\
**Answer:** A) It simplifies building React Native apps

### Lifecycle of a Component
**Which lifecycle method is used in React Native class components to perform side effects after the first render?**\
A) `componentDidMount()`\
B) `componentWillMount()`\
C) `componentWillUnmount()`\
D) `componentDidUpdate()`\
**Answer:** A) componentDidMount()

### Flex Box
**What is the default flex direction in React Native?**\
A) `row`\
B) `column`\
C) `row-reverse`\
D) `inherit`\
**Answer:** B) `column`

### Metro
**Which command starts the Metro bundler?**\
A) `npm start`\
B) `npx react-native start`\
C) `expo start`\
D) All of the above (depending on setup)\
**Answer:** D) All of the above (depending on setup)

### Debugging
**How do you debug a React Native app?**\
A) Using Chrome DevTools\
B) Using React Native Debugger\
C) Using Flipper\
D) All of the above\
**Answer:** D) All of the above

### Advanced
**In React Native, how are native modules typically connected to JavaScript code?**\
A) Using Redux\
B) Using the Native Bridge\
C) Using Context API\
D) Using WebSockets\
**Answer:** B) Using the Native Bridge

**What is the purpose of the `useEffect` hook’s dependency array?**\
A) To define styles\
B) To control when the effect runs\
C) To declare state variables\
D) To prevent re-renders\
**Answer:** B) To control when the effect runs

**Which React Native component provides a performant way to render large grouped lists?**\
A) `<FlatList>`\
B) `<ScrollView>`\
C) `<SectionList>`\
D) `<ListView>`\
**Answer:** C) `<SectionList>`

**What is the primary purpose of `React.memo`?**\
A) To prevent component unmounting\
B) To memoize expensive calculations\
C) To prevent unnecessary re-renders of functional components\
D) To store global state\
**Answer:** C) To prevent unnecessary re-renders of functional components

**How does React Native handle styling differently from React (web)?**\
A) Inline styles are not supported\
B) It uses JavaScript objects instead of CSS\
C) It requires external libraries for styling\
D) It has built-in CSS support\
**Answer:** B) It uses JavaScript objects instead of CSS

**Which hook would you use for performance optimization when passing functions as props?**\
A) `useState`\
B) `useEffect`\
C) `useCallback`\
D) `useMemo`\
**Answer:** C) `useCallback`

**How does `useMemo` differ from `useCallback`?**\
A) `useMemo` memoizes values, `useCallback` memoizes functions\
B) `useMemo` works with arrays, `useCallback` works with objects\
C) `useMemo` is for class components, `useCallback` for functional\
D) They are identical in functionality\
**Answer:** A) `useMemo` memoizes values, `useCallback` memoizes functions

**Which navigation type is best for tab-based navigation?**\
A) Stack Navigator\
B) Drawer Navigator\
C) Bottom Tab Navigator\
D) Switch Navigator\
**Answer:** C) Bottom Tab Navigator

**What is the role of Metro bundler in React Native?**\
A) Handles navigation\
B) Compiles JavaScript and bundles assets\
C) Manages database connections\
D) Provides UI components\
**Answer:** B) Compiles JavaScript and bundles assets

**In React Native, how are images bundled by default?**\
A) As inline base64 strings\
B) As separate assets packaged with the app\
C) As CDN links\
D) They are not bundled automatically\
**Answer:** B) As separate assets packaged with the app

**Which hook replaces `componentDidMount` and `componentWillUnmount` in functional components?**\
A) `useState`\
B) `useEffect`\
C) `useReducer`\
D) `useLayoutEffect`\
**Answer:** B) `useEffect`

**What is the purpose of `useRef` in React Native?**\
A) To store global state\
B) To reference DOM/native elements or persist values across renders\
C) To trigger re-renders\
D) To memoize functions\
**Answer:** B) To reference DOM/native elements or persist values across renders

**How can you improve FlatList performance in React Native?**\
A) Use `keyExtractor`\
B) Use `getItemLayout`\
C) Use `initialNumToRender`\
D) All of the above\
**Answer:** D) All of the above

**What is the difference between `useLayoutEffect` and `useEffect`?**\
A) `useLayoutEffect` runs asynchronously, `useEffect` synchronously\
B) `useLayoutEffect` runs before the screen paints, `useEffect` after\
C) `useEffect` can only be used in class components\
D) There is no difference\
**Answer:** B) `useLayoutEffect` runs before the screen paints, `useEffect` after

**What does `Hermes` do in React Native?**\
A) Provides navigation\
B) Optimizes JavaScript execution\
C) Manages app state\
D) Provides animations\
**Answer:** B) Optimizes JavaScript execution

**Which of the following libraries is commonly used for animations in React Native?**\
A) Lodash\
B) React Native Reanimated\
C) Redux Toolkit\
D) Axios\
**Answer:** B) React Native Reanimated

**What is the primary advantage of Redux Toolkit over plain Redux?**\
A) It is slower but simpler\
B) It eliminates the need for reducers\
C) It reduces boilerplate and simplifies store setup\
D) It only works with React Native\
**Answer:** C) It reduces boilerplate and simplifies store setup

**Which of the following APIs allows direct communication between React Native and device hardware?**\
A) AsyncStorage\
B) Native Modules\
C) Context API\
D) JSX\
**Answer:** B) Native Modules

**What happens if you don’t provide a unique `key` prop in a list?**\
A) App crashes\
B) Items may not render correctly and cause performance issues\
C) Nothing happens\
D) FlatList won’t render\
**Answer:** B) Items may not render correctly and cause performance issues

**Which thread is responsible for rendering UI updates in React Native?**\
A) JS Thread\
B) UI (Main) Thread\
C) Native Module Thread\
D) Worker Thread\
**Answer:** B) UI (Main) Thread
