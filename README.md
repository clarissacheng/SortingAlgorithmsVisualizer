# React App to visualize Sorting Algorithms

This app is a visual way to see sorting algorithms like Merge Sort, Quick Sort, Selection Sort, and Bubble Sort in action. Available at: (https://clarissacheng.github.io/SortingAlgorithmsVisualizer/)

## Implementation

By clicking 'Generate Array' the user generates a number array of length 250 which is stored in the SortingVisualizer object's state. This is translated into array bars by looping over the array and giving each bar a height of 0.1% times the value of the array.

By clicking on the button for any given algorithm, the user can see the array bars being sorted where the height of the bar represents a value in an array of numbers.

## The Algorithms

The file sortingAlgorithms.js contains the logic and implementation for each sorting algorithm. The algorithms are then translated into animations that I pass into the relevant algorithms inside SortingVisualizer.jsx which finally translates these animations into height values for the array bars in the visualizer.

## The Future

In the future, I will be implementing a toggle where the user can switch between a single algorithm view to a comparison window where multiple algorithms can be run in parallel for comparison.
