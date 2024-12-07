# React useEffect Hook with Empty Dependency Array

This repository demonstrates a common error in React's `useEffect` hook: using an empty dependency array `[]` when the effect should actually depend on a state variable. This leads to the effect running only once after the component mounts, even if the state variable changes. 

The `bug.js` file shows the incorrect implementation with an empty dependency array resulting in the console log only appearing on the initial render.  The `bugSolution.js` file demonstrates the correct implementation with a state variable in the dependency array, leading to the effect running whenever the state changes. 