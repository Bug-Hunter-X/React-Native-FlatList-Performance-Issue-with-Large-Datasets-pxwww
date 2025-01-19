# React Native FlatList Performance Issue

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and provides a solution.  Failure to implement a correct `keyExtractor` function can lead to inefficient rendering and potential crashes. The `FlatListBug.js` file shows the problem, while `FlatListBugSolution.js` presents the solution.

## Problem
The `FlatListBug.js` file shows how a missing or inefficient `keyExtractor` function can significantly impact performance when rendering a large number of items.  Observe the slow rendering or potential crashes when scrolling through the list.