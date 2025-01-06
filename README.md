# React useEffect Hook Unexpected Behavior
This repository demonstrates a common issue encountered with React's `useEffect` hook where the effect function isn't triggered on every state update, despite the apparent intention.

## Problem
The provided code uses `useEffect` to log a message to the console.  The expectation is the message would appear every time the `count` state variable changes. However, because of the empty dependency array `[]`, it only runs once after the initial render.