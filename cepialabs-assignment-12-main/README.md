# Introduction

- Name - Harsh Jain
- Email - [harshkmjain3@gmail.com]

## Fetch Users using Redux Async Thunk

- This repo Fetches Users using Redux Async Thunk.
- Run:

```sh
npm install
npm run dev
```


---

# **React Assignment Day 7 Quiz**

## **1.Redux is primarily used for ____ in React applications.**  
**Answer:** b) Managing application state

---

## **2.In Redux, what does the Store represent?**  
**Answer:** b) A central container for the application state

---

## **3. Which function is used to create a Redux store in Redux Toolkit?**  
**Answer:** c) configureStore()

---

## **4. The createSlice() function is used to ____**  
**Answer:** a) Write reducers and actions together

---

## **5. What is the purpose of the Provider component in React-Redux?**  
**Answer:** a) To wrap the app and make the store available to all components

---

## **6. Which hook is used to read data from the Redux store?**
**Answer:**  b) useSelector()

---

## **7.  Which hook is used to send actions to the Redux store?**
**Answer:** a) useDispatch()

---

## **8.  Which method is used for handling asynchronous operations in Redux Toolkit?**  
**Answer:** c) createAsyncThunk()

---

## **9.  What is the best way to store data that should persist between browser sessions?**  
**Answer:** b) localStorage

---

## **10. In Redux Toolkit, reducers should be ____**
**Answer:** b) Pure functions

---


# **React Assignment Day 7 Short Answer**


---

## **1. What is Redux and why is it used in React applications?**
**Answer:** Redux is a predictable state management library that centralizes the application's state in a single store.
It is used in React to help manage complex state logic, make debugging easier, enable predictable data flow, and share state across multiple components without prop drilling.

---

## **2. Explain the difference between useSelector() and useDispatch() hooks.**
**Answer:** useSelector() is used to read data from the Redux store. It lets components subscribe to specific pieces of state.

useDispatch() is used to send actions to the Redux store. It allows components to trigger state updates.

---

## **3. What is the role of a reducer in Redux?**
**Answer:** A reducer is a pure function that takes the current state and an action, then returns a new updated state.
It defines how the application's state changes in response to dispatched actions.

---

## **4. How does createAsyncThunk() help in Redux Toolkit?**
**Answer:**createAsyncThunk() simplifies handling asynchronous operations (like API calls) by automatically generating pending, fulfilled, and rejected action types.
It reduces boilerplate and integrates smoothly with slices for managing loading and error states.

---

## **5. What is the purpose of the Provider component from react-redux?**
**Answer:** The Provider component wraps the React application and makes the Redux store available to all nested components.
Without Provider, components would not be able to access the store using hooks like useSelector or useDispatch.


---