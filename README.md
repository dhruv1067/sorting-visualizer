# Sorting Algorithm Visualizer

An interactive web-based **Sorting Algorithm Visualizer** built with
HTML, CSS, and JavaScript. The project demonstrates how popular sorting
algorithms work by animating their operations step by step, making it
easier to understand concepts such as comparisons, swaps, partitioning,
merging, and heap construction.

## ✨ Features

-   Visualizes multiple sorting algorithms in real time
-   Animated comparison and swapping operations
-   Adjustable array visualization
-   Clean and responsive interface
-   Helps compare different sorting approaches
-   Implemented using vanilla JavaScript without external frameworks

## 🧩 Sorting Algorithms

The project currently includes:

  Algorithm          Average Time   Worst Time        Space
  ---------------- -------------- ------------ ------------
  Bubble Sort               O(n²)        O(n²)         O(1)
  Insertion Sort            O(n²)        O(n²)         O(1)
  Selection Sort            O(n²)        O(n²)         O(1)
  Merge Sort           O(n log n)   O(n log n)         O(n)
  Quick Sort           O(n log n)        O(n²)   O(log n)\*
  Heap Sort            O(n log n)   O(n log n)         O(1)

\*Space complexity for Quick Sort refers to the typical recursive stack
usage; it can become O(n) in the worst case.

## 📁 Project Structure

``` text
Sorting-Visualizer/
│
├── index.html
├── style.scss
├── README.md
│
├── main.js
├── visualizations.js
│
├── bubble_sort.js
├── insertion_sort.js
├── selection_sort.js
├── merge_sort.js
├── quick_sort.js
└── heap_sort.js
```

### File Overview

-   **`index.html`** --- Main structure and layout of the visualizer.
-   **`style.scss`** --- Styling and visual appearance of the
    application.
-   **`main.js`** --- Handles the main application logic and user
    interactions.
-   **`visualizations.js`** --- Controls array visualization and
    animation-related functionality.
-   **`bubble_sort.js`** --- Bubble Sort implementation.
-   **`insertion_sort.js`** --- Insertion Sort implementation.
-   **`selection_sort.js`** --- Selection Sort implementation.
-   **`merge_sort.js`** --- Merge Sort implementation.
-   **`quick_sort.js`** --- Quick Sort implementation.
-   **`heap_sort.js`** --- Heap Sort implementation.

## 🛠️ Technologies Used

-   **HTML5** --- Page structure
-   **CSS / SCSS** --- Styling and layout
-   **JavaScript (ES6+)** --- Sorting algorithms, DOM manipulation, and
    animations

## 🚀 Getting Started

### 1. Clone the repository

``` bash
git clone https://github.com/your-username/sorting-visualizer.git
```

### 2. Open the project

Navigate to the project directory:

``` bash
cd sorting-visualizer
```

### 3. Run the visualizer

Open `index.html` in a web browser.

For the best development experience, you can use **VS Code with Live
Server** and launch `index.html`.

## 🧠 How It Works

The application generates an array of values and represents each value
visually using bars of different heights.

When a sorting algorithm is selected, the corresponding JavaScript
implementation processes the array while the visualization layer
displays the operations performed by the algorithm.

For example:

1.  The algorithm selects elements to compare.
2.  The visualization highlights the relevant elements.
3.  Comparisons or swaps are animated.
4.  The array gradually moves toward its sorted state.
5.  Once the algorithm finishes, the sorted array is displayed.

This separates the **sorting logic** from the **visualization logic**,
making the project easier to understand and extend.

## 📊 Algorithms Demonstrated

### Bubble Sort

Repeatedly compares adjacent elements and swaps them when they are in
the wrong order. Larger elements gradually move toward the end of the
array.

### Insertion Sort

Builds the sorted portion of the array one element at a time by
inserting each new element into its appropriate position.

### Selection Sort

Repeatedly finds the smallest element from the unsorted portion and
places it at the beginning of that portion.

### Merge Sort

Uses the divide-and-conquer approach. The array is recursively divided
into smaller sections and then merged back together in sorted order.

### Quick Sort

Uses a pivot to partition the array into smaller and larger elements,
then recursively sorts the resulting partitions.

### Heap Sort

Builds a heap data structure and repeatedly extracts the largest element
to produce the sorted array.

## 🎯 Learning Objectives

This project was developed to strengthen understanding of:

-   Sorting algorithms and their complexity
-   JavaScript programming
-   DOM manipulation
-   Asynchronous animations
-   Algorithm visualization
-   Time and space complexity
-   Modular code organization
-   Front-end development fundamentals

## 🔮 Possible Improvements

Future versions could include:

-   Sorting speed controls
-   Array size controls
-   Algorithm performance comparison
-   Number of comparisons and swaps
-   Execution-time statistics
-   Additional algorithms such as Shell Sort, Counting Sort, Radix Sort,
    and Bucket Sort
-   Dark/light theme
-   Mobile UI improvements

## 📌 Project Purpose

The goal of this project is to make sorting algorithms **interactive and
intuitive** rather than relying only on static code or theoretical
explanations. By watching comparisons and rearrangements happen
visually, users can develop a better understanding of how different
algorithms behave and how their time complexities affect performance.

## 👨‍💻 Author

**Dhruv**\
Chemical Engineering Student --- NIT Jalandhar

------------------------------------------------------------------------

⭐ If you found this project useful, consider giving the repository a
star!
