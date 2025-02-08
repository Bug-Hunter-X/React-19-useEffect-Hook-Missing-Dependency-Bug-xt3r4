# React 19 useEffect Hook Missing Dependency Bug
This repository demonstrates a common bug in React 19 related to the `useEffect` hook.  The bug arises from omitting necessary dependencies in the `useEffect` dependency array, leading to unexpected re-renders and potentially incorrect behavior.

## Bug Description
The bug is the result of an improperly configured `useEffect` hook.  Missing dependencies in the dependency array leads to unexpected behavior in the `useEffect` callback.